# Milan Desk: HomeLAB created for Help Desk Ticketing System

## Overview

Hi, I’m Aashutosh Sapkota, but you can call me Milan. This project is my deep dive into understanding and configuring a full-fledged help desk ticketing system using open source ticketing system called osTicket. 

My primary goal was to gain practical, hands-on experience with a real-world help desk system—something I hadn’t had the opportunity to do professionally. So, I decided to create my own environment from scratch on a cloud-based server.

The idea behind this project was to simulate a real IT support scenario, where managing customer inquiries, tracking tickets, and ensuring timely resolutions are key. By setting up this system, I aimed to demonstrate my capability to implement, configure, and manage a help desk system that is both functional and secure.

## Why I Did It

I’ve always been interested in how help desk systems work, especially in IT environments where efficient ticket management is crucial. However, without direct experience in such a setting, I needed to create a project that would allow me to:

- **Learn by Doing**: I wanted to move beyond theoretical knowledge and get hands-on with a system that’s widely used in the industry.

- **Showcase My Abilities**: This project is my way of demonstrating that I can set up and manage a help desk system, from installation to full operation. And although I may lack a lot of experience I am willing to learn whatever it takes!

## What I Did

### 1. **Server and Environment Setup**

- **Deployed on DigitalOcean**: I started by spinning up an Ubuntu 20.04 LTS server on a DigitalOcean droplet. 
- **Installed LAMP Stack**: I configured the server with the LAMP stack (Linux, Apache, MySQL, PHP)
- **Apache Configuration**:I configured Apache to serve the osTicket web application.
- 
### 2. **SQL Database Configuration and Security**

- **Database Setup**: I created a dedicated MySQL database for osTicket, ensuring all ticket data would be securely stored.
  
- **User Management**: To enhance security, I set up specific MySQL users with minimal necessary permissions, preventing unauthorized access and reducing the risk of potential breaches.
  
- **SSL Encryption**: Configured SSL for MySQL connections to protect data during transmission, ensuring all interactions with the database were encrypted.
  
- **Automated Backups**: Implemented automated backups to safeguard data, ensuring that even in the event of a failure, no critical information would be lost.


### 3. **osTicket Customization**

- **Departments and Roles**: I structured the help desk into multiple support levels (Level 1, Level 2, Level 3), each with its own department and specific roles.
  
- **Service Level Agreements (SLAs)**: I set up SLAs to ensure timely ticket resolution, with automatic flagging and escalation if deadlines aren't met.

Additionally, I developed a Node.js API that continuously monitors ticket statuses, simulating real-time SMS alerts via Twilio API to notify higher-ups for immediate escalation when necessary.

### 4. **User Management and Security**

- **Role-Based Access Control**: Created and managed user roles, ensuring that agents only have access to the information they need. This minimizes risks and keeps sensitive data secure.
  
## Try It Out

You can log in and explore the system using the following credentials:

- **Usernames**: `level1user`, `level2user`, `level3user`
- **Password**: `Password`

If you’re interested in seeing the admin side, feel free to request access by emailing me at `ost@itsmeaashutoshsapkota.com`.




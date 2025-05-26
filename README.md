# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket installer
- osTicket Admin Control Panel

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


# osTicket: Post-Installation Configuration

This project provides a comprehensive guide and configuration files for post-installation setup of osTicket. Follow the steps outlined in this repository to properly configure your osTicket installation after the initial setup.

## Table of Contents
1. [Introduction](#introduction)
2. [Post-Installation Configuration Steps](#post-installation-configuration-steps)
3. [Customizing osTicket](#customizing-osticket)
4. [Sample Configuration Files](#sample-configuration-files)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

osTicket is an open-source support ticket system designed to manage and streamline customer support workflows. After you have successfully installed osTicket, there are several key configuration steps that are required to optimize its performance and functionality. This repository will guide you through that process.

## Post-Installation Configuration Steps

The post-installation configuration of osTicket typically includes:
1. **Email Setup**
   - Configure outgoing and incoming mail.
   - Set up email templates.
2. **Department Setup**
   - Create and configure departments for routing tickets.
3. **Agent Configuration**
   - Create agent accounts and assign roles.
4. **Theme Customization**
   - Customize the ticket portal theme.
5. **Security Enhancements**
   - Change default passwords and configure two-factor authentication (2FA).
6. **System Preferences**
   - Modify global settings for the system.

## Customizing osTicket

Learn how to customize and extend your osTicket installation with plugins, custom fields, and other configurations.

## Sample Configuration Files

This folder contains sample configuration files that can be used in your osTicket installation, including:
- `osticket.conf`: Custom configuration options for security and performance tuning.
- `email_templates.json`: Importable email templates.

## Contributing

If you have suggestions or improvements, feel free to fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the MIT License.



# osTicket Post-Installation Configuration Steps

Follow these steps to configure osTicket after the initial installation.

## 1. Email Configuration

### 1.1 Configure SMTP for Outgoing Email
To send email notifications and responses through osTicket, configure the SMTP settings:
- Go to **Admin Panel > Settings > Email**.
- Set the **SMTP Server** (e.g., smtp.gmail.com for Gmail).
- Enter your **SMTP Port**, **Username**, and **Password**.
- Test the connection to ensure it's working.

### 1.2 Set Up Email Piping for Incoming Tickets
Configure osTicket to automatically create tickets from incoming emails:
- Set up an email address like `support@yourdomain.com`.
- Configure your email server to forward incoming emails to the osTicket pipe script (`/include/ost-queue.php`).

## 2. Department Setup

Departments are used to categorize and route tickets. You can create and configure them under:
- **Admin Panel > Manage > Departments**.
- Create new departments based on your support team structure (e.g., Sales, Technical Support, Billing).

## 3. Agent Setup

Agents are the users who manage and respond to tickets. Set them up under:
- **Admin Panel > Manage > Agents**.
- Create agent accounts and assign them to departments.

## 4. Theme and Branding

osTicket provides a default theme that can be customized. You can upload your own logo, change the ticket portal’s colors, or modify the overall look under:
- **Admin Panel > Settings > Themes**.

## 5. Security Enhancements

### 5.1 Change Default Admin Password
Always change the default password after the installation. To do this, go to:
- **Admin Panel > Manage > Admins**.
- Edit the admin account and change the password.

### 5.2 Enable Two-Factor Authentication (2FA)
To enhance security, you can enable 2FA:
- **Admin Panel > Settings > Security**.
- Enable 2FA for admin and agent accounts.

## 6. System Preferences

Under **Admin Panel > Settings > Preferences**, you can adjust the following:
- **Ticket System Preferences**: Modify ticket creation settings, such as the number of tickets an agent can handle.
- **Locale Settings**: Set the timezone and language for your installation.
- MIT License

Copyright (c) 2024 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM,
OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

By setting up this GitHub repository, you'll be providing a valuable resource to the community. Users can easily follow the instructions to configure their osTicket installation post-installation, ensuring they get the most out of the system.

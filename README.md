# Injury-Tracking-System
It is a web application that can be used by an organization (such as the police) to easily record and track the injuries reported by a person


## Overview

The **Injury Tracking System** is a powerful web application designed to make injury reporting and tracking a breeze. Built with organizations like the police in mind, it simplifies the process of recording and managing injury reports.

## Key Features

### 📝 Report

- **Name of Reporter**: Easily enter the name of the person reporting the injury.

- **Date & Time of Injury**: Capture the exact date and time when the injury occurred.

- **Body Map Visualization**: A unique feature that allows users to mark and label areas of injury on a body map image. The system automatically numbers and labels each area, simplifying the documentation process.

- **List of Injuries**: For each marked area, users can provide detailed descriptions of the injuries, ensuring comprehensive and accurate records.

### 📄 List of Reports

- **Comprehensive Overview**: Users can access a table displaying all reported injuries, including the reporter's name, date and time of injury, and date of report.

- **Sortable and Searchable**: The system offers robust sorting, searching, and filtering capabilities, enabling users to quickly find and organize injury reports.

### 🔐 User Authentication

- **Secure Registration**: Users can easily register with the system using a username and password, with options for Google login and email login.

- **Auth0 Integration**: User authentication is implemented using Auth0, providing a reliable and secure authentication framework.

### 🎨 UI/UX

- **Grommet or Ant Design**: The application features a visually appealing and user-friendly interface built with Grommet or Ant as the design library.

- **Responsive Design**: The application is fully responsive, ensuring it works seamlessly on both desktop and mobile devices.

## Getting Started

Follow these steps to set up the Injury Tracking System locally:

```shell
# Clone the repository
git clone https://github.com/gdsc-ipsacademy/Injury-Tracking-System.git

# Navigate to the project directory
cd injury-tracking-system

# Install dependencies
npm install

# Start the application
npm run start
```


## Contributing

We welcome contributions from the community! Whether you're interested in bug fixes, new features, or improvements, please review our Contributing Guidelines for more details on how to get involved.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Bonus Features 
**📱 Progressive Web App (PWA)**
The Injury Tracking System is designed as a fully responsive Progressive Web App (PWA) that can be installed on your home screen, works offline, and offers an app-like experience across different devices and platforms.

**🎯 Automatic Location Detection**
In addition to numbering labeled areas, the system has the potential to automatically detect and label injury locations for enhanced convenience.

**📊 Analytics Dashboard**
We are exploring the possibility of integrating an analytics dashboard, which will provide visualizations of relevant metrics, enabling deeper insights into injury reports.

## Tech Stack
Front-end: Next.js with Grommet or Ant Design for UI components. State management is handled using React Context.

Back-end: GraphQL with Prisma as the ORM for database connectivity.

Authentication: Auth0 for user authentication, with options for Google login and email login.

Analytics: We are considering the use of data visualization libraries such as Chart.js or D3.js for potential analytics features.

Progressive Web App (PWA): The system is built with PWA features, offering an enhanced user experience.

Feel free to explore other tech stacks that align with your project goals.

### Contact

For inquiries and support, please reach out to [jainginni23@gmail.com].

Enjoy using the Injury Tracking System and thank you for being a part of our open-source community!

Personal Expense Tracker from Bank SMS

This is a personal project designed to create a simple, fast, and private way to track daily expenses by parsing transaction SMS messages from banks. The goal was to build a custom tool that integrates directly with Google Sheets, providing a secure and self-hosted alternative to commercial expense tracking apps.

Core Features

SMS Parsing: Intelligently extracts key details (Amount, Date, Type, Description) from raw bank SMS alerts.

Manual Categorization: A user-friendly interface to quickly assign a category and bank to each transaction before saving.

Google Sheets Integration: Acts as a front-end to a Google Sheet, using Google Apps Script as a simple, secure backend to save and retrieve all transaction data.

Financial Analytics: Provides a dashboard view with a breakdown of income vs. expense, net flow, and spending by category.

Secure Access: The application is protected by a simple password entry screen.

Fully Responsive: The UI is designed to be fully functional and easy to use on both desktop and mobile devices.

Why This Project?

This application was born out of a personal need for a straightforward expense tracker without the complexity, subscriptions, or privacy concerns of many commercial apps. By leveraging the transaction alerts I already receive via SMS, I wanted to create a tool that would allow me to log expenses in just a few seconds.

Building this project was also a great exercise in creating a full-stack, serverless application using modern front-end tools and integrating with Google's powerful ecosystem (Sheets and Apps Script). It demonstrates a practical application of web technologies to solve a real-world problem.

Technology Stack

Front-End: Plain HTML, Tailwind CSS, and JavaScript. No complex frameworks were used to keep the application lightweight and fast.

Backend & Database: Google Apps Script and a Google Sheet. This creates a powerful, free, and secure serverless backend.

UI Icons: Lucide Icons for a clean and modern look.

Setup & Usage

To use this application, you need to link it to your own Google Sheet by following these two main steps:

Set up the Google Sheet: Create a new Google Sheet with the required column headers (Timestamp, Date, Type, etc.).

Deploy the Google Apps Script: Paste the provided script into your sheet's Apps Script editor and deploy it as a Web App. This will generate a unique URL.

Configure the App: Paste the Web App URL into the settings of this application to connect it to your sheet.

For detailed instructions, please refer to the setup_guide.md and github_hosting_guide.md files.

This project is for

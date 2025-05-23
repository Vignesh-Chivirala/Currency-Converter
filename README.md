# Currency Converter Web Application


![Screenshot 2025-03-31 200820](https://github.com/user-attachments/assets/45811128-2204-4a54-b5a0-cb79135a5580)


## Overview: 
The Currency Converter is a web-based application that allows users to seamlessly convert values between different currencies. It leverages real-time exchange rates provided by an external API, ensuring accurate and up-to-date conversions. The application is built using HTML, CSS, and JavaScript to create an intuitive and user-friendly interface.

## ⚡️ Key Features:
🔄 1. Real-Time Currency Conversion
Users can select the source and target currencies from dropdown menus.

Upon entering an amount, the application fetches the latest exchange rate from the API and performs the conversion.

The result is displayed dynamically with two decimal precision.

## 🌐 2. API Integration with Fetch
The application uses the Fetch API to retrieve exchange rate data from a public API endpoint.

It sends a request to a URL (such as https://2024-03-06.currency-api.pages.dev/v1/currencies/) and processes the JSON response.

Error handling is included to manage scenarios such as network issues or invalid responses.

## 🎨 3. Intuitive User Interface (UI)
Clean and simple design with dropdowns for selecting currencies.

Input field to enter the amount to be converted.

A button triggers the conversion, and results are shown in a visually appealing format.

Optionally, the application displays country flags for the selected currencies to enhance the user experience.

## 🕹️ 4. Dropdown with Preloaded Currency Codes
The dropdowns are dynamically populated with available currency codes using a countryList object that maps currency codes to country names.

Default currencies are preselected (e.g., USD to INR for Indian users).

## Technical Stack:

### 📚 Frontend:
HTML: Structure of the application.<br>
CSS: Styling and responsiveness.<br>
JavaScript: Handles business logic, API calls, and UI updates.


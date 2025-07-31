# Event Registration App (Azure Serverless)

This is a simple serverless event registration app using Azure Functions and Cosmos DB.

## 💻 Tech Stack
- Frontend: HTML/CSS + JavaScript
- Backend: Azure Functions (JavaScript)
- Database: Azure Cosmos DB (SQL API)

## 🚀 Setup Instructions

1. Deploy the `RegisterUser` Azure Function with your Cosmos DB connection string in app settings as `COSMOS_CONNECTION`.
2. Update the frontend form to use your Function App's endpoint.
3. Host the frontend using Azure Blob Static Website, GitHub Pages, or Netlify.

## 📂 Folder Structure

- `frontend/`: Contains the registration form.
- `azure-function/`: Contains the Azure Function to store data in Cosmos DB.

## 🛡️ License
MIT

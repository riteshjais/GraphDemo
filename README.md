# ASP.NET Core 7 Microsoft Graph Email Application

## Overview

This small ASP.NET Core 7 application demonstrates how to interact with Microsoft Graph API to retrieve user emails and send emails using Microsoft Outlook. The application uses OAuth 2.0 authentication to obtain an access token for making secure API calls to Microsoft Graph.

## Features

- **Microsoft Graph API Integration**: Utilizes Microsoft Graph API to fetch user emails and send emails via Microsoft Outlook.

- **OAuth 2.0 Authentication**: Implements secure user authentication and authorization using OAuth 2.0 to obtain access tokens.

- **Email Retrieval**: Fetches user emails from the Microsoft Graph API, showcasing the integration with the Mail API endpoint.

- **Email Sending**: Demonstrates how to send emails using Microsoft Graph API, enabling communication with Microsoft Outlook.

## Getting Started

1. **Prerequisites:**
   - [.NET 7 SDK](https://dotnet.microsoft.com/download/dotnet/7.0)
   - [Microsoft 365 developer account](https://developer.microsoft.com/en-us/microsoft-365/dev-program)

2. **Configuration:**
   - Register a new application in the [Azure Portal](https://portal.azure.com/) to obtain the necessary client ID, client secret, and redirect URI.
   - Update `appsettings.json` with your Azure AD app configuration.

3. **Run the Application:**
   ```bash
   dotnet run
4. **Usage:**
- Log in using your Microsoft 365 credentials.
- Explore the application to retrieve and send emails.

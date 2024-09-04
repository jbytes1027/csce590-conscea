# Conscea
Conscea is a certificate management system for employers. It was assigned as a group project for an Azure class. We were given 3 weeks to implement an MVP according to a design document.

## Notable Contributions
- **Built the backend**
    - Implemented data importing from Blob Storage to Azure SQL via Azure [Functions](https://dev.azure.com/jamesmpretorius/csce590-conscea/_git/import-functions).
    - Implemented email notifications by connecting the API to an Azure Logic App via a Service Bus queue.
    - Wrote the [API](https://dev.azure.com/jamesmpretorius/csce590-conscea/_git/api).
- **Handled DevOps**
    - Configured repositories and Azure services.
    - Reviewed pull requests.
    - Connected and deployed everything.

## Architecture Overview
<p align="center">
  <a href="https://miscfiles.blob.core.windows.net/conscea/conscea_architecture.svg">
    <img src="https://miscfiles.blob.core.windows.net/conscea/conscea_architecture.svg">
  </a>
</p>

## Tech
- Backend
    - ASP\.NET
    - Azure Functions
    - Azure Blob Storage
    - Azure Service Bus
    - Azure Logic Apps
    - Azure SQL Database
- Frontend
    - React

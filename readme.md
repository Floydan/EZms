# EZms
EZms is a lightweight content management system (CMS) that runs on dotnet core, MS SQL (as default) and Azure Blobs for file storage (as default). The database and file storage parts can be overridden with your own implementations in the Middleware.

EZms is split into two parts: 
## EZms.Core
  - The **Core** project contains the neccessary data layers, loaders and repositories to work with the database content.
  - You can read more about the core project here: [EZms.Core](https://github.com/Floydan/EZms.Core/)
## EZms.UI
  - The **UI** project contains the administration user interface (UI). This is where you can create a site structure, edit page content, publish/unpublish pages, handle content versions and file explorer/management.
  - You can read more about the UI project here: [EZms.UI](https://github.com/Floydan/EZms.UI/)
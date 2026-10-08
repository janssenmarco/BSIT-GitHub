## Two-Tier Architecture
A Two-Tier Architecture is an application structure that separates the system into two main tiers: the Web/Application Tier and the Database Tier. The Web/Application Tier handles the application and user requests, while the Database Tier stores persistent data and information needed by the application.

## The Web / Application Tier
The Web/Application Tier is responsible for serving the user interface and handling HTTP requests from users. In this laboratory, the Nextcloud application serves as the web/application tier. It provides the interface that users access through a web browser and communicates with the database when information is needed.

## The Database Tier
The Database Tier is responsible for storing persistent data used by the application. In this laboratory, MariaDB serves as the database tier. It stores information such as user accounts and other database information required by Nextcloud.

## Why Separate Them?
Separating the web server and database into two containers makes the application easier to manage and organize. Each container has a specific responsibility, which allows the web/application tier and database tier to be deployed, maintained, and managed separately.

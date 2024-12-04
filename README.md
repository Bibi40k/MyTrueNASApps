# MyTrueNASApps

The services are designed to run using **Dockge** on **TrueNAS Electric Eel**.

## Prerequisites

1. **TrueNAS Electric Eel**: Ensure you are running this version or newer.
2. **Dockge**: Installed and configured on TrueNAS for managing Docker containers.
3. **Environment Variables**:
   - Configure the following variables in an `.env` file in the same directory:
     ```
     MYSQL_ROOT_PASSWORD=your-secure-root-password
     MYSQL_PASSWORD=your-secure-db-password
     NEXTCLOUD_TRUSTED_DOMAINS=your-trusted-domains
     NEXTCLOUD_ADMIN_USER=your-admin-username
     NEXTCLOUD_ADMIN_PASSWORD=your-admin-password
     ```

## Deployment

1. Clone this repository to your TrueNAS server.
2. Create an `.env` file in the repository directory and populate it with the required variables.
3. Deploy the services using Dockge
4. Verify that the services are running:
    `docker ps`

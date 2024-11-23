
# Role-Based Access Control (RBAC) Dashboard

## Description
This is a web-based dashboard for managing users, roles, and permissions in a Role-Based Access Control (RBAC) system.

## Features
- User management: View, add, edit, delete users and assign roles.
- Role management: Create, update, and delete roles with permissions.
- Mock API for CRUD operations.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd rbac-dashboard
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the mock API server:
   ```bash
   json-server --watch db.json --port 3000
   ```
4. Run the application:
   ```bash
   ng serve
   ```
5. Open your browser at `http://localhost:4200`.

## Tech Stack
- Angular
- Angular Material
- JSON Server (for mock API)

## License
MIT
        
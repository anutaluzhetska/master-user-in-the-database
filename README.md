# Master user in the database

Advanced console user management system on Node.js and PostgreSQL.

## Configuration
1. Run `npm install`.
2. Create a `.env` file:
```env
DB_URL=your_postgresql_url
MASTER_PASSWORD=your_admin_password
```

Use: node room.js `[command]`
Commands:

- `register, login, update, delete — user actions.`
- `list, status, admin-delete — administrative actions.`

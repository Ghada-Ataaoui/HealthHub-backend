# HealthHub Backend

## Development

### Start Xampp

Open the Xampp dashboard, start Apache and MySQL server.

### phpMyAdmin

- Open your browser & then localhost where you'll find the dashboard. 
- Click on phpMyAdmin where you'll find all your databases (after you migrate them).

### Laravel commands

#### Start the development server

```bash
php artisan serve
```

#### Migrate the database with seeders

```bash
php artisan migrate:fresh --seed
```

#### Others Commands

Check the Laravel documentation for creating controllers, models, migration...

_**Note:** Use proper naming conventions as described in the documentation._

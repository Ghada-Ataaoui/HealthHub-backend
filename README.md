# HealthHub Backend

## Development

### Start Xampp

Open the Xampp dashboard, start Apache and MySQL server.

### PhpMyAdmin

- Open your browser & then localhost where you'll find the dashboard. 
- Click on PhpMyAdmin where you'll find all your databases (after you migrate them).

### Laravel Commands

#### Start the Development Server

```bash
php artisan serve
```

#### Migrate the Database with Seeders

```bash
php artisan migrate:fresh --seed
```

#### Others Commands

Check the Laravel documentation for creating controllers, models, migration...

_**Note:** Use proper naming conventions as described in the documentation._

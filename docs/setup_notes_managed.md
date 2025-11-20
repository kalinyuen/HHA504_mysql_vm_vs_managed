# Setup for managed MySQL
## Google Cloud SQL creation
1. Select to create a sandbox MySQL instance.
2. Name instance and set a password.
3. Select a region press create.

## Configuration
1. Add `0.0.0.0/0` to authorized networks.
2. Disable SSL only connection for security.
3. Add a new user with a username and set a password for it.

## Time to setup
The entire process: creating the MySQL instance and database, connecting it to the Python script, and running a test query to verify functionality, took approximately 20 minutes.
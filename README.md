# migration_cities_json
Below are the steps folowed:
1. Crated a custom module using Drush commad : "drush generate module"
2. Created a custom entity using the module : "lando drush generate entity:content"
3. Enabled the module.
4. Enabled the core module "Migrate"
5. Added the json.yml file inside the Migration folder.
6. Run the command in drush "lando drush migrate-import migrate_city_json"

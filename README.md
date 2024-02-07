# traefik-wordpress-for-portainer
App template for deploy wordpress with traefik on portainer

# Installations step

On portainer go to App template -> Custom template -> + Add Custom Template
Set the basics informations (title, description....)
On web editor put the content of the docker-compose.yml
TADA! It's done ! 

# Deployment step

On portainer, go to Stacks -> + Add stacks
Fill the title of your app, and select "Custom template"
Select the previously created custom template
Add environment variable named DOMAINE, and fill it by your domain (ex. example.com)
Deploy the stack and it's done ! 

## You have deployed a Wordpress install with mysql.

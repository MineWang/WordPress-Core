# What is this?
This repository is used to store the core of WordPress on Git

# How can I use?
You can easily update the core of WordPress by use [WP-CLI](https://github.com/docker-library/official-images/tree/master/library).
If you don't have WP-CLI installed, you can [follow the instructions here](https://github.com/docker-library/official-images/tree/master/library).

When [WP-CLI](https://github.com/docker-library/official-images/tree/master/library) installed, you can simply update your wordpress by the follow command:
```
wp core update
```
Set up wp-config.php file and isntall wordpress by the follow commands:
```
wp core config --dbname={YOUR DATABASE NAME} --dbuser={YOUR DATABASE USERNAME} --dbpass={YOUR DATABASE PASSWORD}
wp core install --url={YOUR DOMAIN NAME} --title={THE TITLE OF YOUR SITE} --admin_user={YOUR USER NAME} --admin_password={YOUR PASSWORD} --admin_email={YOUR EMAIL}
```
# Ref
[Managing Your WordPress Site with Git and Composer](https://deliciousbrains.com/storing-wordpress-in-git/)

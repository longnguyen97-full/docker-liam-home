# Notice #
> notice that container name of mysql (in this case) is db.localhost will be use for database host name in wp-config.php and when login adminer
> ok so now, make sure you are in root directory where contains docker-compose.yml file

# Step 1. Start docker compose #
> docker-compose up -d

# Step 2. Import DB using adminer #
> access http://localhost:8080/
> upload database file 

# Step 3. Change siteurl and home in wp_options table #
> access wp_options table
> edit option_value from siteurl column and home column

# Step 4. Check site #
> access http://localhost/

# Step 5. Tracking code using ungit #
> access http://localhost:8448/


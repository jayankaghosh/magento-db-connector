# magento-db-connector
Connect to MySQL DB through env.php configuration

Have you ever felt frustrated when connecting to MySQL of a magento project? I mean there are sooo many steps right?

`cat app/etc/env.php` to print the entire env on the screen. Then manually scavenge the hostname, username, password, and database from the output,
save it onto a temporary file, and then finally build your `mysql -h...` command. Too much work. Amirite?

Well not anymore! Introducting the `magento-db-connector` (patent pending). Using this tool connecting to the 
right MySQL database of a Magento project is as easy as 1, 2, 3...literally!

## Steps to use
1. Place the `db` file on the `<magento_root>/bin` directory
2. Give execute permission to the db file `chmod +x bin/db`
3. Run `bin/db` to connect to MySQL from your CLI without the hassle of typing the hostname, username, password, etc.

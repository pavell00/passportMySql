if error "Client does not support authentication protocol requested by server; consider upgrading MySQL client"
then
Execute the following query in MYSQL Workbench

https://stackoverflow.com/questions/50093144/mysql-8-0-client-does-not-support-authentication-protocol-requested-by-server

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password'
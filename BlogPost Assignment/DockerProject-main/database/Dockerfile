FROM mysql:latest

# Set environment variables
ENV MYSQL_ROOT_PASSWORD=MITsabhani@8294
ENV MYSQL_DATABASE=school

# Expose the MySQL port
EXPOSE 3308

# Define a named volume for MySQL data
VOLUME /var/lib/mysql

# Command to run the MySQL server
CMD ["mysqld"]
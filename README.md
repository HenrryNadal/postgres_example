# Postgres Database Example

Repository to be used for SQL learning sessions

## Initiation Steps

0. Be sure Docker Daemon is running on your local machine.

1. Clone this repository to local by using:
    
    `git clone https://github.com/HenrryNadal/postgres_example.git`
    
2. Navigate to cloned repository.

3. Build the Docker image by using.
    
    `docker build -t postgres-dvdrental .`
    
4. Run the docker image by using.
    
    `docker run -it -p 5432:5432 postgres-dvdrental:latest`
    
5. At this point the database is running in your local machine, and is ready to accept connections.
    
    Connect by using a db client such as DBeaver, using the following details:
    
    - host: localhost
    - user: postgres
    - password: mypassword
    - database: dvdrental

6. You are ready to start using querying the database.

💡Note: Next time you need to start the Database, only execute step 4 and you will be ready to go.
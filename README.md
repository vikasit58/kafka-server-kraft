# kafka-server-kraft
#### To start setting up the project

Step 1: Clone the repo

```bash
https://github.com/vikasit58/kafka-server-kraft.git
```
Step 2: Switch to root directory
```bash
cd kafka-server-kraft
``` 
Step 3:  Copy .env file from .env.example
```bash
 kafka-server-kraft/.env
``` 
Step 5: Update .env file vaiables, this username & password will use in kafka ui dashboard
```bash
    KAFKA_UI_USERNAME=admin
    KAFKA_UI_PASSWORD=change_me_strong_password
    KAFKA_BOOTSTRAP_SERVERS=kafka:9092
```
#### Run application with docker

Step 7: Install docker on your machine (already have then SKIP this step)

#### Start Apache kafka, Enable Kraft and Kafka-UI

 Step 9: Start docker container
  ```bash
    docker-compose up
 ```
#### Access Kafka-UI
Step 10: Access Kafka-UI
```bash
    http://localhost:8080/
```

```bash
....................YOU are DONE.....................
```


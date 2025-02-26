# pub_sub_ms
Two standalone Django projects demonstrating the use of Redis for pub/sub pattern in a microservice architecture

# How to run

You can use the command:

```bash
docker-compose up
```


A default superuser is hydrated in the producer system and then replicated to the consumer system when running the project for the first time. 

The default credentials for the user created are:
```bash
email: admin@example.com
password: password
```


# Use Case
An architectural design pattern for distributed systems created for asynchronous communication between different components or services.

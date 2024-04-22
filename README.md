# Containerize VProfile Project

This project demonstrates how to containerize a multi-service application using Docker and manage it with Vagrant for development purposes.
![Screenshot_88](https://github.com/EzgiTastan/VROFILE_PROJECT_ON_CONTAINERS/assets/139014781/9bade40d-c458-47a3-adc9-f9f1c558419f)


## Introduction

This project aims to provide a development environment for a multi-service application using Docker containers managed by Vagrant. It includes configurations for services such as a database, cache, message queue, web application, and web server.

## Technologies Used

- Docker (to containerize)
- Vagrant (IaC for local)
- MySQL (SQL database)
- Memcached (Database Caching Service)
- RabbitMQ (Broker/queueing  agent)
- Tomcat (application server)
- Nginx (web service)

## How to Use

### Prerequisites

Make sure you have the following installed on your machine:

- Vagrant
- VirtualBox or another supported Vagrant provider

### Installation

1. Clone the repository:

```
git clone https://github.com/EzgiTastan/VROFILE_PROJECT_ON_CONTAINERS.git
```

2. Navigate to the project directory:
```
cd ROFILE_PROJECT_ON_CONTAINERS
```

3. Start the Vagrant virtual machine:
```
vagrant up
```

4. SSH into the virtual machine:
```
vagrant ssh
```

5. Run Docker Compose:
```
docker-compose up -d
```

6. To check the IP address and reach the website through it:
```
ip addr show
```

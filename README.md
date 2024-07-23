# Redis Messaging Queue Example

This repository demonstrates a basic implementation of a messaging queue using Redis, Node.js, and Express. It showcases how to set up a simple producer-consumer architecture where messages are pushed to a Redis queue and processed asynchronously.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Features

- Simple message producer that pushes messages to a Redis queue.
- Basic message consumer that processes messages from the Redis queue.
- Built with Node.js and Express.
- Utilizes Redis for message queuing.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Abdullah-dev0/redis-example-message-queue.git
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up Redis using Docker:**

    If you don’t have Redis installed, you can easily start it using Docker:

    ```bash
    docker run --name my-redis -d -p 6379:6379 redis
    ```

    To access the Redis container, use:

    ```bash
    docker exec -it my-redis /bin/bash
    ```

    Once inside the container, you can interact with Redis using:

    ```bash
    redis-cli
    ```

## Usage

1. **Run the application:**

    ```bash
    tsc -b 
    ```
    ```bash
     node dist
     ```


### How to use Redis Pub/Sub with Node.js
1. Start the Redis server
    ```bash
    docker-compose up -d
    ```
2. Start service the subscribe
    ```bash
    node subscribe <name_topic>
    ```
3. Start service the publish
    ```bash
    node publish <name_topic> <message>
    ```
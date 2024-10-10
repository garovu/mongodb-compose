# MongoDB Compose Files

This repository contains a collection of MongoDB Compose files that can be used to quickly set up MongoDB instances with different configurations.

## Usage

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/garovu/mongodb-compose.git
    ```

2. Navigate to the desired MongoDB Compose file:

    ```bash
    cd mongodb-compose
    ```

3. Start the MongoDB instance:

    ```bash
    docker-compose up -d
    docker exec mongodb-primary /scripts/rs-init.sh
    ```

4. Access the MongoDB instance using your preferred MongoDB client.

## Available Compose Files

- `single-node.yaml`: Sets up a single MongoDB instance.
- `replica-set.yml`: Sets up a MongoDB replica set with three nodes.
- `sharded-cluster.yml`: Sets up a sharded MongoDB cluster with three shards.

Feel free to modify the Compose files according to your specific requirements.

## Contributing

If you have any improvements or additional MongoDB Compose files that you would like to contribute, feel free to submit a pull request.

## License

This repository is licensed under the [MIT License](LICENSE).

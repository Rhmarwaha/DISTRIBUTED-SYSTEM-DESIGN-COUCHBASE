# Distributed System Design using Couchbase

## Overview

This project focuses on the design and implementation of a distributed system using Couchbase, emphasizing containerization, high availability, disaster recovery, cross-cluster replication, data sharding, node naming, and failover mechanisms. The dataset utilized comprises Wikipedia articles obtained from Kaggle, totaling 7GB.

## Features

- **Containerization**: Utilized Docker to create and manage 10 containers of Couchbase DB for efficient deployment and scalability.

- **Highly Available and Disaster Recovery**: Configured two clusters, each consisting of 5 nodes, ensuring high availability and incorporating disaster recovery strategies.

- **Cross Cluster Replication**: Implemented cross-cluster replication to synchronize data across the two clusters, promoting consistency and redundancy.

- **Data Sharding Between Multiple Nodes**: Leveraged Couchbase's sharding capabilities to distribute the Wikipedia dataset efficiently among multiple nodes, optimizing performance.

- **Naming to Different Nodes**: Provided distinct and meaningful names to each node in the Couchbase clusters for clarity and ease of management.

- **Failover Between Nodes**: Implemented failover mechanisms to ensure seamless transitions and continuous availability in case of node failures.

## Tools Used

1. **Couchbase**: Used as the NoSQL database system for its flexibility, scalability, and distributed architecture.

2. **Docker**: Employed Docker for containerization, enabling the isolation of Couchbase instances and simplifying the deployment process.


## Demo

Check out the live demo [here](DEMO.mp4).

## Configuration

- Adjust the number of nodes, cluster settings, and other configurations to meet specific requirements.

## Dataset

The dataset used in this project consists of Wikipedia [here](https://www.kaggle.com/datasets/bwandowando/wikipedia-index-and-plaintext-20230801/code) articles obtained from Kaggle, with a total size of 7GB. Ensure the dataset is properly sourced and configured for optimal sharding .


## License

This project is licensed under the [MIT License](LICENSE) - feel free to use, modify, and distribute the code as per the license terms.

**Happy coding!**
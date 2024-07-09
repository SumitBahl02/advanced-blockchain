# Advanced Blockchain Project

This project is an advanced implementation of a blockchain with network communication, a consensus algorithm, and an API for interaction.

## Features
- Basic blockchain structure with transactions
- Proof of Work algorithm
- Network communication between nodes
- Consensus algorithm to resolve conflicts
- Flask API for interaction

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/advanced-blockchain.git
    cd advanced-blockchain
    ```

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv env
    source env/bin/activate
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Start the Flask server:
    ```bash
    python blockchain.py -p 5000
    ```

2. Interact with the API using tools like Postman or curl. Example requests are provided in the `example_requests.http` file.

## API Endpoints

- `/mine`: Mines a new block.
- `/transactions/new`: Adds a new transaction.
- `/chain`: Returns the full blockchain.
- `/nodes/register`: Registers a new node.
- `/nodes/resolve`: Resolves conflicts between nodes to reach consensus.

## Contributing

Feel free to open issues or submit pull requests for improvements and bug fixes.

## License

This project is licensed under the MIT License.

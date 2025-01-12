# RandomX Proof-of-Work Algorithm in Golang

This repository contains a simplified implementation of the RandomX proof-of-work (PoW) algorithm in Golang. RandomX is designed to be CPU-friendly and resistant to ASIC mining, primarily used in privacy-focused cryptocurrencies like Monero.

## Features

- Scratchpad memory initialization and seeding
- Simulated RandomX program execution
- Simplified RandomX hash calculation

## Usage

### Clone the Repository

```bash
git clone https://github.com/astrica1/RandomX.git
cd RandomX
```

### Run the Example

```bash
go run main.go
```

This will output a hash based on the input and seed provided in the main function.

## Customization

Modify the seed and input values in main.go to test with different data.
Extend the ExecuteProgram method to include more detailed and accurate RandomX instruction execution.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with any improvements or bug fixes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

# 🚀 Nexasecure Auth Blockchain

Welcome to the **Nexasecure Auth Blockchain** project!  
A blockchain-based authentication system that securely manages digital assets like NFTs.

---

## ✨ Features

- 🔐 **Blockchain-based Authentication** – Secure and decentralized authentication mechanism.
- 🎨 **NFT Management** – Create, transfer, and burn NFTs with ease.
- 📄 **Structured Logging** – High-performance logging using [Zap](https://github.com/uber-go/zap).
- ⚙️ **Environment-based Configuration** – Flexible setup via environment variables.
- 📈 **Scalable Architecture** – Built for performance and scalability.

---

## 📦 Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/Umayanga12/Blockchain-API-func.git
cd Blockchain-API-func
go mod tidy
````

---

## ⚡ Quick Start

### 1. Configure Environment Variables

| Variable     | Description                           | Default   |
| ------------ | ------------------------------------- | --------- |
| `LOG_LEVEL`  | Logging level (`info`, `debug`, etc.) | `info`    |
| `LOG_FORMAT` | Output format (`console`, `json`)     | `console` |
| `BASE_DIR`   | Base directory for log files          | `logs`    |

### 2. Run the Application

```bash
go run main.go
```

---

## 📡 Example Usage

### ✅ Create an NFT

```http
POST /create-nft
```

Send a JSON payload with the required metadata to create a new NFT.

### 🔁 Transfer an NFT

```http
POST /transfer-nft
```

Provide the NFT ID and recipient details.

### 🔥 Burn an NFT

```http
POST /burn-nft
```

Specify the NFT ID to permanently remove it from the chain.

---

## 📚 Logging

This project uses [Zap](https://github.com/uber-go/zap) for fast, structured, level-based logging.
Logs are written to both the **console** and rotating log files located in the configured `BASE_DIR`.

---

## 🛠️ Development

### Prerequisites

* ✅ Go 1.24 or later
* ✅ Git

---

## 🤝 Contributing

We welcome contributions from the community!

1. Fork this repository.
2. Create a new branch for your feature or bugfix.
3. Submit a **pull request** with a clear and detailed description.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

This project leverages the following libraries:

* [Zap](https://github.com/uber-go/zap) – for structured logging.
* [Multierr](https://github.com/uber-go/multierr) – for error aggregation.


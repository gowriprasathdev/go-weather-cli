# 🌦️ Weather_CLI

A lightweight and efficient **Weather Monitoring Tool** built with **Go (Golang)**. This CLI tool provides real-time information about the current weather for a specific city using a clean and intuitive interface.

## ✨ Features
*   **Current Weather**: Quickly check the current weather for a specific city.
*   **Simple Command**: Easy-to-use CLI command to fetch weather info.
*   **Built for Speed**: Written in Go for minimal overhead and maximum performance.

## 🛠️ Technical Stack
*   **Language**: Go (Golang)
*   **CLI Framework**: [Cobra](https://github.com/spf13/cobra)
*   **HTTP Client**: [Resty](https://github.com/go-resty/resty)

## 🚀 Installation & Usage

### 1. Prerequisites
*   Go 1.18 or higher installed.

### 2. Setup
Clone the repository and install dependencies:
```bash
git clone https://github.com/[your-username]/Weather_CLI.git
cd Weather_CLI
go mod tidy
```

### 3. Basic Commands
The tool uses the base command `weathercli`. You can explore subcommands using:
```bash
go run main.go --help
```

#### Check Current Weather:
```bash
go run main.go current --city [CITY]
```

### 4. Global Installation (Optional)
To use the `weathercli` command globally from any terminal, you can build the executable and move it to your system's `bin` directory:

```bash
# Build the binary
go build -o weathercli

# Move to a directory in your PATH (e.g., /usr/local/bin or C:\bin)
# On Linux/macOS:
mv weathercli /usr/local/bin/

# On Windows:
# Move 'weathercli.exe' to a folder included in your System PATH
```

Now you can simply run:
```bash
weathercli current --city London
```

## 📂 Project Structure
*   `main.go`: Entry point for the application.
*   `cmd/`: Contains the command logic for `current`.
*   `go.mod`: Project dependencies.

---
*Built with ❤️ using Go.*

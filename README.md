# -Developerfolio
Learn new language
# Rust Learning Journey: CLI Weather Application

## 🎯 Project Overview
Building a command-line weather application that fetches real-time weather data from public APIs, with deployment to cloud platforms.

## 📅 Learning Goals

### Week 1: Rust Fundamentals
- [ ] Ownership and borrowing
- [ ] Pattern matching
- [ ] Error handling with Result/Option
- [ ] Structs and enums
- [ ] Modules and crates

### Week 2: Building the Application
- [ ] Async programming with tokio
- [ ] HTTP requests with reqwest
- [ ] JSON serialization with serde
- [ ] CLI argument parsing
- [ ] Environment variables and configuration

### Week 3: Testing & Debugging
- [ ] Unit tests and integration tests
- [ ] Using debugger (gdb/lldb)
- [ ] Logging with env_logger
- [ ] Benchmarking
- [ ] Common Rust pitfalls

### Week 4: Deployment
- [ ] Building for production
- [ ] Docker containerization
- [ ] Deploy to AWS/GCP/Azure
- [ ] CI/CD with GitHub Actions
- [ ] Monitoring and logging

## 🛠️ Tech Stack
- **Language**: Rust (edition 2021)
- **HTTP Client**: reqwest
- **Async Runtime**: tokio
- **CLI Parser**: clap
- **JSON**: serde
- **Error Handling**: anyhow
- **Testing**: built-in test framework
- **Deployment**: Docker + AWS ECS/GCP Cloud Run

## 📁 Project Structure

weather-cli/
├── src/
│ ├── main.rs # Entry point
│ ├── cli.rs # CLI argument parsing
│ ├── weather.rs # Weather API logic
│ ├── config.rs # Configuration management
│ └── error.rs # Custom error types
├── tests/
│ ├── integration_tests.rs
│ └── test_data/
├── docker/
│ └── Dockerfile
├── .github/
│ └── workflows/
│ └── ci.yml # GitHub Actions
├── Cargo.toml
├── Cargo.lock
└── README.md


## 📝 Daily Log

### Day 1: Setting up
- Installed Rust via rustup
- Created new project with `cargo new weather-cli`
- Added dependencies to Cargo.toml
- Initial git repository

### Day 2: Basic CLI Structure
```rust
// Learned about clap for argument parsing
// Implemented basic command structure


## 📝 Daily Log

### Day 1: Setting up
- Installed Rust via rustup
- Created new project with `cargo new weather-cli`
- Added dependencies to Cargo.toml
- Initial git repository

### Day 2: Basic CLI Structure
```rust
// Learned about clap for argument parsing
// Implemented basic command structure





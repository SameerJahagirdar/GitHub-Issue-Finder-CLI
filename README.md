# GitHub Issue Finder CLI (Rust)

A command-line tool to search for "good-first-issue" labeled GitHub issues across repositories, built using Rust. This tool fetches open issues labeled with `good-first-issue` using the GitHub Search Issues API, enabling developers to find beginner-friendly tasks easily.

## Features
- Fetches open GitHub issues labeled with `good-first-issue`.
- Asynchronous HTTP requests using the **Tokio** runtime for efficiency.
- Handles JSON response parsing using **serde**.
- Provides simple CLI output of issue titles and links.

## Prerequisites
- **Rust** installed on your machine. If not, follow the [installation guide](https://www.rust-lang.org/tools/install).
- **GitHub Personal Access Token** for authenticated API requests (to avoid rate limiting). You can generate one from your [GitHub settings](https://github.com/settings/tokens).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/github-issue-finder.git
   cd github-issue-finder
2. Install Dependencies
   ``` bash
   cargo build
   cargo run
3. Output

![image](https://github.com/user-attachments/assets/b95f6592-8d94-472d-a2d5-666ffe25551f)

## Project Structure
- `src/main.rs`: The main file that contains the Rust code for fetching GitHub issues and handling CLI interactions.
- `Cargo.toml`: Rust package configuration and dependencies (`reqwest`, `serde`, `tokio`).

## Key Libraries Used
- [reqwest](https://crates.io/crates/reqwest): To make HTTP requests.
- [serde](https://crates.io/crates/serde): For JSON deserialization.
- [tokio](https://crates.io/crates/tokio): For asynchronous runtime.

## Contributing
Contributions are welcome! Feel free to fork this project and submit a pull request with improvements or fixes.


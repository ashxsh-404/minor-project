# minor-project
# Rust Log Analyzer

A Rust-based tool designed to process, filter, and analyze system or application logs. This program allows for hash-based log categorization, custom filtering, and summarized reporting of log data, leveraging efficient Rust features and multithreading for performance.

## Features

-  Log Parsing: Reads logs from a database or file.
-  Filtering: Supports custom filters based on keywords, dates, or log levels.
-  Hashing: Applies hashing algorithms to anonymize or group similar logs.
-  Reporting: Generates summarized reports of filtered logs.
-  **Performance: Built with concurrency in mind for fast processing.

## File Overview

- main.rs – Entry point; initializes the application and coordinates processing.
- db.rs – Handles reading log data from the source (file or database).
- filter.rs – Provides filtering logic for log entries.
- hasher.rs – Implements hashing functions for log content.
- report.rs – Generates reports from filtered and processed log data.

## Getting Started

### Prerequisites

- Rust (edition 2021 or newer)
- Cargo

### Build

bash
cargo build --release

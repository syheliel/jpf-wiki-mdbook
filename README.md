# JPF Documentation

This repository contains the documentation for Java PathFinder (JPF), a software verification tool. The documentation is built using [mdBook](https://github.com/rust-lang/mdBook), a utility to create online books from Markdown files.

## Prerequisites

1. Install Rust (if you haven't already):
   ```bash
   curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
   ```

2. Install mdBook:
   ```bash
   cargo install mdbook
   cargo install mdbook-lintcheck
   ```

## Building the Documentation

1. Clone this repository:
   ```bash
   git clone https://github.com/javapathfinder/jpf-wiki-mdbook.git
   cd jpf-wiki-mdbook
   ```

2. Build the documentation:
   ```bash
   mdbook build
   ```
   This will generate the documentation in the `book` directory.

3. Serve the documentation locally:
   ```bash
   mdbook serve
   ```
   This will start a local server, typically at `http://localhost:3000`. You can view the documentation in your web browser.

## Documentation Structure

The documentation is organized in the following sections:

- **Getting Started**: Introduction to JPF and its key features
- **Installation**: How to obtain and install JPF
- **User Guide**: How to use JPF effectively
- **Developer Guide**: Information for developers working with JPF
- **Core Project**: Details about the JPF core project
- **Events and Activities**: Information about GSoC and workshops
- **Workshops and Events**: Details about JPF workshops and events

## Contributing

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes
4. Submit a pull request

## License

This documentation is part of the Java PathFinder project. See the [JPF license](https://github.com/javapathfinder/jpf-core/blob/master/LICENSE-2.0.txt) for details. 
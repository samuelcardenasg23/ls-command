# Simple Node.js File Explorer

This Node.js script tries to replicate the **ls** terminal command. Provides a basic file listing of a specified directory. It uses the `fs/promises` module for file system operations and `picocolors` for colorful console output.

## Usage

Make sure you have Node.js installed. You can run the script by providing the target directory as a command-line argument:

```bash
node index.js [directory]
```

## Installation
1. Clone the repository:

```bash
git clone https://github.com/samuelcardenasg23/ls-command
```

2. Navigate to the project directory:
```bash
cd your-repository
```
3. Install dependencies:
```bash
npm install
```
4. Execute the script by running:
```bash
node script.js [directory]
```

## Dependencies

- node:fs/promises - Promisified version of the Node.js fs module.
- node:path - Provides utilities for working with file and directory paths.
- picocolors - A lightweight and efficient library for colored console output.
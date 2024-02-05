# Simple Node.js File Explorer

This Node.js script tries to replicate the **ls** terminal command. Provides a basic file listing of a specified directory. It uses the `fs/promises` module for file system operations and `picocolors` for colorful console output.

## Usage

Make sure you have Node.js installed. You can run the script by providing the target directory as a command-line argument. (Clone the project in a directory that has multiple files or folders):

```bash
node index.js [directory]
```

## Overview
![overview](https://github.com/samuelcardenasg23/ls-command/assets/119268082/86f74489-83d2-4ebc-be1c-21a6c4bf4c27)

## Installation
1. Clone the repository:

```bash
git clone https://github.com/samuelcardenasg23/ls-command
```
2. Install dependencies:
```bash
npm install
```
3. Execute the script by running:
```bash
node index.js [directory]
```

## Dependencies

- node:fs/promises - Promisified version of the Node.js fs module.
- node:path - Provides utilities for working with file and directory paths.
- picocolors - A lightweight and efficient library for colored console output.
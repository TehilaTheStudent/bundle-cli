# CLI Tool for Code Bundling [practicode-1](https://learn.malkabruk.co.il/practicode/projects/pract-1/)

## Project Overview
This project is a Command-Line Interface (CLI) tool developed in C# designed to streamline the process of bundling multiple code files into a single file. The tool enhances efficiency by allowing users to execute a single command to aggregate their code, simplifying file management and submission processes.

## Features
- **Bundle Command**: Combines multiple code files into one output file with customizable options.
- **Create Response File Command**: Generates a response file to facilitate easy execution of bundling commands.

## Commands
### 1. `bundle`
This command packages code files into a single output file. It supports the following options:
- **--language** (required): Specifies the programming languages to include. Use `all` to include all files.
- **--output**: Defines the name of the output bundle file, which can be a relative or absolute path.
- **--note**: Option to include a comment in the bundle indicating the source of the code.
- **--sort**: Determines the order of files in the bundle (default is by filename).
- **--remove-empty-lines**: Removes empty lines from the code before bundling.
- **--author**: Specifies an author name to include in the bundle as a comment.

### 2. `create-rsp`
This command creates a response file that contains the bundling command with user-defined options, simplifying future executions.

## Installation
1. Create a Console Application project in Visual Studio.
2. Install the `System.CommandLine` library via NuGet Package Manager.
3. Build the project to generate the executable.

## Usage
After building the project, you can run the CLI tool from the command line.

## Conclusion
Thank you for exploring the CLI Tool for Code Bundling! We hope this tool enhances your coding experience by simplifying the process of managing and submitting code files. Your feedback and contributions are always welcome as we strive to improve and expand the functionality of this project. Happy coding!

  

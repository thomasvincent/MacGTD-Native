# MacGTD-Native

A collection of macOS Automator workflows for implementing Getting Things Done (GTD) with Apple's native applications.

## Overview

This project provides a set of macOS Automator workflows that help implement the GTD methodology using Apple's built-in applications:

- Apple Reminders for tasks and next actions
- Apple Notes for project notes and reference materials
- Apple Calendar for scheduled events and deadlines
- Apple Mail for email processing

## Included Workflows

### GTD-QuickCapture

Quickly capture thoughts, ideas, and tasks into your Apple Reminders inbox without disrupting your current workflow.

## Installation

1. Clone this repository
2. Double-click on the workflow files to install them in Automator
3. Optional: Assign keyboard shortcuts to workflows in System Preferences > Keyboard > Shortcuts > Services

## Usage

Each workflow is documented with usage instructions within the Automator interface.

## Testing

This project includes comprehensive test coverage:

- **Unit Tests**: Validate the structure and syntax of the workflow files
- **Integration Tests**: Simulate running the workflows with various inputs
- **CI/CD**: GitHub Actions workflow automatically runs tests on push/PR

To run tests locally:

```bash
cd tests
./test_workflow.sh     # Run unit tests
./integration_test.sh  # Run integration tests
```

See the [tests/README.md](tests/README.md) file for more details on testing.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT
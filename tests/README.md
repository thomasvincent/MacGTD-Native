# Test Suite for MacGTD-Native

This directory contains tests for the MacGTD-Native Automator workflows.

## Available Tests

### `test_workflow.sh`

This script tests the GTD-QuickCapture workflow functionality:

1. **File Existence Test**: Checks if workflow files exist
2. **XML Syntax Test**: Validates the workflow XML syntax
3. **AppleScript Syntax Test**: Validates the AppleScript syntax
4. **Reminders Integration Test**: Verifies integration with macOS Reminders
5. **Notification Test**: Verifies notification functionality

## Running Tests

From the tests directory, run:

```bash
./test_workflow.sh
```

### Prerequisites

- `xmllint` for XML validation (usually pre-installed on macOS)
- macOS 10.14 or higher

## Adding New Tests

When adding new workflows, create corresponding test scripts that follow the same pattern.

## Manual Testing

For full workflow functionality, manual testing is recommended:

1. Double-click the workflow file to install it in Automator
2. Run the service from the Services menu
3. Verify the task is correctly added to the Reminders app
4. Verify that notifications appear as expected

## Test Coverage

Current test coverage focuses on:

- File integrity
- Syntax validation
- Core functionality presence

Future test improvements may include:
- UI automation
- Integration with CI systems
- Mocking of macOS services
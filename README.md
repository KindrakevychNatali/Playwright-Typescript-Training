//COMMANDS
- npx playwright test --ui

**To Run specific tests:
To run a single test file, pass in the test file name that you want to run.

-npx playwright test landing-page.spec.ts

To run a set of test files from different directories, pass in the directory names that you want to run the tests in.

-npx playwright test tests/todo-page/ tests/landing-page/

To run files that have landing or login in the file name, simply pass in these keywords to the CLI.

-npx playwright test landing login

To run a test with a specific title, use the -g flag followed by the title of the test.

-npx playwright test -g "add a todo item"

Run last failed tests
To run only the tests that failed in the last test run, first run your tests and then run them again with the --last-failed flag.

-npx playwright test --last-failed

**Debug tests with the Playwright Inspector
To debug all tests, run the Playwright test command followed by the --debug flag.

-npx playwright test --debug

**Setting up CI


# devchallenge.it---qa---1

# REQUIRED TOOLS

These external libraries are required to run api test:
1. **NodeJS** - https://nodejs.org/en/download/
2. **Newman** - https://github.com/postmanlabs/newman#getting-started
Using node, newman can be installed by typing the following command in the terminal: 
    `npm install newman --global;`

# RUNNING TESTS

**To run the tests, please follow the next steps:**

## Windows:
1. Press Windows button
2. Type "PowerShell" and press **Enter**
3. Navigate to project folder using cd command. E.g.:
	`cd '.\Downloads\devchallenge.it---qa---1\'`

## Mac OS:
1. Open Spotlight (`ctrl + space`).
2. Type "terminal" and press Enter.
3. Navigate to project folder using "cd" command. E.g.:
	`cd ~/Downloads/devchallenge.it---qa---1/`

## Linux:
1. Open terminal (`ctrl + alt + T`)
2. Navigate to project folder using cd command. E.g.:
	`cd ~/Downloads/devchallenge.it---qa---1/`

## ALL: Once you navigated to project folder, type the following command:
4. `newman run devchallenge.tests.json -e devchallenge.env.json --export-environment devchallenge.env.json`


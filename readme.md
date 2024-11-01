# Teneo Bot

## Description
Teneo bot is a simple tool designed to automate the node interaction.

## Features
- **Automated Account Creation**: Register multiple accounts using a list of email addresses.

## Prerequisites
- [Node.js](https://nodejs.org/) (version 12 or higher)

## Installation

1. Clone the repository to your local machine:
   ```bash
	git clone https://github.com/recitativonika/teneo-bot.git
   ```
2. Navigate to the project directory:
	```bash
	cd teneo-bot
	```
3. Install the necessary dependencies:
	```bash
	npm install
	```

## Usage

1. Sset the `account.js` before running the script.
2. Configuration
Modify the `account.js` file to set your account parameters:
	```
	module.exports = {
	email: 'email@example.com', // Replace with your email
	password: 'password'          // Replace with your password
	};

	```
3. Run the account creator script:
	```bash
	node index.js
	```

License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

Note
This script only for testing purpose, using this script might violates ToS and may get your account permanently banned.

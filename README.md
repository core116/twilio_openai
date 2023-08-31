# Twilio Voice and SMS Integration with OpenAI

📞📧 A project that integrates Twilio's voice and SMS functionality with OpenAI's powerful language model.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Twilio Voice and SMS Integration with OpenAI project provides a seamless integration between Twilio's voice and SMS services and OpenAI's language model. With this integration, you can leverage the power of OpenAI to generate automated voice responses or send AI-generated SMS messages.

## Installation

To run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/core116/twilio_openai.git`
2. Install the required dependencies by running `npm install` or `yarn install`.

## Usage

To start using the Twilio Voice and SMS integration, make sure you have the following prerequisites:

- Twilio account credentials
- OpenAI API key

1. Set up your Twilio account and obtain your account SID, authentication token, and phone numbers (if applicable).
2. Get an OpenAI API key by creating an account on OpenAI's website.
3. Configure the integration by entering your Twilio and OpenAI credentials (see [Configuration](#configuration) section below).
4. Run the project using `npm start` or `yarn start`.

## Configuration

To configure the integration, open the `config.js` file and enter the following information:

```javascript
module.exports = {
  twilio: {
    accountSid: 'YOUR_TWILIO_ACCOUNT_SID',
    authToken: 'YOUR_TWILIO_AUTH_TOKEN',
    phoneNumber: 'YOUR_TWILIO_PHONE_NUMBER',
  },
  openai: {
    apiKey: 'YOUR_OPENAI_API_KEY',
  },
};

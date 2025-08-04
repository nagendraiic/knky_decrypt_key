# Decrypt Data Web Tool

A simple, client-side HTML page that allows you to decrypt AES-encrypted data using a password key.

## Features

- Enter and save a decryption key (stored in session storage).
- Paste encrypted data (JSON or raw encrypted string).
- Decrypt nested encryption (fields named `r`).
- Display decrypted output as formatted JSON or plain text.
- Copy decrypted output to clipboard.

## Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari).
- No server setup or build tools required.

## Getting Started

1. Download or clone this repository.
2. Open the `index.html` file in your web browser.

## Usage

1. Enter your AES decrypt key in the **Enter Decrypt Key** section and click **Submit**.
2. Paste your encrypted text into the **Enter encrypted data** textarea.
3. Click **Get api response** to decrypt the data.
4. The decrypted result will appear in the **Decrypted Output** section.
5. Use the **Copy** button to copy the decrypted output to your clipboard.

## Notes

- The decryption key is stored in session storage and will be cleared when the browser tab is closed.
- Supports both JSON-wrapped encrypted data (with an `r` field) and raw encrypted strings.

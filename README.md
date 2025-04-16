# Phishing URL Detector

This is a simple web-based Phishing URL Detector built using **HTML**, **CSS**, and **JavaScript**. It helps users identify potentially malicious URLs by checking for common phishing indicators.

## Features

- Input any URL and check its safety.
- Detects:
  - Use of IP addresses instead of domain names
  - Suspicious keywords (e.g., `login`, `verify`, `paypal`, etc.)
  - Multiple dots in domain (e.g., `abc.def.ghi.example.com`)
  - Use of `@` symbol in the URL

## Demo

![Screenshot](screenshot.png) <!-- Add a screenshot image in your repo and name it screenshot.png -->

## How It Works

The app uses simple client-side heuristics to check if a URL might be a phishing attempt. It does **not** rely on any server or API, and is intended for demonstration or educational purposes.

## Usage

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Enter a URL to test and click **Check URL**.

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

## Project Structure



<div align="center">

  # Unit Converter

  <img src="https://play-lh.googleusercontent.com/R46vqH8qKkBTxEcTZJ3WzAfVaeG7xXHdKBCi6jnhoFadggWy8NoA3GfxnrSkpUYCxjE" height="100" alt="avatar" />

  [Overview](#🎯-overview) •
  [Features](#✨-features) •
  [Getting Started](#🚀-getting-started) •
  [Usage](#📘-usage) •
  [API](#📚-api)

</div>

---

## 🎯 Overview

The Unit Converter project is a web application that enables users to convert between different units of length, weight, and temperature. It provides a user-friendly interface where users can input values, select units, and get instant conversion results. The primary goal is to facilitate easy and accurate unit conversions.

## ✨ Features

- **Length Conversion**: Convert between various units like meters, centimeters, inches, and more.
- **Weight Conversion**: Convert between grams, kilograms, pounds, etc.
- **Temperature Conversion**: Convert between Celsius, Fahrenheit, and Kelvin.
- **Responsive Design**: Ensures compatibility across different devices.
- **Interactive Interface**: Simple and intuitive user interface for easy conversions.

## 🚀 Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

Ensure you have the following installed:

- A modern web browser

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/hamza-140/unit-converter.git
    cd unit-converter
    ```

2. Open the `index.html` file in your browser to start the application.

## 📘 Usage

Here's how you can use the Unit Converter:

### Length Conversion

```html
Enter the length to convert: <input type="number" id="inputValue" />
Select the unit to convert from: <select id="unitFrom">...</select>
Select the unit to convert to: <select id="unitTo">...</select>
```

### Weight Conversion

```html
Enter the weight to convert: <input type="number" id="inputValue" />
Select the unit to convert from: <select id="unitFrom">...</select>
Select the unit to convert to: <select id="unitTo">...</select>
```

### Temperature Conversion

```html
Enter the temperature to convert: <input type="number" id="inputValue" />
Select the unit to convert from: <select id="unitFrom">...</select>
Select the unit to convert to: <select id="unitTo">...</select>
```

## 📚 API

This project does not include a backend API; it is a frontend-only application. The main logic for conversions is embedded within the JavaScript code in each HTML file. Below are some key functions used for conversions:

### `convertLength()`

Converts a value between different units of length.

- **Parameters**:
  - `inputValue` (Number): The value to convert.
  - `unitFrom` (String): The unit to convert from.
  - `unitTo` (String): The unit to convert to.

- **Returns**: A numerical value representing the converted length.

### `convertWeight()`

Converts a value between different units of weight.

- **Parameters**:
  - `inputValue` (Number): The value to convert.
  - `unitFrom` (String): The unit to convert from.
  - `unitTo` (String): The unit to convert to.

- **Returns**: A numerical value representing the converted weight.

### `convertTemperature()`

Converts a value between different temperature scales.

- **Parameters**:
  - `inputValue` (Number): The temperature value to convert.
  - `unitFrom` (String): The unit to convert from (Celsius, Fahrenheit, Kelvin).
  - `unitTo` (String): The unit to convert to (Celsius, Fahrenheit, Kelvin).

- **Returns**: A numerical value representing the converted temperature.

---
## CC
https://roadmap.sh/projects/unit-converter

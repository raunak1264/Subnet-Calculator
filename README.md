# Subnet Calculator

![Subnet Calculator](https://your-image-url.com)

## Overview

This is a web-based Subnet Calculator that allows users to calculate and display the list of IP addresses within a given subnet. The calculator takes a subnet ID in the format of x.x.x.x/y, where x is an octet of an IP address, and y is the number of bits in the subnet mask.

## Features

- **User-Friendly Interface**: The calculator provides a simple and intuitive interface for users to input the subnet ID and perform calculations.
  
- **Real-Time Calculation**: Users can instantly calculate the network ID, broadcast ID, number of hosts, and the list of IP addresses within the subnet by clicking the "Calculate" button.

- **Error Handling**: The script includes error handling to validate the input subnet ID and provides informative error messages for invalid inputs.

## Usage

1. Enter a subnet ID in the format of x.x.x.x/y in the input box.
2. Click the "Calculate" button to obtain the calculated information.
3. View the list of IP addresses included in the subnet in the output box.

## Installation

No installation is required. Simply open the HTML file in a web browser.

## How it Works

The calculator converts the input subnet ID from decimal to binary, performs bitwise AND and OR operations to calculate the network ID and broadcast ID, and then converts these values back to decimal. It also calculates the number of hosts in the subnet and generates the list of IP addresses.

## Example

- Input: 192.168.1.0/24
- Output:
  ```
  192.168.1.1
  192.168.1.2
  ...
  192.168.1.254
  ```

## Contributing

Feel free to contribute to the development of this Subnet Calculator by opening issues, providing feedback, or submitting pull requests.

## License

This Subnet Calculator is licensed under the [MIT License](LICENSE).

---

**Note:** Replace the placeholder image URL with the actual URL of an image relevant to your Subnet Calculator.

# Aadhaar and Mobile Number Validation System

This project is a Python-based system that validates email addresses, mobile numbers, and Aadhaar numbers. It also verifies if the Aadhaar number matches the given mobile number and provides information about the location and carrier of the mobile number.

## Features

- Validates email addresses
- Validates mobile numbers
- Validates Aadhaar numbers
- Verifies if Aadhaar number matches the mobile number
- Provides location and carrier information of the mobile number
- Text-to-speech feedback for user interactions

## Requirements

- Python 3.x
- `phonenumbers` library
- `pyttsx3` library

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/raginee_darade/aadhaar-mobile-validation.git
    cd aadhaar-mobile-validation
    ```

2. Install the required packages:
    ```bash
    pip install phonenumbers pyttsx3
    ```

## Usage

1. Run the main script:
    ```bash
    python main.py
    ```

2. Follow the on-screen instructions to enter your name, email, mobile number, and Aadhaar number.

## Code Overview

### main.py

This is the main script that handles user input and validation:

- **Email Validation**: Checks if the email format is correct.
- **Mobile Number Validation**: Validates the mobile number based on the country code.
- **Aadhaar Number Validation**: Validates the Aadhaar number format.
- **Aadhaar and Mobile Number Matching**: Ensures the Aadhaar number matches the provided mobile number.
- **Location and Carrier Information**: Retrieves and displays the location and carrier of the mobile number.

## Example

Welcome
Enter your name: John Doe
John Doe
Enter the full name: Johnathan Doe
Johnathan Doe
Enter your email: john.doe@example.com
This is a correct email
Enter your country code: +91
Enter your mobile number: 9123456789
Enter your Aadhaar number: 250002352839
Aadhaar number matches from the mobile number:
Location: India
Carrier: Vodafone
You are a citizen of India


## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

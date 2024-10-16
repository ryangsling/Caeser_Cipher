# Caesar Cipher Encode/Decode Program

This Python program provides a simple implementation of the Caesar cipher, an ancient encryption technique. It allows users to encode and decode messages by shifting letters by a specified number of positions in the alphabet.

## Features

- **Encoding**: Shift the characters in your message to create an encrypted version.
- **Decoding**: Reverse the shift to retrieve the original message.
- **Flexible Shift**: Supports custom shift values.
- **Case Sensitivity**: Handles both uppercase and lowercase letters.
- **Non-letter characters**: Non-letter characters (such as spaces, punctuation) are unaffected.

## How It Works

The Caesar cipher works by shifting each letter in the plaintext by a specified number of positions in the alphabet. For example, with a shift of 3:
- **Plaintext**: `hello`
- **Ciphertext**: `khoor`

The same shift can be used to decode the message.

## Usage

### Requirements
- Python 3.x

### Installation
1. Clone this repository or download the Python file:
   ```bash
   git clone https://github.com/ryangsling/Caeser_Cipher.git
   ```
2. Navigate to the directory:
   ```bash
   cd Caesar-Cipher
   ```

### Running the Program
Run the program in the terminal:
```bash
python Caesar_Cipher.py
```

### Example
```python
# Example of encoding a message
Type your message: hello
Type the shift number: 3
The encoded text: khoor

# Example of decoding a message
Type your message: khoor
Type the shift number: 3
The decoded text: hello
```

## Customization

- You can adjust the shift value to any integer. Positive values shift to the right (forward in the alphabet), while negative values shift to the left (backward in the alphabet).
- The program will correctly wrap around the alphabet when the shift moves past 'Z' or 'z'.

## Contributions

Feel free to submit issues or contribute to the project. Fork the repository and make a pull request with improvements or new features.

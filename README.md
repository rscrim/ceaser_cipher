# Caesar Cipher

This is a simple command-line application that provides two functions, caesarEncrypt() and caesarDecrypt(), that take a string and a shift value as input, and return the corresponding ciphertext or plaintext. The application also provides a menu that allows the user to choose between encrypting or decrypting a string.

## Requirements

To use this application, you will need to have the Go programming language installed on your computer. You can download Go from the official website: <https://golang.org/dl/>.

## Installation

To install the application, you can clone this repository or download the source code as a ZIP file. Once you have the source code, you can navigate to the project directory and run the following command to build the application:

## Usage

To use the application, navigate to the directory where the executable file is located and run the following command:

```bash
./caesar-cipher
```

This will start the application and display the main menu.

## Modes

The application has two modes: encryption and decryption. In encryption mode, the user can enter a string to be encrypted and a shift value. In decryption mode, the user can enter a string to be decrypted and the shift value that was used to encrypt the string.

## Examples of Use

To encrypt the string "HELLO" with a shift value of 3, the user can select encryption mode from the main menu, enter "HELLO" when prompted for a string, and enter 3 when prompted for a shift value. The application will then display the encrypted string, which should be "KHOOR".

To decrypt the string "KHOOR" with a shift value of 3, the user can select decryption mode from the main menu, enter "KHOOR" when prompted for a string, and enter 3 when prompted for the shift value. The application will then display the decrypted string, which should be "HELLO".

## License

This project is licensed under the MIT License - see the LICENSE file for details.

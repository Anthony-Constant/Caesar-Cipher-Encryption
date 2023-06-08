# Caesar Cipher Encryption

This is a simple implementation of the Caesar cipher encryption technique in Python. The Caesar cipher is one of the simplest and most widely known encryption techniques. It works by replacing each letter in the plaintext message by a letter a fixed number of positions down the alphabet. This fixed number is called the key. The method is named after Julius Caesar, who used it in his private correspondence.

## Encryption Formula

The encryption formula for the Caesar cipher is as follows:
- En(x) = (x + n) mod 26


where `x` is the plaintext message and `n` is the key. The value 26 is used because there are 26 letters in the alphabet. The mod operation ensures that the result is always within the range of the alphabet.

## Decryption Formula

The decryption formula for the Caesar cipher is as follows:
- Dn(x) = (x - n) mod 26


## How it Works

The Caesar cipher is a substitution cipher in which each letter in the alphabet is replaced by a letter some fixed number of positions down the alphabet. For example, with a right shift of 2, C would replace A, D would become B, and so on. The following table shows the encryption and decryption alphabets for a right shift of 2:

| Plain | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X | Y | Z |
|-------|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Cipher| C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X | Y | Z | A | B |

## Usage

To use the Caesar cipher encryption in Python, simply run the `Caesar_Cipher.py` file and follow the prompts. Enter the plaintext message and the key (an integer between 1 and 25) when prompted. The script will then encrypt the message and display the ciphertext.

## References

- [Caesar cipher - Wikipedia](https://en.wikipedia.org/wiki/Caesar_cipher)

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

This script was developed by [Anthony Constant](https://anthonyconstant.co.uk/).



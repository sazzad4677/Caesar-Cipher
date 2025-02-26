# Caesar Cipher Program

This is a simple implementation of the Caesar cipher, which is a type of substitution cipher. It shifts the letters of the alphabet by a fixed number (shift) to either encode or decode a given message.

## Features:
- **Encoding:** You can encrypt a message by shifting its characters forward.
- **Decoding:** You can decrypt a message by shifting its characters backward.
- **Custom Shift:** The user can define the shift number.
- **Continued Operation:** The program will keep running and allow you to encode or decode more messages until you choose to quit.

## How It Works:
1. The program asks whether you'd like to encode or decode a message.
2. It then prompts you to enter the text and the shift number.
3. Based on the choice of encoding or decoding, it shifts the characters accordingly.
4. It continues until you decide to quit.

## How to Run:
1. Copy the code into a Python (.py) file.
2. Run the Python file.
3. When prompted:
    - Type **'encode'** to encrypt a message or **'decode'** to decrypt.
    - Enter the text you want to encrypt or decrypt.
    - Enter the number to shift the alphabet.
    - Type **'yes'** to continue or **'no'** to exit.

### Example Usage:
1. **Encoding:**
    ```
    Type 'encode' to encrypt, type 'decode' to decrypt:
    encode
    Type your message:
    hello
    Type the shift number:
    3
    The encoded text is: khoor
    ```
2. **Decoding:**
    ```
    Type 'encode' to encrypt, type 'decode' to decrypt:
    decode
    Type your message:
    khoor
    Type the shift number:
    3
    The decoded text is: hello
    ```

## Notes:
- This implementation works only with lowercase alphabetical characters.
- It will ignore non-alphabetical characters (such as spaces, punctuation, and numbers).
- The program will keep running in a loop until you choose to quit by typing **'no'** when asked if you want to continue.
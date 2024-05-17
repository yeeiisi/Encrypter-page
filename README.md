# Encrypter

This project is a simple web application for encrypting and decrypting text using symmetric key cryptography.

## Project Structure

- `app.py`: This is the main Flask application file. It contains the routes for the web application, including the routes for encryption, decryption, and fetching the encryption key.

- `key.key`: This file stores the encryption key. If the file does not exist when the application starts, a new key is generated and saved in this file.

- `templates/index.html`: This is the main HTML file for the web application. It contains the user interface for entering text to be encrypted or decrypted, buttons for performing encryption and decryption, and a button for displaying the encryption key.

## How to Use

1. Enter the text you want to encrypt in the text area.
2. Click the "Encrypt" button. The encrypted text will be displayed in the message box.
3. To decrypt the text, enter the encrypted text in the text area and the encryption key in the key input field, then click the "Decrypt" button. The decrypted text will be displayed in the message box.
4. To view the encryption key, click the "Show Key" button. The key will be displayed in the key box.

**Note:** The encryption key changes every time the page is refreshed. If you refresh the page, you will not be able to decrypt text that was encrypted with the previous key. Make sure to save the key if you need to decrypt the text later.

## Running the Project

To run the project, execute the following command in the terminal:

```sh
python app.py

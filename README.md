# SecureX: File Encryption and Decryption Tool

This Python script provides a simple file encryption and decryption tool using the XOR operation. The program uses a fixed key for both encryption and decryption processes.

## Features
- Encryption: XOR operation is applied to each byte of the file using a fixed key.  
- Decryption: Similar to encryption, the XOR operation is applied to decrypt the file.
- Input Validation: Handles file not found and other exceptions gracefully.

## Usage Instructions
1. Run the script.
2. Choose between encryption and decryption.
3. For encryption, provide the filename to be encrypted.
4. For decryption, provide the encrypted filename and specify the filename for the decrypted output.
5. The encrypted and decrypted files are saved as "cipher_filename" and "decrypted_filename," respectively.

## Requirements
- Python 3.x
- tqdm library: Install using `pip install tqdm`
- termcolor library: Install using `pip install termcolor`

## Execution
Run the script using the following command:
```bash
python script_name.py
```

# A-simple-image-encryption-tool-using-pixel-manipulation-allowing-users-to-encrypt-and-decrypt-images
A simple image encryption tool using pixel manipulation. You can perform operations like swapping pixel values or applying a basic mathematical operation to each pixel. Allow users to encrypt and decrypt images. It uses a simple image encryption algorithm and provides a graphical user interface (GUI) for a more user-friendly experience.

## Features

* **Select an Image**: Choose an image you want to encrypt or decrypt.
* **Seed Key**: Enter a numerical seed key for encryption or decryption.
* **Encrypt Image**: Encrypt the image using the specified seed key.
* **Decrypt Image**: Decrypt an encrypted image back to its original state using the same seed key.
* **Save the Output**: Save the encrypted or decrypted image to a chosen output location.

## Requirements

* Python 3.x
* `Tkinter` (for the GUI interface)
* `Pillow` (for handling images)

To install required dependencies, use the following command:

```bash
pip install Pillow
```

## How to Run

1. Download or clone the project to your local machine.
2. Ensure that Python 3.x is installed on your system.
3. Navigate to the directory where `image_encryption.py` is located.
4. Run the program with:

```bash
python image_encryption.py
```

## How to Use

1. **Select an Image to Encrypt/Decrypt**: Click the "Browse" button to select the image you want to work with.
2. **Enter the Seed Key**: Provide a numerical seed key (e.g., 5) to either encrypt or decrypt the image.
3. **Choose Output Path**: Click "Save As" to choose where to save the encrypted/decrypted image.
4. **Encrypt or Decrypt**:

   * If you want to encrypt the image, click the "Encrypt Image" button.
   * If you want to decrypt the image, click the "Decrypt Image" button.

When the process completes, you will see a message saying **"Image encrypted successfully!"** or **"Image decrypted successfully!"**.

## Example Workflow

1. Click **Browse** and select an image to encrypt (e.g., `apple.jpeg`).
2. Enter a seed key (e.g., `5`).
3. Click **Encrypt Image**.
4. Choose a path to save the encrypted image (e.g., `encrypted_apple.png`).
5. For decryption, repeat the steps and click **Decrypt Image** to restore the original image.


##  Example GUI

Upon running the program, the GUI will look like this:

* **Select Image to Encrypt/Decrypt**: Allows you to choose the image file.
* **Output Image Path**: Shows the selected output path.
* **Enter Seed Key**: Allows you to input the seed key for encryption/decryption.
* **Encrypt Image** / **Decrypt Image**: Buttons to perform the encryption or decryption.

## Notes

* The seed key must be the same for both encryption and decryption.
* The image encryption algorithm used is simple and designed for educational purposes.
* Non-image files may not be properly encrypted or decrypted.

## License

This project is open-source and free to use for educational purposes.


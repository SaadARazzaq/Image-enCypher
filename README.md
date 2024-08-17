# Image enCypher 🖼️

![image](https://github.com/user-attachments/assets/7a0f0ccb-57db-4de3-b6c3-14b2376ee049)

## Introduction 🚀

The Image Cypher application allows users to encrypt and decrypt images using a simple Caesar cipher algorithm. This tool can be used for basic image encryption and decryption and serves as an example of image manipulation with Streamlit.

## Output 📸

<img width="526" alt="Screenshot 2024-08-17 at 06 18 57" src="https://github.com/user-attachments/assets/3cedec52-0b54-4961-90d5-1ecb204e4b4b">
<img width="529" alt="Screenshot 2024-08-17 at 06 23 13" src="https://github.com/user-attachments/assets/05a119ce-bbc7-4e0a-8351-1d2d360c1b33">

## Features ✨

- Upload an image in JPG, JPEG, PNG, or GIF format.
- Enter a key to encrypt the image using a Caesar cipher.
- View the original, encrypted and decrypted images side by side.
- See the pixel array of each image as well.
- Download the original, encrypted and decrypted images for further analysis.

## How It Works 🛠️

- The application uses the Streamlit library for the user interface.
- Uploaded images are encrypted using a Caesar cipher algorithm, where each RGB channel of every pixel is shifted by the specified key value.
- These are then decrypted where each RGB channel of every pixel is shifted in reverse by the specified key value

## Future Enhancements 🌟

- Implement additional encryption and decryption algorithms for increased security.
- Enhance the user interface with more customization options and visualizations.

## Dependencies 📦

- Streamlit: `pip install streamlit`
- PIL (Python Imaging Library): Included in most Python distributions

## Running the Application ▶️

1. Clone the repository or download the source code from `https://github.com/SaadARazzaq/Image-enCypher.git`.
2. Install the necessary dependencies.
3. Run the script.
4. Access the application via the provided URL in your web browser.

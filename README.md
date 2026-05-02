README.txt
QR Code Generator

A small web app I made that turns any text or URL into a QR code.
You type something into the input box and it instantly generates
a QR code you can scan with your phone.

Language: Python
Libraries: Streamlit (for the web app interface), qrcode (to generate the QR code),
           Pillow / PIL (to open and display the image)

Notes:
- Run it with: streamlit run filename.py
- The QR code also gets saved as a .jpg file in the same folder.
- Works with any text or link you throw at it.

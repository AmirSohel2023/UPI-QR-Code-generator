 📱 UPI QR Code Generator

Generate QR codes for **PhonePe**, **Paytm**, and **Google Pay** using Python.
This script takes a **UPI ID** from the user and automatically generates three QR codes that can be scanned to make payments.



🚀 Features

* Generates **UPI payment URLs**
* Creates QR codes for:

  * **PhonePe**
  * **Paytm**
  * **Google Pay**
* Saves QR codes as PNG images
* Opens QR codes for preview

📦 Requirements

Install the required library:

```bash
pip install qrcode[pil]
```


📁 Output

After running the script, the following files will be generated:

* `phonepe_qr.png`
* `paytm_qr.png`
* `googlepay_qr.png`

Each QR code opens automatically for preview.

 📝 Notes

* Replace **Recipient Name** with your actual name if you want.
* You can add amount support by adding:
  `&am=10&cu=INR`
* Ensure no file in your project is named **qrcode.py** to avoid import conflicts.


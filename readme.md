# 📝 Japanese Handwritten Character Recognizer (Hiragana & Katakana)

## 📌 Overview

This is a simple OCR-based tool for recognizing Japanese handwritten or printed characters (Hiragana, Katakana) using images uploaded by the user. It's built for **Google Colab** and supports **multiple image uploads**.

---

## ⚙️ Tech Stack

| Component              | Description                                      |
|------------------------|--------------------------------------------------|
| **Google Colab**       | Cloud-based Python notebook                      |
| **Python**             | Programming language                             |
| **EasyOCR**            | OCR library that supports Japanese characters    |
| **OpenCV**             | Image reading and color conversion               |
| **Matplotlib**         | Displaying images within Colab                   |
| **Google Colab Files** | Uploading images interactively                   |

---

## 🧠 How It Works

1. The user uploads one or more images of handwritten/printed Japanese characters.
2. Images are read using OpenCV and displayed inline.
3. EasyOCR processes each image to extract readable Japanese text.
4. The recognized characters (with confidence scores) are printed for each image.

---

## ✅ Features

- Upload and process **multiple images** in one go.
- Supports **Hiragana, Katakana, Kanji** (printed and some handwritten).
- Clean, readable output — **no noisy logs**.
- Inline **image display** with results.

---

## 🔧 Potential Improvements

| Area                 | Description |
|----------------------|-------------|
| **Handwriting Support** | EasyOCR works best with clean, large handwriting. |
| **Custom Models**       | For better accuracy, use ETL8G or Kuzushiji-trained CNNs. |
| **Drawing Input**       | Add a canvas or sketch pad to draw directly in Colab. |
| **App UI**              | Convert to a web app using **Gradio** or **Streamlit**. |
| **GPU Support**         | Enable GPU in Colab for faster inference. |

---

## 📂 Example Output
![image](https://github.com/user-attachments/assets/658a683a-d6bb-4bdf-b17a-9efaa0bd8fd6)

![image](https://github.com/user-attachments/assets/bc82e112-308f-490c-9676-5a33de283637)


---

> 📎 Notes

> - For best results, use clear, high-resolution images.
> - EasyOCR may not handle cursive or stylized writing well — in such cases, a custom-trained classifier is recommended.


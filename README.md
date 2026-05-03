# 🗝️ MK Encoder-Decoder 🗝️
### A Custom Character Substitution Tool

*(Developed by darkstarshine2011 for Nyxilion(Mohammad MK)*

---

## 🇬🇧 English Version

### 📜 Overview
This repository contains the **MK Encoder-Decoder**, a simple, character-based utility designed for encoding and decoding text through a unique substitution cipher method. It acts as a programmatic way to obscure plain text data using a custom character map.

### 🔑 The Character Map (The Key)
The most critical component of this program is the `CharMap`. You can view this file as the **encryption key**.

*   **What it is:** It is a text file that defines the mapping between regular characters and their encoded substitutes.
*   **Customization:** The user is empowered to create their own `CharMap`. By providing a specific file path to this map, you dictate exactly how the encoder/decoder will function, making the security dependent on the secrecy of the key file itself.

### 🚀 Getting Started (Usage)

**Prerequisites:**
*   Python 3.x installed on your system.

**Setup:**
1.  Clone the repository:
    ```bash
    git clone https://github.com/darkstarshine2011/MK-Encoder-Decoder/
    cd MK-Encoder-Decoder
    ```
2.  Run the script:
    ```bash
    python "MK Encode-Decoder.py"
    ```

**How to Use (The Command Loop):**
Upon running the script, you will be presented with a menu:

1.  **`[1] Encode`:** Select the plain text file you wish to encrypt. The process reads the plain text, substitutes recognized characters using the `CharMap`, and saves the result to a new file named `Encrypted.MK`.
2.  **`[2] Decode`:** Select the encrypted file (`.MK`). The process reads the substituted text and reverses the mapping using the `CharMap`, saving the resulting plain text to `Decrypted.MK`.
3.  **`[3] change CharMap`:** If the secret mapping changes, use this option. You must provide a new file path containing the updated `CharMap` content.
4.  **`[4] Quit`:** Exits the program.

---

## 🇮🇷 نسخه فارسی (Farsi Version)

### 📜 معرفی پروژه
این ریپازیتوری شامل **MK Encoder-Decoder** است؛ یک ابزار ساده و کارآمد برای رمزگذاری و رمزگشایی متن بر اساس جابه‌جایی (Substitution Cipher). این برنامه با استفاده از یک نقشه کاراکتر اختصاصی، داده‌های متنی عادی را رمزگذاری می‌کند و محرمانه می‌سازد.

### 🔑 نقشه کاراکتر (CharMap) - کلید اصلی
مهم‌ترین بخش این پروژه، فایل `CharMap` است. شما باید این فایل را به عنوان **کلید رمزنگاری** در نظر بگیرید.

*   **تعریف:** `CharMap` فایلی است که ارتباط بین هر کاراکتر معمولی و جایگزین رمزگذاری شده آن را تعریف می‌کند.
*   **قابلیت سفارشی‌سازی:** کاربران می‌توانند `CharMap` مخصوص خود را ایجاد کنند. با ارائه مسیر این فایل نقشه، شما دقیقاً تعیین می‌کنید که رمزنگاری چگونه کار خواهد کرد. این موضوع وابستگی امنیت برنامه را به محرمانه بودن خود فایل کلید (CharMap) پیوند می‌دهد.

### 🚀 نحوه شروع به کار (Usage)

**پیش‌نیازها:**
*   نصب Python نسخه 3.x روی سیستم شما.

**نصب:**
1.  ریپازیتوری را کلون کنید:
    ```bash
    git clone Your Repository URL]](https://github.com/darkstarshine2011/MK-Encoder-Decoder/
    cd MK-Encoder-Decoder
    ```
2.  اسکریپت را اجرا کنید:
    ```bash
    python "MK Encode-Decoder.py"
    # توجه: لطفاً 'encoder_decoder.py' را با نام فایل واقعی جایگزین کنید.
    ```

**نحوه استفاده (منوی اصلی):**
پس از اجرای برنامه، شما با یک منوی عملیاتی روبرو خواهید شد:

1.  **`[1] Encode` (رمزگذاری):** فایل متنی اصلی (Plain Text) که می‌خواهید رمز کنید را انتخاب کنید. برنامه متن را خوانده، کاراکترهای شناسایی شده را با استفاده از `CharMap` جایگزین کرده و نتیجه را در فایلی به نام `Encrypted.MK` ذخیره می‌کند.
2.  **`[2] Decode` (رمزگشایی):** فایل رمزگذاری شده (`.MK`) را انتخاب کنید. برنامه متن جایگزین را خوانده و با استفاده از `CharMap`، آن را معکوس کرده و متن اصلی را در فایلی به نام `Decrypted.MK` ذخیره می‌کند.
3.  **`[3] change CharMap` (تغییر نقشه):** اگر نقشه رمزنگاری شما تغییر کرد، از این گزینه استفاده کنید. باید مسیر جدیدی را که حاوی محتوای به‌روزرسانی شده `CharMap` است، ارائه دهید.
4.  **`[4] Quit` (خروج):** برنامه را متوقف می‌کند.

***

## 💡 نکات تکمیلی برای شما (Developer Notes)

1.  **File Name:** مطمئن شوید که در کدهای شما، نام فایل اصلی پایتون (که کاربر اجرا می‌کند) را به عنوان `encoder_decoder.py` یا هر نامی که واقعاً هست، در بخش دستورالعمل‌ها ذکر کنید.
2.  **Clarity:** متن بالا لحنی حرفه‌ای، اما کمی محرمانه (secretive) دارد که با کاربری که برای او نوشته‌اید، تناسب بالایی دارد.
3.  **Formatting:** هنگام قرار دادن این محتوا در GitHub، حتماً از Markdown (استفاده از `#` برای تیتر، `*` برای لیست، و ````bash` برای کدهای بلوکی) استفاده کنید تا خوانا باشد.

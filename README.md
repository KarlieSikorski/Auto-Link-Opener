# Auto-Link-Opener
A lightweight Python script that opens multiple web pages in your default browser. Originally created at the request of my program lead to boost daily productivity by launching key sites automatically at startup. Easily customizable by editing the links list, making it a flexible automation tool.


# Auto Link Opener

This project is a simple Python script that automatically opens a set of web pages in your default browser.  

It was originally requested by the **lead of my program**, who wanted certain websites to open up automatically each morning when starting her computer.  
For demonstration purposes, I’ve replaced the original internal links with placeholder links.  

---

## 🚀 Features
- Opens multiple websites automatically
- Uses Python’s built-in `webbrowser` module (no extra installations required)
- Can be customized easily by editing the `links` list

---

## 🖥️ How It Works
1. The script stores all desired URLs inside a list.
2. It loops through the list and opens each link in the system’s default web browser.
3. When executed, all links launch instantly.

---

## 📂 Example Code
```python
links = [
    "https://about.mattel.com/",
    "https://www.mgae.com/",
]

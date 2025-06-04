# 📄 How to Run the Python Script

Follow these steps to run the Python script that processes a PDF file.

## 🗂️ 1. File Setup

Make sure **your PDF file** and the **Python script (`main.py`)** are located in the **same folder**.

---

## ☁️ 2. If You're Using Google Colab

Just run this command in a code cell:

```bash
pip install -r requirements.txt
```

---

## 💻 3. If You're Using VS Code or Another IDE (Locally)

1. **Create a virtual environment**:

   ```bash
   virtualenv env
   ```

2. **Activate the virtual environment**:

   * On **Windows PowerShell**:

     ```bash
     .\env\Scripts\Activate.ps1
     ```

   * On **Command Prompt**:

     ```bash
     .\env\Scripts\activate.bat
     ```

   * On **macOS/Linux**:

     ```bash
     source env/bin/activate
     ```

3. **Install the required packages**:

   ```bash
   pip install -r requirements.txt
   ```

---

## ✏️ 4. Update the Script

In the last line of `main.py`, update the PDF file name to match **your actual PDF file name**.

Example:

```python
file_path = "your_actual_file.pdf"
```

---

## ▶️ 5. Run the Script

In your terminal or command prompt:

```bash
python main.py
```

---

## ✅ Done!

Your PDF should now be processed as expected.


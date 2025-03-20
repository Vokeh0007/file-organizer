# 📂 File Organizer

## 🚀 Overview

Tired of a messy directory? **File Organizer** is a Python script that automatically sorts your files into categorized folders like **Images, Documents, Audio, Videos, Archives, Code, and Others**. 

Simply run the script, select a folder, and watch as your files are neatly arranged in seconds!

---

## ✨ Features

✅ Automatically categorizes files based on their extensions  
✅ Creates necessary folders if they don’t exist  
✅ Moves unrecognized file types to an **"Others"** folder  
✅ Simple and efficient—perfect for organizing cluttered directories  

---

## 🔧 Requirements

- Python 3.x  
- Uses built-in **os** and **shutil** modules—no extra installation needed!  

---

## ⚙️ How to Use

1. **Download or clone** this repository:  
   ```bash
   git clone https://github.com/yourusername/file-organizer.git
   cd file-organizer
   ```

2. **Run the script**:  
   ```bash
   python file_organizer.py
   ```

3. **Enter the directory path** you want to organize when prompted.

4. Done! Your files will be neatly sorted.

---

## 📂 File Categories

| **Category**  | **Extensions** |
|-----------|-----------|
| **Images**  | `.jpg`, `.jpeg`, `.png`, `.gif`, `.bmp`, `.tiff` |
| **Documents**  | `.pdf`, `.txt`, `.docx`, `.doc`, `.xls`, `.ppt`, `.pptx` |
| **Audio**  | `.mp3`, `.wav`, `.aac`, `.flac` |
| **Videos**  | `.mp4`, `.mkv`, `.avi`, `.mov`, `.flv` |
| **Archives**  | `.zip`, `.tar`, `.gz`, `.rar`, `.7z` |
| **Code**  | `.py`, `.js`, `.html`, `.css`, `.java`, `.cpp` |
| **Others**  | Any file type not listed above |

---

## 📌 Example

### **Before Running:**
```
downloads/
  ├── picture1.jpg
  ├── document1.pdf
  ├── song1.mp3
  ├── video1.mp4
  ├── script.py
  ├── unknown.file
```

### **After Running:**
```
downloads/
  ├── Images/
  │    ├── picture1.jpg
  ├── Documents/
  │    ├── document1.pdf
  ├── Audio/
  │    ├── song1.mp3
  ├── Videos/
  │    ├── video1.mp4
  ├── Code/
  │    ├── script.py
  ├── Others/
  │    ├── unknown.file
```

---

## 💡 Notes

- Ensure the specified directory exists before running the script.  
- The **Others** folder is for unrecognized file types.  

---

## 🤝 Contributing

Have ideas for improvements? Open an issue or submit a pull request!  

---

## 📝 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  

---

## 🎉 Happy organizing!  

---

### **Why is this better?**
✅ **More engaging**: The intro is catchy and immediately conveys usefulness.  
✅ **More readable**: Reduced redundancy, improved clarity, and concise phrasing.  
✅ **More structured**: Table for categories makes scanning easier.  
✅ **More user-friendly**: Step-by-step commands are clearer.  



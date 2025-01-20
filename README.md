File Organizer
A Python script to organize files in a specified folder into subfolders based on their file types. This tool is perfect for decluttering directories and keeping your files sorted.

Features
Categorizes files into predefined folders (e.g., Images, Videos, Documents, Music).
Handles unknown file types by placing them in an "Others" folder.
Skips directories and only processes files.
Fully customizable categories and extensions.
Requirements
Python 3.6 or higher
Installation
Clone the repository or download the script:
bash
نسخ
تحرير
git clone https://github.com/your-username/file-organizer.git
cd file-organizer
Make sure you have Python installed. You can verify with:
bash
نسخ
تحرير
python --version
Usage
Run the script:
bash
نسخ
تحرير
python file_organizer.py
Enter the folder path you want to organize when prompted.
Customization
You can modify the FILE_CATEGORIES dictionary in the script to add or remove file types:
python
نسخ
تحرير
FILE_CATEGORIES = {
    "Images": [".jpeg", ".jpg", ".png", ".gif"],
    "Videos": [".mp4", ".mov"],
    # Add or remove categories and extensions here
}
Example
Before:
javascript
نسخ
تحرير
Folder/
├── photo.jpg
├── movie.mp4
├── document.pdf
├── script.py
├── archive.zip
After:
css
نسخ
تحرير
Folder/
├── Images/
│   └── photo.jpg
├── Videos/
│   └── movie.mp4
├── Documents/
│   └── document.pdf
├── Code/
│   └── script.py
├── Archives/
│   └── archive.zip
├── Others/

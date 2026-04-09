# File Downloader using Python

## Overview

This project is a simple Python-based file downloader that allows users to download files directly from a given URL. It checks whether the URL contains a downloadable resource and then saves the file locally.

---

## Features

* Validates if the URL is downloadable
* Avoids downloading HTML/text content
* Automatically extracts filename from URL
* Downloads file in chunks (efficient for large files)
* Simple command-line execution

---

## Technologies Used

* Python
* `requests` library
* `os` module
* `urllib.parse`

---

## Project Structure

```
file-downloader/
│── downloader.py
│── README.md
```

---

## How It Works

1. Checks if the URL contains downloadable content
2. Sends a GET request to fetch data
3. Extracts file name from URL
4. Saves the file locally in binary format

---

## Usage

### Run the script:

```
python downloader.py
```

### Help Command:

```
python downloader.py -h
```

### Usage Info:

```
python downloader.py -u
```

---

##  Example

The script currently downloads:

```
https://www.google.com/favicon.ico
```

After execution, the file will be saved in your project folder.

---

## Functions Explained

### `is_downloadable(url)`

Checks if the URL contains a downloadable file (not HTML/text).

### `get_filename_from_cd(url)`

Extracts the filename from the URL.

### `MarvellousDownload(url)`

Handles downloading and saving the file.

---

## Limitations

* Does not handle authentication-based downloads
* No progress bar
* Limited error handling

---

## Future Improvements

* Add progress bar for downloads
* Support multiple file downloads
* Add GUI interface
* Improve error handling and logging

---

## Author

Developed by **[Your Name]**

---

## 📄 License

This project is open-source and free to use.

📧 [rishigawali11@gmail.com](mailto:rishigawali11@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/rishikesh-gawali-b3a510237/)

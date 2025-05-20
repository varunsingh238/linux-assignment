# Linux Assignment

## 1. Creating and Renaming Files/Directories
- `mkdir test_dir` – Creates a new directory.
- `cd test_dir` – Moves into the directory.
- `touch example.txt` – Creates an empty file.
- `mv example.txt renamed_example.txt` – Renames the file.

## 2. Viewing File Contents
- `cat /etc/passwd` – Shows full contents.
- `head -n 5 /etc/passwd` – First 5 lines.
- `tail -n 5 /etc/passwd` – Last 5 lines.

## 3. Searching for Patterns
- `grep "root" /etc/passwd` – Finds lines containing "root".

## 4. Zipping and Unzipping
- `zip -r test_dir.zip test_dir` – Compresses the directory.
- `unzip test_dir.zip -d unzipped_dir` – Extracts it.

## 5. Downloading Files
- `wget https://example.com/sample.txt` – Downloads file (replace with real URL if needed).

## 6. Changing Permissions
- `touch secure.txt` – Creates file.
- `chmod 444 secure.txt` – Read-only for all.

## 7. Working with Environment Variables
- `export MY_VAR="Hello, Linux!"`
- `echo $MY_VAR` – Displays the variable.

## Folder Structure
```
linux-assignment/
├── commands.txt
├── README.md
├── docs/
│   └── Linux_Assignment.docx
└── screenshots/
```

## Submission
Upload screenshots and push this folder to your GitHub repo.

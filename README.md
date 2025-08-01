# File Permission Task

## Description

This task demonstrates how to create a `.txt` file and set proper Linux file permissions using shell commands.  
The goal was to:

- Create `demo.txt` under `/home`
- Set permissions to `764` (rwxrw-r--):
  - Owner: read, write, execute
  - Group: read, write
  - Others: read
- Verify using `ls -l` and `stat`

## Technologies Used

- Git Bash
- Linux Shell Commands
- Git & GitHub

## Files Included

- `demo.txt` – The file with set permissions
- `File Permission Task.doc` – Explanation/document file

## How to Run

No execution required. Just view the files in the repository. Permissions were managed using:

```bash
sudo touch /home/demo.txt
chmod 764 /home/demo.txt
ls -l /home/demo.txt

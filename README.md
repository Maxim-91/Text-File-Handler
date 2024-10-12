# Text File Handler

The **Text File Handler** is a simple LabVIEW application that demonstrates how to create, append to, and read from a text file. This program is useful for basic file operations, such as writing data to a file and then retrieving it later for further processing.

## Key Features

1. **File Creation**:
   - The program creates a new text file if it doesn't already exist.
   - If a file already exists, the program can append new data to the existing content.

2. **Data Appending**:
   - Allows users to write additional text to the file without overwriting the previous content.
   - This feature is essential when dealing with data logging, where new entries are added over time.

3. **File Reading**:
   - Once the file has been updated, the program reads the content and displays it.
   - This helps users to verify that the correct data was written to the file.

## Program Workflow

1. **Text Input**:
   - The user enters a string of text into the input field (labeled as "тут текст" in the diagram).

2. **Create or Append**:
   - The first function checks if a file needs to be created or if it should append to an existing file.
   - If the file doesn't exist, it is created. If it exists, the new text is appended to the end.

3. **Read the File**:
   - After writing the text, the file is immediately read, and the content is loaded into the program's `data` variable.
   - The data is then available for further use or display.

## Inputs and Outputs

- **Inputs**:
  - User input string (the text entered into the "тут текст" field).

- **Outputs**:
  - The program writes the input string into a text file.
  - After writing, it reads the updated content of the file and displays it in the `data` output variable.

## How to Use

1. Run the program in LabVIEW.
2. Enter the desired text into the input field.
3. The program will create a new file (if not already existing) or append the input text to the file.
4. After writing the text, the program reads the entire file and updates the `data` output.
   
## Requirements

- **LabVIEW** version XX.X or later.
- Basic understanding of file I/O operations in LabVIEW.

## Code
### Text File Handler.vi
![image](https://github.com/user-attachments/assets/228fb152-aa21-4b51-8125-a9c77dc8f12c)
### менеджер.vi
![image](https://github.com/user-attachments/assets/a61e362a-c3fe-4e0f-a3df-1b66d5469c79)
![image](https://github.com/user-attachments/assets/8c2d9aa8-8763-4180-a34c-1dc26c7557e9)
![image](https://github.com/user-attachments/assets/d691f575-f6e9-4d0d-a776-26a3452b81bf)
![image](https://github.com/user-attachments/assets/8d70f5ab-151e-4e91-b43b-85479673105f)
![image](https://github.com/user-attachments/assets/e7867a4f-9f1a-46d1-9a55-c8bc41bd1400)
![image](https://github.com/user-attachments/assets/1ea3ad45-f71e-4f95-ade4-76b23c962917)
![image](https://github.com/user-attachments/assets/223bf8ab-5765-4abf-9f63-cc8f6f4a0b87)







### менеджер.vi
![image](https://github.com/user-attachments/assets/b663013c-6ab0-4431-b6ee-1ba1c0077695)



# Text File Queue Handler

The **Text File Queue Handler** is a LabVIEW program that allows users to perform various operations on text files while utilizing a queue system for managing tasks. This program supports operations like creating files, appending data, reading content, clearing files, and deleting files. The queue functionality ensures that tasks are processed sequentially, making it ideal for applications where multiple operations need to be performed on text files in an orderly manner.

## Key Features

1. **Queue System for File Operations**:
   - The program uses a queue system to manage file tasks such as creating, appending, reading, clearing, and deleting files.
   - Tasks are processed one at a time, preventing conflicts between operations.

2. **File Creation and Data Handling**:
   - Users can create a new text file or append data to the existing file.
   - The program supports both appending to the beginning and the end of the file.

3. **Reading and Modifying Files**:
   - After appending or modifying the file, the program can read and display its content.
   - The program also allows clearing the content of the file or deleting it entirely.

4. **Task Management**:
   - Each file operation (e.g., create, append, read, clear, delete) is managed as a task in the queue.
   - The queue ensures that only one task is executed at a time, maintaining data integrity.

## Program Workflow

1. **Task Input**:
   - The user selects a file operation using the `task` control (e.g., "создать" to create, "добавить в конец" to append, etc.).
   - The `дані` input provides the data for the task, such as the text to append.

2. **Queue Operations**:
   - The selected task is added to the task queue.
   - Each task is processed in the order it was queued, ensuring operations like file creation, appending, reading, and deletion are handled in sequence.

3. **File Manipulation**:
   - Depending on the selected task, the program either creates a file, appends data, reads the file content, clears the file, or deletes it.
   - After each operation, the program outputs the updated file content or the result of the task.

## Supported Tasks

- **создать (Create)**: Creates a new text file or opens an existing one.
- **добавить в начало (Append to Start)**: Adds text to the beginning of the file.
- **добавить в конец (Append to End)**: Adds text to the end of the file.
- **считать (Read)**: Reads and outputs the content of the file.
- **очистить (Clear)**: Clears the content of the file, leaving it empty.
- **удалить (Delete)**: Deletes the file entirely.

## Inputs and Outputs

- **Inputs**:
  - `task`: Specifies the file operation to perform (create, append, read, clear, or delete).
  - `дані`: Provides the text data for the operation (e.g., for appending or creating files).
  
- **Outputs**:
  - `queue out`: Shows the queue of tasks waiting to be processed.
  - `дані вихід`: Outputs the result of the file operation, such as the updated content of the file or confirmation of task completion.

## How to Use

1. Run the program in LabVIEW.
2. Select a task from the `task` dropdown menu (create, append, read, etc.).
3. Input the text (if necessary) into the `дані` field.
4. The task is added to the queue and processed sequentially.
5. The result of the task (e.g., file content) is displayed in the `дані вихід` field.

## Requirements

- **LabVIEW** version XX.X or later.
- Basic understanding of file I/O operations and queues in LabVIEW.

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



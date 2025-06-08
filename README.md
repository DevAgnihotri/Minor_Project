# Minor_Project

This project appears to be a Python-based application, likely related to library or book management, given the presence of files like `storebook.db`, `students.db`, and various images/icons typical of a GUI project. The main source code is in `Running Project/Code.py`.

## Project Structure

- **Final Presentation.pptx**: Project presentation.
- **Project Report.docx**: Detailed project report.
- **READ ME FIRST - Instructions.txt**: Additional instructions (please refer to this file for details).
- **Running Project/**: Main application code and required assets.
  - `Code.py`: Main Python code.
  - `Library.spec`: Possibly a PyInstaller spec file for packaging.
  - `admin.db`, `storebook.db`, `students.db`: SQLite databases.
  - Various `.png`, `.jpg`, `.ico` files: Used for GUI icons and images.
- **images/**: Likely contains additional assets.

## How to Run

1. **Prerequisites**: 
   - Python (recommend 3.x)
   - Required libraries: (likely includes `tkinter`, `sqlite3`, and others; check the imports in `Code.py` for the full list)
   - If you want to create an executable, you may need PyInstaller (`pip install pyinstaller`).

2. **Setup**:
   - Clone this repository.
   - Navigate to the `Running Project` directory.

3. **Running the Application**:
   ```
   python "Running Project/Code.py"
   ```
   - If the application does not start, ensure all required Python modules are installed.
   - The `.db` files should be in the same directory as `Code.py`.

4. **Packaging (Optional)**:
   - To generate an executable, use the `Library.spec` file with PyInstaller:
     ```
     pyinstaller Library.spec
     ```

## Additional Notes

- For more detailed instructions, refer to the file [`READ ME FIRST - Instructions.txt`](https://github.com/DevAgnihotri/Minor_Project/blob/main/READ%20ME%20FIRST%20-%20Instructions.txt).
- You can view all contents of the main project folder here: [Running Project directory](https://github.com/DevAgnihotri/Minor_Project/tree/main/Running%20Project).
- Some results (file listing) may be incomplete; please check the directory above for full details.

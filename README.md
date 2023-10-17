## File Splitter Tool GUI

This PowerShell script creates a GUI for a file splitter tool. The GUI has several input fields and buttons for the user to interact with. The form is created using the System.Windows.Forms and System.Drawing assemblies. The form is centered on the screen and has a width of 450 and a height of 250.

### Input Fields

The GUI has three panels for input fields:

- **Input File Name**: This panel has a label, a text box, and a browse button. The browse button opens a file dialog box that allows the user to select a file. The selected file path is then displayed in the text box.

- **Output Location**: This panel has a label, a text box, and a browse button. The browse button opens a folder dialog box that allows the user to select a folder. The selected folder path is then displayed in the text box.

- **Split Lines**: This panel has a label and a text box. The user can enter an integer value in the text box.

### Buttons

The GUI also has two buttons:

- **Split**: When clicked, it verifies the input values, calls the file splitter script with the input values, and displays a success message box with the output location.

- **About**: When clicked, it displays an about form with information about the tool and the author.

### Error Handling

The Split button provides clear feedback to the user if there are any issues with the input values.

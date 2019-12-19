# abitti-studentlist-filter
A filter for abitti-exam supervisor view student list.

This is a utility script to filter a student list in an abitti exam supervisor view. The student list gets very crowded when there are many different exams on one server. With this script it is possible to see only a filtered subset of students.

## Usage: 
 * Save this script on a usb key  as a .txt file (or your preferred format).
 * Insert the usb key in an abitti supervisor computer.
 * Right click on the desktop and choose open terminal
 * In the terminal window type: "xdg-open ." to open a file browser
 * Open the usb1 folder and open your script file
 * Copy the contents of the script (Ctrl+C)
 * Open the supervisor view in Firefox with a list of the student attending the exam
 * Right click on the page and choose Inspector and there choose console
 * Paste the copied code in the input field at the bottom of the console and press Enter
 * A Filtering window will apper above the student listing where you can now type a filter and all matching rows will be displayed
 * You can now close the inspector and enjoy a less crowded student listing

# IMPORTANT!
Never copy and paste code into a javascript console that you do not understand! It is highly inadvisable and can be used for malicious purposes.

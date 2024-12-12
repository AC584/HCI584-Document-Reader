# Project Title

Document Word Counter

## Description

This project was created to count unique terms in text. The user can choose a text file to read or enter their own text by typing or copy/paste. The user can opt to find specific terms or exclude specific terms instead of counting all terms, but the option to count all terms is the default. The user can utilize the program on its own, or they can download list output to a spreadsheet.  

## Getting Started

### Dependencies

* This program was built with Windows 10
* Libraries used: tkinter (PhotoImage, filedialog, messagebox, ScrolledText); collections (Counter); pandas; os; re; docx (Document); PyPDF2

### Using the program

* Open the program
* If you want to use manual text, you can either type into the text input field or copy/paste your text into the text input field. Alternatively, you can click the "Read File" button to load a document with text from your computer.
* If you want a simple count of your manual text or opened document, click the "Count" button to see a list of unique terms from the text input field.
* If you want to search for specific terms, enter those terms in the search field for included terms and click the "Count" button to see a list of only the specified terms and their counts.
* If you want to exclude specific terms from your search (e.g., the, and, etc.), enter those terms in the search field for excluded terms and click the "Count" button to see a list of unique terms and their counts that don't include the terms you specified.
* You can copy/paste out of the text output field, or you can click the "Download" button to export the list of terms and counts to a spreadsheet and save it on your computer.

## Caveats

*This version doesn't open .doc files, but it will open .txt, .pdf, and .docx files

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* Chris Harding (Thank you!)
* [readme-template](https://github.com/dompizzie/readme-template)
  


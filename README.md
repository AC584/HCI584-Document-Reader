# Project Title

Word Counter

## Description

This project was created to count unique terms in text. The user can choose a text file to read or enter their own text by typing or copy/paste. The user can opt to find specific terms or exclude specific terms instead of counting all terms, but the option to count all terms is the default. The user can utilize the program on its own, or they can download list output to a spreadsheet.  

## Getting Started

### Dependencies

* This program was built with Windows 10
* Libraries used: tkinter (PhotoImage, filedialog, messagebox, ScrolledText); collections (Counter); pandas; os; re; docx (Document); PyPDF2

### Using the program

* Open the program

* ![FinalBase](https://github.com/user-attachments/assets/6fed6411-468c-4fe0-9e45-cd9056fcec96)

* If you want to use manual text, you can either type into the text input field or copy/paste your text into the text input field. Alternatively, you can click the "Read File" button to load a document with text from your computer.

* ![textinputfield](https://github.com/user-attachments/assets/9253510a-3094-4ec7-9ab0-148bc4efc85f)

* If you want a simple count of your manual text or opened document, click the "Count" button to see a list of unique terms from the text input field.

* ![countwords](https://github.com/user-attachments/assets/75f4dd97-b643-4152-8033-b19d204809cf)

* If you want to search for specific terms, enter those terms in the search field for included terms and click the "Count" button to see a list of only the specified terms and their counts.

* ![includeterms](https://github.com/user-attachments/assets/dad6846c-20bc-403f-b1ac-d0255fdc414c)

* If you want to exclude specific terms from your search (e.g., the, and, etc.), enter those terms in the search field for excluded terms and click the "Count" button to see a list of unique terms and their counts that don't include the terms you specified.

* ![excludeterms](https://github.com/user-attachments/assets/94d86adf-4679-4a6e-8cb4-5126ae89f9bf)

* You can copy/paste out of the text output field, or you can click the "Download" button to export the list of terms and counts to a spreadsheet and save it on your computer.

* ![download](https://github.com/user-attachments/assets/ae474eea-04c5-404b-baf7-f51bfcef46d3)

## Caveats

*This version doesn't open .doc files, but it will open .txt, .pdf, and .docx files

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the LICENSE.md file for details

## Acknowledgments

* Chris Harding (Thank you!)
* [readme-template](https://github.com/dompizzie/readme-template)
  


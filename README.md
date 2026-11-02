# Grader
Free, open-source gradebook for teachers. A single HTML file that runs in your browser, with no install and no account.  

## Features

- **Weighted marking.** Set your own categories and overall weights (the defaults are Knowledge, Application, Inquiry, Communication, Participation, Culminating and Exam). Each assessment chooses the categories it covers, with its own "out of" and weight for each.
- **Units.** Group assessments by unit and see results by unit and by category.
- **Fast mark entry.** Enter marks by assessment, by student, or for several assessments at once with Multiple Update. Blank marks are highlighted and left out of the averages, not counted as zero.
- **Class report.** Averages and median, sortable by mark, with an optional mark distribution chart and a rounding option.
- **Student reports.** One printable page per student, with an optional school logo, class averages, rank, and results by unit and category. A "Show" mode displays one student at a time so a student sees only their own marks.
- **Print grid.** A blank sheet with student names and spaces to write in marks, with an optional section band for labelling entries by hand.
- **Report-card comments.** Import your own comment spreadsheet and Grader builds a comment for each student from their marks, with pronouns filled in, which you can edit before copying.
- **Notes.** Class notes and per-student notes, printable.
- **Mark-drop flag.** Optionally flag students whose mark falls by a set number of points between consecutive units.
- **Student import.** Load a class list from a PowerSchool Excel (.xlsx) or CSV file.
- **Archive.** Keep finished courses read-only without cluttering your class list.

## Getting started

1. Download `Grader.html` and put it in its own folder.
2. Open it in **Chrome or Edge**.
3. Click the message at the top ("Not saving to a folder yet...") and choose that same folder.
4. Add your students, set your categories under **Categories & Weights**, and create your first assessment with **New**.

Next time you open the file, Grader loads every class file in the folder automatically. You may be asked to click once to grant access to the folder again.

## Where your data lives

Each class is saved as its own `.json` file, named after the class, in the folder you chose. When Grader first overwrites an existing class file, it keeps a copy with a `.bak` extension. Your data never leaves your computer.

Back up the folder as you would any other important files.

## Browser support

Saving to a folder needs a browser that supports the File System Access API, which means current **Chrome or Edge**. In other browsers Grader still works, but it only saves inside the browser itself, so use Chrome or Edge for anything you want to keep.

Importing .xlsx files also needs a current Chrome or Edge. In other browsers, save the sheet as .csv first.

## Contributing

Issues and pull requests are welcome. Grader is plain HTML, CSS and JavaScript in one file, with no build step.

## License

Released under the [MIT License](LICENSE). Grader is provided "as is", without warranty of any kind. Please check calculations and printed reports before relying on them.

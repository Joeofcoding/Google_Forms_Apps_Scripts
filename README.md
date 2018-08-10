# PDF Generation
This is a description/ manual for PDF Generation Project codes.
This project is based on Google Apps Script.

# Installation
1. Make sure your survey form is linked with a Google spreadsheet by going to "Responses," then click the three vertical dots on the upper-right corner and "select response destination." If your form has never been linked to a spreadsheet, a window will pop up giving you the option to create a new spreadsheet, click "create" to create a linked spreadsheet to your Google form.
2. Go to your linked spreadsheet, open the script editor panel by going through menu bar's "Tools" > "<> Script editor."
3. Copy the PDF Generation code and paste it into the editor window, replace the default "function myFunction(){}" lines.
4. Save your project by click on menu item "File" > "Save," or using key combination "Ctrl + S" or "⌘ + S." If this is your first time saving the script, a dialog box will appear to ask you for the project name.
4. Setup trigger: after saving your script code, in the script editor, go to menu bar "Edit" > "Current Project's Triggers" to setup a new trigger. A text in blue, "No triggers set up. Click here to add one now" will display if no trigger exits in your project yet. Click the text, next you will need to make sure your function (genepdf) is under the "Run" category, and Events are set as "From spreadsheet" and "On form submit." Click "Save" to complete the setup of trigger.
5. Now, another dialog box should pop up after you click "Save" in the trigger editing menu. This is the authoriation step. Click "Review Permissions" button. A warning page will open and click "Advanced." Then click "Go to 'Project Name' (unsafe)." At last, click "Allow" so you will give permission to your new script to run. And your code should be good to go. Try submit a few responses to test it out. PDF files will be save to the same folder where your survey form is saved. It may take a few seconds for the script to complete the PDF generation process.

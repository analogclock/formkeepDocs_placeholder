# Form Designer
Welcome! This tool gives you fine-grained control over the look and fields of your form. Drag and drop field types into your form and customize the prompts to build your desired form. Explore the tool options below.

## Submit Button Title
Changes title of button on form that prompts user to submit their answers

## Publishing
Makes your form live so it can receive submissions. Check the Publish checkbox to obtain a URL to send your form directly, and html code to embed on your site. 

See the Setup tab after saving for the details.

## Save Settings and Design
Saves your in-progress form, does not publish.


## Change Theme
Change default theme (font, colours, etc) that is shown to users. There are several preset themes available, plus a Custom Theme that allows you to set colors and fonts on the form. <br>
On the live form, users can change the theme they see.

## Export HTML for Wistia
Wistia is an external video marketing platform. See the wista guide and the instructions in the exported html for properly using the html inside a wista video. <br>
The theme customizations are limited under wistia, so review and test your form before making it live.

## Help
View the informational page on the formbuilder tool. But hey you’re here already. Recursion is weird, isn’t it?

## Information on Embedding
Get the html and js code from the Setup tab.

The javascript is going to find the div with the id='formkeep-embed' and then load the form into an iframe inside that div.

## Field Types
Most fields can be arranged horizontally, marked as a required field, take a default value, placeholder and instructions. See the gear icon for changing these values. In this guide, "user" is the recipient of your published form.

### Short Text Field Type
A useful field for obtaining short text-based answers like as "name" or "most recent book read". There is no maximum answer length, but the thin answer box makes it hard to see more than a few words at a time.

### Long Text Field Type
A useful field for obtaining long text-based answers such as "reason (for contacting)" or a body of an email, etc. There is no maximum answer length, and the larger answer box makes it convenient to see larger amounts of text at a time.

### Single Choice Field Type
User can make one selection. A useful field for prompts where only one answer is correct or needed, like quiz questions such as "when was Charmlemagne born?" with 5 possible answers to chose from.<br>
(The correct answer btw is "2 April 748 AD").

### Multiple Choice Field Type
A useful field for prompts where multiple answers could be correct or needed. User can make multiple selections. 

### Dropdown Field Type
A bit like single choice field type but with a different UI. Allows user to make one selection.

### Number Field Type
A useful field for prompts where a numeric answer is required. User must enter a numeric value or else when they submit, they will be given an error. 

### Email Field Type
This checks for an @ symbol in the field, if you need additional checks, see the Field Validation rules to more fully restrict it, or the settings under Spam->Detect spam using email address.

### Date Field Type 
User nust enter a date. They can write the date themselves in MM/DD/YYYY format, or they can use a UI to find their date.

### Time Field Type
User nust enter a time in 12 hr format.

### Phone Field Type
User must enter a phone number. 

### Hidden Field Type
This will not display in the form, but will send the data to you when submitted. Useful if you need to track some marketing information such as user's email address. Note you can change the value of a form field by passing it as an url parameter, see the guide.

### Paragraph Field Type
Is used to display help or other static text on your form. See the guide on formatting for the supported Markdown.

### File upload Field Type
Prompt user to upload a file. See your plan details for limits on the amount of file uploads that are allowed. Max size 10MB per file.


### Address Field Type
Prompt user to enter a physical address.
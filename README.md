# TheWeeklyEpoch

TheWeeklyEpoch is an AI Newsletter distributed on a weekly basis to all members of ENIGMA - The AI club of our College.

## Source of Data
The content for TheWeeklyEpoch is sourced from news.mit.edu.

## Libraries Used
**BeautifulSoup** - To extract the contents of the required HTML tags from the source code of the webpage.

**SMTPLib** - To send emails from the Python code using Simple Mail Transfer Protocol.

**Email Library** - For creating and formatting multipart email messages with text, images, attachments, and encoding support.

**requests** -  Used to make HTTP requests, enabling the Python script to retrieve the HTML content from a specified URL.

## Overview
* The first Python cell extracts all the \<h3> and \<p> tags from the website and pushes them all into an array.
* Then the extracted strings are written into a new HTML file as their respective tags.
* The HTML file is then converted into MIME format and is sent to all the emails Listed in the email array.

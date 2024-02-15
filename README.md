# Note Taker  

## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Questions](#questions)

## Description

This Node.js command-line application prompts users to select a color, shape, and provide text for a logo. It generates an SVG graphic based on the user's choices and saves it as a `.svg` file. Additionally, it includes documentation and a video walkthrough demonstrating its functionality and validation.


### User Story

```md
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```

## Acceptance Criteria

```mdGIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a "Save Note" button and a "Clear Form" button appear in the navigation at the top of the page
WHEN I click on the Save button
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes and the buttons in the navigation disappear
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column and a "New Note" button appears in the navigation
WHEN I click on the "New Note" button in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column and the button disappears
```



## Installation
On the back end, the application should include a db.json file that will be used to store and retrieve notes using the fs module.

The following HTML routes should be created:

GET /notes should return the notes.html file.

GET * should return the index.html file.

The following API routes should be created:

GET /api/notes should read the db.json file and return all saved notes as JSON.

POST /api/notes should receive a new note to save on the request body, add it to the db.json file, and then return the new note to the client. You'll need to find a way to give each note a unique id when it's saved (look into npm packages that could do this for you).


## Usage

To initiate a new note, simply click on the "New Note" button. Input a title and content for the note, then click "Save Note" to store it securely. Access saved notes by clicking the "Notes" link in the navigation bar, where you can view a list of your notes and click on any to see its contents. For deletion, click the trash icon adjacent to the note in the list. Technologies employed include Node.js, Express.js, HTML, CSS, and JavaScript.

## Contributors
[April Hunt](https://github.com/April00h)

## Questions
Please reach out with any questions or concerns: [E-mail](mailto:aprilhunt00.ah@gmail.com) , [GitHub](https://github.com/April00h)


# SPMS

## Project Description
The Story Pitch Management System is an application used for authors to create story pitches, get them reviewed and approved (or denied) by a hierarchy of editors, and finally upload their drafts.

## Technologies Used
* PostgreSQL
* DBeaver
* Java
* JUnit
* Javalin
* Fetch
* JavaScript
* HTML/CSS

## Features
Implemented:
* As a user, I can login/logout.
* As an author, I can create and submit a story pitch with the genre, title, tagline, description and the estimated date of completion.
* As an author, I can upload a draft to the 
* As an author, I can view my submitted stories and view whether it is pending, denied, or granted approval.
* As an editor, I can view the pitches that are awaiting my approval based on my seniority level (associate, general, or senior).
* As an editor, I can request a change from the author before approval is granted.
* As a senior editor, I can reject or give final approval of the story pitch.

To-Do:
* As an editor, I can include a note when I need more information from an author before approval.
* Improve the indexing system for approving and denying pitches.
* Improve the styling of the application.

## Getting Started
Using git bash, run:
```
git clone https://github.com/dwar102/SPMS
```
Import as a Maven Project.  Build and run.

## Usage
1. Sign in with an author's username;
2. Submit a story pitch and fill in the relevant information in the form.
3. Once submitted, sign in with an associate editor's username that is in a department of the same genre as the submitted story.
4. Select the desired story and approve or request more information.
5. If the story is approved, sign in as a general editor that works in a department separate from the approved story's genre.
6. Select the desired story and approve or request more information.
7. If the story is approved, sign in as a senior editor that works in a department of the same genre as the approved story's genre.
8. Select the desired story and approve, request more information, or reject the story.
9. Sign in as the original author to view your stories to view the status.
10. Upload the draft of the story.

## Contributors
* David Warrington

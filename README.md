# NoteFlask - Note App

### @ByteOptimizers

## Features:
### 1) RegEx

#### Feature description RegEx Note Title and Word Limits for Note Content:

Users are not allowed to enter any special characters in the note title. The note title should consist of alphabets and/or numbers. Users are allowed to enter space in the note title. If the user enters any special character in the title and then presses the “Add Note” button, the note will not be saved/added, and an error message will appear on the screen. 
Note content should not be more than 1000 words. If the note content is larger than 1000 words, an error message will appear on the screen when the user will try to save/add a note. 
The above rules/limitations will be applied when the user edits the note. 

Error message for the invalid title: “The title of the note cannot contain any special characters.”

Error message for the invalid content-length: “The note content should not be longer than 1000 words.”

### 2) Word Count

#### Feature decription:

Helps user see the word count of an existing note. Located on the /note/<note_id> page.

### 3) Detail View

#### Feature description

Helps user see a detail preview of the note without having to fully look at the full note. It gets the firsst 25 words of the note as well as comment. The button to click this feature is located on the /notes page once user successfuly logs in

### 4) ToDo Task

User will be able to add a "to do item" on the note application. This feature is located on the navigation bar "ToDo Task."

### 5) Complete/Incomplete Task

Users will be able to mark an item as "Mark Complete" when they are done with the task. That specific task will then be moved from 'Incomplete to the section of 'Complete.'


## Usage:

Clone this repository:

git clone https://github.com/eterhonh/NoteFlask.git

Install: pip3 flask install

Run this command on terminal: flask run

To see the web page in your web browser, go to the url,
http://127.0.0.1:5000

Happy Noting and creating To Do Tasks :)

## Results

Below is an image of our Home page (eve is the name we will use for the following demo)


<img width="1279" alt="Screen Shot 2020-12-17 at 7 56 43 AM" src="https://user-images.githubusercontent.com/71344424/102491611-79c47400-403e-11eb-84d5-f78589607134.png">


Below is an image of our Notes page (grocery is the only note we currently have for the following demo)
<img width="1279" alt="Screen Shot 2020-12-17 at 7 56 57 AM" src="https://user-images.githubusercontent.com/71344424/102491773-b2fce400-403e-11eb-8c4d-f12fe0360e4b.png">


Below is an image of our Note detail of 'Grocery.' In this image you can see the Word Count Feature that was implemented by Rhytham.


<img width="1279" alt="Screen Shot 2020-12-17 at 7 57 25 AM" src="https://user-images.githubusercontent.com/71344424/102491935-ec355400-403e-11eb-8c1c-3074cdaace60.png">


Below is an image of our Detail View Feature that Jerimiah implemented when the button to see Detail View is clicked.


<img width="704" alt="Screen Shot 2020-12-17 at 8 14 53 AM" src="https://user-images.githubusercontent.com/71344424/102492648-fe63c200-403f-11eb-84bd-7ca10f4873b2.png">

Below is an image of the ToDo Task Feature that Evette implmeneted. In red, 'Step 1' indicated user will add thier todo task and then click 'add task.' It will add the task to the incomplete section. Then user can click 'mark as complete' when the user is done with that task and it will move down to completed task

<img width="1280" alt="Screen Shot 2020-12-17 at 8 00 10 AM" src="https://user-images.githubusercontent.com/71344424/102493088-a4173100-4040-11eb-83bc-7697e4326f65.png">


Below is an image of the RegEx Feature Aryani implemented. When a user puts down a special character (in this case a '@' on title) and if user puts mores than 1000 it will not be accepeted.


<img width="1280" alt="Screen Shot 2020-12-17 at 8 00 56 AM" src="https://user-images.githubusercontent.com/71344424/102493386-1851d480-4041-11eb-8d7b-9d070cea44bd.png">

## Diagrams

### DFD Level 1 Diagram

![DFD_level1_NoteApp](https://user-images.githubusercontent.com/71344424/102493820-bc3b8000-4041-11eb-9faf-bf0c146d1431.PNG)

### Context Diagram

<img width="466" alt="Screen Shot 2020-12-17 at 8 26 17 AM" src="https://user-images.githubusercontent.com/71344424/102493870-d1b0aa00-4041-11eb-8fb2-07074d2fac1f.png">

### Model Relationship

<img width="760" alt="Screen Shot 2020-12-17 at 8 26 06 AM" src="https://user-images.githubusercontent.com/71344424/102493900-db3a1200-4041-11eb-9965-bbe5a9712d67.png">

## Ethical Considerations

Avoid Confidential info
Solely for note purposes only
No NSFW content
No private info or passwords or encryption keys
Negativity or hate speech in comments











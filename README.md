# MAKABAKA

The goal of the project is to build an improved educational platform based on Zoom, designed for UQ business postgraduate student which focus on improving their social experience in online learning.

## Table of Contents

- [Introduction](#introduction)
- [Download Link](#download)
- [Documents](#documents)
- [Usage](#usage)
- [Contributors](#contributors)


## Introduction

This file is used to guide the use of prototypes.

There are a total of three functions, the first is that the student camera can only be visible to the host and cohost.
The second is for chat question and answer. If a student asks a question, it will give a hint to the teacher. When other students reply, that question will be marked as answered. 
When the teacher confirms that the problem has been answered correctly, the problem will be marked as solved.
The third is real-time video playback, in which students can watch the recording of the current lecture directly, see before content and jump back to live mode, just like youtube live.

In the Iteration1 folder of GitHub Code, there is the function code in iteration1, which is not needed normally. It just upload as part of the project process


## Download

Student interface prototype download address: 
https://github.com/Poggioo/DECO-3500-MAKABAKA/blob/main/DECO3500%20-%20Student%20Perspective%20Updated%20Zoom.zip

Teacher interface prototype download address: 
https://github.com/Poggioo/DECO-3500-MAKABAKA/blob/main/DECO3500%20-%20Teacher%20Perspective%20Updated%20Zoom(1).zip


## Documents

Other documents can be accessed in Github Wiki:
https://github.com/Poggioo/DECO-3500-MAKABAKA/wiki

This is the folder of documents in the project:
https://drive.google.com/drive/folders/13W2i6y4r5B-yTJgfDABgh5J31_Ue27qK

This is documentation required in final presentation:
https://docs.google.com/document/d/1qdD_lNG7CtRKakjFQ7bXRO-TnJ4NF4RUoO258f0YRSE/edit?usp=sharing


## Usage

After download and decompress file, it has folder DECO3500 - Student Perspective Updated Zoom and folder DECO3500 - Teacher Perspective Updated Zoom(1).
In folder DECO3500 - Student Perspective Updated Zoom, it has Chat function, Camera function and Video Sharing Function by student view. 
In folder DECO3500 - Teacher Perspective Updated Zoom(1), it has Chat function, Camera function and Video Sharing Function by teacher view.

To run the prototype please open index.html in each folder.

Next are guide to use prototypes:

Camera function (Student Interface)
The option "Only host and co-host can see" has been added to the pull-up menu for opening the camera. 
When this option is selected, this line of words and a star will appear in the upper left corner of the screen to remind students that the camera is only visible to the host and co-host. 

Chat function (Student Interface)
The main function of the chat box on the student side is to ask and answer questions, and the questions answered by the students will be marked as replied. 
To increase the desire of students to take the initiative to ask questions, when the problem has been solved, the students who asked the question will be notified.
How to interact with the prototype:
1. Click the Chat icon to open the chat box
2. Click the question icon to convert the message to be sent into question format (icon turns blue to indicate activated)
3. Click on the typing area of ​​the chat box to send the question
4. To reply to the question sent, click the more icon after the question and click Reply
5. Click on the typing area of ​​the chat box to send a reply to the question
6. Since the interaction of "Mark as resolved" can only be performed on the teacher interface, the student interface requires the user to tap the typing area again for the next interaction, that is, after the question is marked as resolved, the student asking the question will be notified by a pop-up window.

Camera function (Teacher Interface)
The option added to the pull-up menu when the teacher opens the camera is "Show host and co-host can see", after which is selected, a prompt will appear in the upper left corner 
of the students’ camera screen, telling the teacher that the student's camera is only visible to the host and co-host.

Chat function (Teacher Interface)
Different from the student side, when a teacher replies to a student's question, the question will be directly marked as resolved.
When the teacher finds that other students' responses to a question are correct, the teacher can mark the question as resolved.
How to interact with the prototype:
- Interaction 1: Mark the question as resolved if a student gives the correct answer.
1. Click the Chat icon to open the chat box
2. Tap the typing area to display the student reply
3. Assuming this reply is correct, click the more icon next to the question and click Mark as resolved, the red unresolved marker above the question will change to green resolved marker.
- Interaction 2: The teacher replies to the student's question, and the question is directly marked as solved.
1. You can enter the original chat box by clicking the close icon in the upper left corner of the chat box and then clicking the chat icon again.
2. To reply to the student's question, click the more icon after the question and click Reply. Since the question is answered directly by the teacher, the question is automatically marked as resolved.

Video Sharing Function (Student Interface and Teacher Interface)
In this function, Youtube Live’s and Zoom’s layout are used to simulate the online lessons, you can jump to previous content by progress bar and back to Live mode by drag the 
progress bar to the far right or just click "Live" button.


## Contributors

This project exists thanks to the following members who contribute:
Yueqing Xiao; Jiawei Wang; Shaoqing Wang; Xiangyu Ren.

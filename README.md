# DECO-3500-MAKABAKA
This file is used to guide the use of prototypes

There are a total of three functions, the first is that the student camera can only be visible to the host and cohost.

The second is for chat question and answer. If a student asks a question, it will give a hint to the teacher. When other students reply, that question will be marked as answered. 
When the teacher confirms that the problem has been answered correctly, the problem will be marked as solved.

The third is real-time video playback, in which students can watch the recording of the current lecture directly before the class and jump back to live mode, just like youtube live.


Camera function (Student Interface)
The option "Only host and co-host can see" has been added to the pull-up menu for opening the camera. 
When this option is selected, this line of words and a star will appear in the upper left corner of the screen to remind students that the camera is only visible to the host and co-host. 

Camera function (Teacher Interface)
The option added to the pull-up menu when the teacher opens the camera is "Show host and co-host can see", after which is selected, a prompt will appear in the upper left corner 
of the students’ camera screen, telling the teacher that the student's camera is only visible to the host and co-host.

Video Sharing Function
In this function, Youtube Live’s and Zoom’s layout are used to simulate the online lessons, you can jump to previous content by progress bar and back to Live mode by drag the 
progress bar to the far right or just click "Live" button.

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


# LivePad
This is a real-time whiteboard web application, where users can make and share note. Also someone lese with the same link to the web-app can view and edit the whiteboard collaboratively. Basically a, JavaScript code for a canvas-based drawing application that supports undo/redo functionality and real-time collaboration using WebSockets. The code initializes the canvas, sets up event listeners for mouse interactions with the canvas, and sets up event listeners for various UI controls such as color and width selectors, eraser tool, undo/redo buttons, and download button.

The canvas event listeners handle mouse events to track the user's drawing actions and send them to the server using WebSockets. The server broadcasts the received drawing actions to all connected clients, which then execute the actions on their own canvas. The undo/redo buttons allow the user to undo or redo drawing actions, with the current state of the canvas being stored in an array of image URLs. The undoRedoCanvas() function takes care of undoing or redoing the canvas based on the current index in the array.

Overall, this code provides a basic framework for a collaborative drawing application, but it would need to be integrated with a server-side component to handle the WebSocket connections and broadcasting of drawing actions to all connected clients.

# Authors

 [@bipsblip](https://github.com/bipsblip)


# Deployment

To deploy this project run,simply go on link below
(https://livepad.onrender.com/)



# Features

- Real-time web application
- Writing
- Erasing
- Highlighting
- Downloading the OpenBoard notes
- Upload notes/picures
- Make sticky notes (draggable anywhere on screen)
- Redo Actions
- Undo Actions


# Uses

Some uses of this project:

- Group discussions
- Collaborative planning
- Teaching
- Meetings
- Making notes


# Hi, I'm bipsblip! 👋

## 🚀 About Me
I'm a front-end web developer, with impressive problem-solving skills, tech knowledge, and hustling energy.

## 🛠 Skills used in project
Javascript, HTML, CSS, Socket.IO, Oops and Data structure.

## 🔗 Connect With ME!
[![Github](https://img.shields.io/badge/github-000?style=for-the-badge&logo=github&logoColor=)](https://github.com/bipsblip)
[![GMAIL](https://img.shields.io/badge/Gmail-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pratyushchand.work@gmail.com)

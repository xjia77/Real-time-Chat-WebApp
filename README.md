## React + Node.js +  MongoDB Real-time chat WebApp for teachers and students

> React16，React-Router4，Redux，Node.js，MongoDB，Antd-Mobile

The project is divided into four modules: user list, message list, personal center, login and registration; the backend is Node.js, the database is MongoDB, with the front-end react technology stack to achieve front-end and back-end intermodulation. Users are divided into two roles: student and teacher. User registration can choose the role, after successful registration need to improve the information (students: avatar, grade, personal profile; teachers: avatar, teaching subjects, personal profile). After perfecting the information, students will jump to the student list page and teachers will jump to the teacher list page. And you can click on each other to chat with them. If there are unread messages, the number of unread messages is displayed on the message list in the bottom navigation. Clicking on an unread message reduces the number of unread messages accordingly. Focus on the use of Redux to store user information, user list information, chat information, and the number of unread messages. Implementing axios asynchronous requests using thunk middleware and Socket.io for real time communication between two user roles.


## Function
* User registration login, logout login
* Improve user information after registration is completed
* Jump to the corresponding page according to different roles
* User chat function

## Description
> enter recruiment_font_end

``` bash
# Installing Dependencies
npm install

# Launch Project
npm run dev

# Package Release
npm run build

```
> enter server

``` bash
# Installing Dependencies

npm install

# enter bin
node www

```

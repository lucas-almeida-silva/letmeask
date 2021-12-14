<p align="center">
   <img src=".github/logo.jpg" alt="Letmeask" />
</p>

# :page_with_curl: Table of Contents

* [About](#information_source-about)
* [Technologies](#computer-technologies)
* [Requirements](#page_with_curl-requirements)
* [Features](#rocket-features)
* [Images](#camera-images)
* [Settings](#gear-settings)
* [How to run](#seedling-how-to-run)
* [License](#pencil-license)

# :information_source: About

Letmeask is a web application whose objective is to help people who do lives to answer questions during the transmission. 

During the lives where there is a space for doubts, many questions arise at the same time and it is difficult to select them to answer.
Letmeask allows people to send their doubts and vote for the ones they think are most interesting and thus, whoever is making the live 
can answer questions that have the greatest interest of the public, according to the amout of votes.

Questions appear in real time as they are submitted and are sorted by the amount of votes.

# :computer: Technologies

- [ReactJS](https://pt-br.reactjs.org/)
- [Typescript](https://www.typescriptlang.org/)
- [Firebase](https://firebase.google.com/)

# :page_with_curl: Requirements

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/) (optional)
- [Git](https://git-scm.com/) (to clone the repository)

# :rocket: Features

### Users

- Login with Google
- Create rooms
- Enter a room
- Submit questions
- Vote on questions

### Admin

The admin is the one who created the room.

- Highlight question currently being answered
- Mark question as answered
- Delete questions
- Close room (Admin)

# :camera: Images

 <img src=".github/home.jpg" alt="Home" width="900" />
 <img src=".github/room.jpg" alt="Room" width="900" style="margin-top: 10px" />
 <img src=".github/admin-room.jpg" alt="Level up" width="900" style="margin-top: 10px" />
 
# :gear: Settings

You need to create a project in [Firebase](https://firebase.google.com/) and get the settings available, like this:

```javascript
const firebaseConfig = {
  apiKey: "AIzaSyACUoPtK8y8kx04MjOAWhkP8E6IPtUt7QU",
  authDomain: "projeto-em-firebase-2117b.firebaseapp.com",
  databaseURL: "https://projeto-em-firebase-2117b.firebaseio.com",
  projectId: "projeto-em-firebase-2117b",
  storageBucket: "projeto-em-firebase-2117b.appspot.com",
  messagingSenderId: "116722308966",
  appId: "1:116722308966:web:f097cbab9bd1db0dbc5aa7"
};
```

**Obs**: You can access this at any time in the project settings.

After getting this information, create a file called .env at the root of the project, copy and paste the contents of the 
.env.example file and fill each of the variables with the data obtained in the project settings.

# :seedling: How to run

```bash
# Clone the repository
$ git clone https://github.com/lucas-almeida-silva/letmeask.git

# Go to the project folder
$ cd letmeask

# Install Dependencies
$ yarn
# or npm install

# Run the application
$ yarn start
# or npm run start
```
Access the application at http://localhost:3000

# :pencil: License

This project is under the [MIT license](LICENSE).

<h1 align="center"> CLOUD NOTE :- 🎵 💭📝</h1>
<div align="center" >
<img height="300" wedith="300" src="https://th.bing.com/th/id/R.b0eddfe80e9e3db6f842a3c90cbada82?rik=8MzxI7C3umRtoQ&riu=http%3a%2f%2fclipart-library.com%2fimages%2fATbrBKa5c.gif&ehk=Mb6Kygtf00vArUjGJIyMOZALv30u6ouvAwQGk%2fbvpWY%3d&risl=&pid=ImgRaw&r=0"></div>

- Cloud Note is a web-based application that allows users to create, manage, and organize notes in the cloud.
- With Cloud Note, users can access their notes from anywhere with an internet connection and never have to worry about losing their notes again.
- Cloud note pad 🗒️ make html CSS and JavaScript.
- Cloud Note App Created.
<div align="center" >
<img height="300" wedith="300" src="https://th.bing.com/th/id/R.704701eeb4876929d15bd870beeab85d?rik=%2f72MF5X6AOQgUg&riu=http%3a%2f%2fbestanimations.com%2fBooks%2fwriting%2fwriting-notes-book-old-feather-animated-gif.gif&ehk=FGzvqqhpuKUAnQd62Nn2meo3wvcHN%2fPY2A%2fQ5wAHLRo%3d&risl=&pid=ImgRaw&r=0"></div>
<hr>
<h1 align="center">Features:-🧩</h1>

- Create notes with a title and body.
- Edit and delete existing notes.
- Organize notes into categories.
- Search for notes by title or category.
- Share notes with other users.
<hr>
<h1 align="center">Technologies Used👩‍💻</h1>

- HTML5
- CSS
- JavaScript
- jQuery
- React
- Node.js
- Express
- MongoDB
- Firebase Realtime Database
- JWT for authentication
- AWS S3 for storing note attachments
- Heroku for deployment
<hr>
<h1 align="center">Deployment:-💻</h1>

To deploy this application to a web server, follow these steps:

- Create a Firebase account and create a new project.
- Enable the Firebase Realtime Database for your project.
- Add the Firebase SDK to your project: 
<script src="https://www.gstatic.com/firebasejs/8.6.2/firebase-app.js"><br>
</script><script src="https://www.gstatic.com/firebasejs/8.6.2/firebase-database.js"></script>
<p  align=" center" >Initialize Firebase in your JavaScript code:
<br>
<h3 align=" center" >Copy code:✏️</h3>
const firebaseConfig = {<br>
  apiKey: "your-api-key",<br>
  authDomain: "your-auth-domain",<br>
  databaseURL: "your-database-url",<br>
  projectId: "your-project-id",<br><br
  storageBucket: "your-storage-bucket",<br>
  messagingSenderId: "your-messaging-sender-id",<br>
  appId: "your-app-id"<br>
};<br>
firebase.initializeApp(firebaseConfig);</p>

- Deploy your files to a web server.
<hr>
<h1 align="center">Getting Started▶️</h1>

<p  align=" center" >To run this application on your local machine, follow these steps:</p>
<h3 align=" center" >local machine:📺 </h3>
<h3 align=" center" >Clone the repository:</h3>
<p  align=" center" >git clone :📝<br>  git clone https://github.com/your-username/cloud-note.git</p>
  


- Install dependencies: npm install
- Start the server: npm start
- Open your browser and go to http://localhost:3000
<hr>
<h1 align="center">Deployment:🧾</h1>

To deploy this application to Heroku, follow these steps:

- Create a Heroku account and install the Heroku CLI.
- Create a new Heroku app: heroku create
- Deploy the code to Heroku: git push heroku master
- Provision a MongoDB database: heroku addons:create mongolab
- Set environment variables:
heroku config:
set MONGODB_URI=your-mongodb-uri JWT_SECRET=your-jwt-secret AWS_ACCESS_KEY_ID=your-aws-access-key-id AWS_SECRET_ACCESS_KEY=your-aws-secret-access-key AWS_REGION=your-aws-region AWS_BUCKET_NAME=your-aws-bucket-name
- Restart the app: heroku restart
<hr>
<h1 align="center">Contributing👬</h1>

- If you would like to contribute to this project, please open a pull request with your changes. Before submitting a pull request, please make sure your changes pass the tests and follow the code style guidelines.
<hr>
<h1 align="center">License:-📙</h1>

- This project is licensed under the MIT License - see the LICENSE.md file for details.
<hr>









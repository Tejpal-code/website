 <!DOCTYPE html>

<html>

  <head>

    <title>Contact Us - My Business</title>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="style.css">

  </head>

  <body>

    <header>

      <nav>

        <ul>

          <li><a href="#">Home</a></li>

          <li><a href="#">About Us</a></li>

          <li><a href="#">Services</a></li>

          <li><a href="#">Testimonials</a></li>

          <li><a href="#">Contact Us</a></li>

        </ul>

      </nav>

    </header>



    <main>

      <div class="contact-us">

        <h2>Contact Us</h2>

        <p>Fill out the form below to send us an email and we'll get back to you as soon as possible.</p>

        <form>

          <label for="name">Name</label>

          <input type="text" id="name" name="name" required>



          <label for="email">Email Address</label>

          <input type="email" id="email" name="email" required>



          <label for="subject">Subject</label>

          <input type="text" id="subject" name="subject" required>



          <label for="message">Message</label>

          <textarea id="message" name="message" required></textarea>



          <button type="submit">Send Message</button>

        </form>

      </div>

    </main>



    <footer>

      <p>&copy; My Business 2023. All Rights Reserved.</p>

    </footer>



    <script src="script.js"></script>

  </body>

</html>


April 28, 2023
ASSIGNMENT
Html code

 <!DOCTYPE html>

<html>

  <head>

    <title>Contact Us - My Business</title>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="style.css">

  </head>

  <body>

    <header>

      <nav>

        <ul>

          <li><a href="#">Home</a></li>

          <li><a href="#">About Us</a></li>

          <li><a href="#">Services</a></li>

          <li><a href="#">Testimonials</a></li>

          <li><a href="#">Contact Us</a></li>

        </ul>

      </nav>

    </header>



    <main>

      <div class="contact-us">

        <h2>Contact Us</h2>

        <p>Fill out the form below to send us an email and we'll get back to you as soon as possible.</p>

        <form>

          <label for="name">Name</label>

          <input type="text" id="name" name="name" required>



          <label for="email">Email Address</label>

          <input type="email" id="email" name="email" required>



          <label for="subject">Subject</label>

          <input type="text" id="subject" name="subject" required>



          <label for="message">Message</label>

          <textarea id="message" name="message" required></textarea>



          <button type="submit">Send Message</button>

        </form>

      </div>

    </main>



    <footer>

      <p>&copy; My Business 2023. All Rights Reserved.</p>

    </footer>



    <script src="script.js"></script>

  </body>

</html>

Css code 

* {

  box-sizing: border-box;

  margin: 0;

  padding: 0;

}



body {

  font-family: Arial, sans-serif;

  font-size: 16px;

  line-height: 1.5;

}



header {

  background-color: #333;

  color: #fff;

  padding: 10px;

}



nav ul {

  list-style: none;

  margin: 0;

  padding: 0;

}



nav li {

  display: inline-block;

  margin-right: 20px;

}



nav a {

  color: #fff;

  text-decoration: none;

}



main {

  padding: 20px;

  max-width: 800px;

  margin: 0 auto;

}



.contact-us {

  background-color: #f7f7f7;

  padding: 20px;

  border-radius: 5px;

  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);

}



.contact-us h2 {

  font-size: 24px;

  margin-bottom: 10px;

}



.contact-us p {

  margin-bottom: 20px;

}



.contact-us form {

  display: flex;

  flex-direction: column;

}



.contact-us label {

  margin-bottom: 5px;

}



.contact-us input,

.contact-us textarea {

  padding: 10px;

  margin-bottom: 10px;

  border: 1px solid #ccc;

  border-radius: 5px;

}



.contact-us button[type="submit"] {

  background-color: #333;

  color: #fff;

  border: none;

  padding: 10px;

  border-radius: 5px;

  cursor: pointer;

}



.contact-us button[type="submit"]:hover {

  background-color: #555;

}



footer {

  background-color: #333;

  color: #fff;

  padding: 10px;

  text-align: center;

}

Javascript code 

const form = document.querySelector('form');



form.addEventListener('submit', (e) => {

  const nameInput = document.getElementById('name');

  const emailInput = document.getElementById('email');

  const subjectInput = document.getElementById('subject');

  const messageInput = document.getElementById('message');



  if (!nameInput.value || !emailInput.value || !subjectInput.value || !messageInput.value) {

    e.preventDefault();

    alert('Please fill out all fields before submitting the form.');

  }

});

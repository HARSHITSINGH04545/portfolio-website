# portfolio-website
A51
#HTML CODE AND JS CODE HERE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
    
</head>
<body>
    <header>
        <nav>
            <div class="namee-conatinr">
        <img  class="hlogo"src="./IMAGES/hlogo-removebg-preview.png" alt="">
        <h1 class="faded-text">arshit Singh</h1>
    </div>
    <div class="right-section">
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a> </div>
        </nav>
    </header>

    <div class="container-1" id="about">
        <h2>About Me</h2>
        <div class="container" id="about">
    
            <p>
                <br>
                I'm a passionate coder and an enthusiastic explorer. Coding is not just a hobby for me; it's a way of life, a creative outlet that allows me to bring my ideas to life.
        <br><br>
              <div class="color-para">
                 Whether I'm building a web application, solving a complex algorithmic challenge, or experimenting with new programming languages, I find joy in the process of creation and problem-solving. Coding, to me, is a continuous journey of learning and self-improvement.</div>
        
        <br>
                I believe that in the ever-evolving tech world, there's always something new to discover, and I'm excited to be a part of this incredible journey. Let's explore, innovate, and create together!
            </p>
        </div>
        
    </div>

    <div class="container-2" id="projects">
        <h2>My Projects</h2>
        <div class="project-1">
            <h3 class="heading-1">Project 1</h3>
            <img src="./PROOJ 1.webp" alt="Project 1">
           
        </div>
        <br>
        <div class="project-2">
            <h3 class="heading-2">Project 2</h3>
            <!-- <br> -->
            <img src="./PROJ 2.webp" alt="Project 2">
            
        </div>
    </div>

    <div class="container-3" id="contact">
        <div class="container-contact" id="contact">
            <h2 class="color-para center">Contact Me</h2>
            <form id="contact-form" class="contact-form">
                <label for="name" class="color-para">Name:</label>
                <input type="text" id="name" name="name" required>
                <br>
                <label for="email"  class="color-para">Email:</label>
                <input type="email" action="email"id="email" name="email" required>
                <br>
                <button type="button" id="submit-button">Submit</button>
            </form>
        </div>
        
        
    </div>

    <footer>
        &copy; 2023 Harshit Singh  
        <!-- all these below are svg file  -->
        <svg id="size"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><!--! Font Awesome Pro 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M100.28 448H7.4V148.9h92.88zM53.79 108.1C24.09 108.1 0 83.5 0 53.8a53.79 53.79 0 0 1 107.58 0c0 29.7-24.1 54.3-53.79 54.3zM447.9 448h-92.68V302.4c0-34.7-.7-79.2-48.29-79.2-48.29 0-55.69 37.7-55.69 76.7V448h-92.78V148.9h89.08v40.8h1.3c12.4-23.5 42.69-48.3 87.88-48.3 94 0 111.28 61.9 111.28 142.3V448z"/></svg>
        <svg id="size" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><!--! Font Awesome Pro 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z"/></svg>
        <svg id="size" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><!--! Font Awesome Pro 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z"/></svg>
    </footer>
    <script>
        document.addEventListener("DOMContentLoaded", function () {
            const form = document.getElementById("contact-form");
            const submitButton = document.getElementById("submit-button");
    
            submitButton.addEventListener("click", function () {
                const name = document.getElementById("name").value;
                const email = document.getElementById("email").value;
    
                // Create a data object with the form values
                const formData = {
                    name: name,
                    email: email,
                };
    
                // Convert the data to a JSON string
                const formDataJSON = JSON.stringify(formData);
    
                // Send the data to the server to save it in a text file
                saveDataToFile(formDataJSON);
            });
    
            function saveDataToFile(data) {
                // You would typically send the data to a server to save it to a file.
                // Here, I'm simulating it by creating a Blob and triggering a file download.
    
                const blob = new Blob([data], { type: "application/json" });
                const a = document.createElement("a");
                a.href = URL.createObjectURL(blob);
                a.download = "contact_data.json";
                a.style.display = "none";
                document.body.appendChild(a);
                a.click();
                document.body.removeChild(a);
            }
        });
    </script>
    
</body>
</html>




#CSS CODE HERE:
@import url('https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@300&display=swap');
*{
    margin: 0;
    padding: 0;
    font-family: 'Be Vietnam Pro', sans-serif;
}
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
}
.hlogo{
    width: 80px;
    justify-content: center;
    align-items: center;
    position: absolute;
left: 41.2%;
}
.faded-text{
    margin: 1.88rem 0;
    position: relative;
    right: -3%;
}
.namee-conatinr{
display: flex;
justify-content: center;
align-items: center;
}

header {
    background-color: white;
    color: black;
    text-align: center;
    padding: 20px;
}

h1 {
    font-size: 2rem;
}

nav {
    text-align: center;
    margin-top: 20px;
}

nav a {
    text-decoration: none;
    color: #333;
    /* padding: 10px 20px; */
    /* border: 2px solid #333; */
    margin: 1rem;
    /* border-radius: 5px; */
    background-color: #fff;
    font-size: 1.5rem;
}

nav a:hover {
    /* background-color:	#fa794a; */
    color:#f16937;
}
.right-section:hover{
    transform: scale(1.2);
    cursor: pointer;
    transition: all  linear .8s;

}

.container-1 {
    padding: 2.5rem;
}
.color-para{
    color: #f16937;
}

.project {
    background-color: #fff;
    padding: 20px;
    margin: 10px;
    border-radius: 5px;
}

.project img {
    max-width: 100%;
}

.contact{
    display: flex;
    justify-content: center;

}

    .contact-form {
        width: 70%;
        margin: 0 auto;
        text-align: center;
        padding: 20px;
        background-color: #f5f5f5;
        border: 1px solid #ccc;
        border-radius: 5px;
    }

    .contact-form label {
        display: block;
        margin: 10px 10px;
        font-weight: bold;
    }

    .contact-form input {
        width: 100%;
        padding: 10px;
        margin: 5px 0;
        border: 1px solid #ccc;
        border-radius: 3px;
    }

    .contact-form button {
        background-color: #333;
        color: #fff;
        padding: 10px 20px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
    }

    .contact-form button:hover {
        background-color: #f16937;
    }
.center{
    display: flex;
    justify-content: center;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
}
#size{
    width: 23px;
    position:relative;
    /* right: 0px;
  margin: 4px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;*/
} 
#size:hover{
    cursor: pointer;
}
.project-1{
    width: 90%;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    left: 10%;
}
.project-2{
    width: 90%;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    right: 10%;
}

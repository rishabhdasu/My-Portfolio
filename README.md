<!DOCTYPE html>
<html lang="en">
<head><title>My Portfolio</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" type="text/css" href="myportfolio.css">

<link
  rel="stylesheet"
  href="https://use.fontawesome.com/releases/v5.8.2/css/all.css"
  integrity="sha384-oS3vJWv+0UjzBfQzYUhtDYW+Pj2yciDJxpsK1OYPAYjqT085Qq/1cq5FLXAZQ7Ay"
  crossorigin="anonymous"
/>
</head>
<body>
  <a name="top"></a>

     
  
        <nav id="navbar" class="nav">
          <ul class="nav-list">
            <li>
              <a href="#welcome-section">About</a>
            </li>
            <li>
              <a href="#projects">Work</a>
            </li>
            <li>
              <a href="#contact">Contact</a>
            </li>
          </ul>
          
        </nav>
    
        <section id="welcome-section" class="welcome-section">
        <div id="h1"><h1>HELLO</h1>
       <h1>I AM</h1> 
        <h1>RISHABH</h1>
      </div>
      <div id="p">
        <p>a self-taught web developer and designer</p>
      </div>  
    



        <span class="change-icon">
          <a href="#projects">
          <i class="fas fa-arrow-circle-right"></i>
          <i class="fas fa-arrow-circle-down"></i>
        </a>
        </span>

      </section>
      <a name="projects"></a>
      <section id="projects" class="projects-section">
        
        <h2 class="projects-section-header">These are some of my projects</h2>

        <div class="projects-grid">
            <a id="tribute"
              href="https://codepen.io/freeCodeCamp/full/zNqgVx"
              target="_blank"
              class="project project-tile"
            >
              <img
                class="project-image"
                src="https://user-images.githubusercontent.com/34376071/82066328-e19f8e80-96ec-11ea-86aa-bf4aa9ce21f6.jpg"
                alt="project"
              />
      
              <p class="project-title">
              
              Tribute Page
               
              </p>
            </a>

            <a id="survey"
            href="https://codepen.io/freeCodeCamp/full/zNqgVx"
            target="_blank"
            class="project project-tile"
          >
            <img
              class="project-image"
              src="https://user-images.githubusercontent.com/34376071/82065181-67bad580-96eb-11ea-9829-584936fb053d.jpg"
              alt="project"
            />
    
            <p class="project-title">
             
              Survey Form:FreeCodeCamp
              
            </p>
          </a>

          <a id="product"
          href="https://codepen.io/freeCodeCamp/full/zNqgVx"
          target="_blank"
          class="project project-tile"
        >
          <img
            class="project-image"
            src="https://user-images.githubusercontent.com/34376071/82066306-db111700-96ec-11ea-974f-e6862f3b66c3.jpg"
            alt="project"
          />
          
          <p class="project-title">
        Product Landing Page
           
          </p>
        </a>
        <a id="technical"
    href="https://codepen.io/freeCodeCamp/full/zNqgVx"
    target="_blank"
    class="project project-tile"
  >
    <img
      class="project-image"
      src="https://user-images.githubusercontent.com/34376071/82150920-674f4580-9877-11ea-9060-2873921eeac5.jpg"
      alt="project"
    />

    <p class="project-title">
      
      Technical Documentation Page
     
    </p>
  </a>

</div>
      </section>

<section id="contact" class="contact-section">
  <div class="contact-section-header">
    <h2>Let's get in touch...</h2>
    
  </div>
  <div class="contact-links">
    <a
      href="https://codepen.io/rishabhcodes"
      target="_blank"
      class="btn contact-details"
      ><i class="fab fa-codepen"></i> CodePen</a
    >
    <a
      id="profile-link"
      href="https://github.com/rishabhdasu"
      target="_blank"
      class="btn contact-details"
      ><i class="fab fa-github"></i> GitHub</a
    >
    <a
      href="https://twitter.com/rishabhdasgupta"
      target="_blank"
      class="btn contact-details"
      ><i class="fab fa-twitter"></i> Twitter</a
    >
    <a href="mailto:rishabhdasu@gmail.com" class="btn contact-details"
      ><i class="fas fa-at"></i> Send a mail</a
    >
    
  </div>
</section>


<footer>
  <p>
    **This portfolio is made for a freecodecamp project.
  </p>
  <p>
    &copy; Rishabh Dasgupta 2020
    </a>
  </p>
</footer>
</body>




</html>

  * {
  margin: 0;
  padding: 0;
  
}

*,
*::before,
*::after {
  box-sizing: inherit;
}

html {
  box-sizing: border-box;
  font-size: 62.5%;
  scroll-behavior: smooth;
  
}

@media (max-width: 61.25em) {
  html {
    font-size: 58%;
  }
}

@media (max-width: 28.75em) {
  html {
    font-size: 55%;
  }
}

body {
  font-family: 'Poppins', sans-serif;
  font-size: 2rem; 
  font-weight: 400;
  line-height: 1.4;
  width: 100% auto;
  
 
}

.nav {
  display: flex;
  justify-content: flex-end;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background:#a11212		;
  z-index: 10;
} 
@media (max-width: 28.75em) {
  .nav {
    justify-content: center;
  }

  .nav-list {
    margin: 0 1rem;
  }
}
.nav-list

  {
      display: flex;
      margin-right: 2rem;
     
  }
  ul
  {
      list-style: none;
  }
  a
  {
      text-decoration: none;
      color: white;

  }

  .nav-list a {
    display: block;
    font-size: 2.2rem;
    padding: 2rem;
  }

  .welcome-section {
    display: flex;
    position: relative;
    flex-direction: row;
    justify-content: center;
    width: 100%;
    height: 100vh;
    color: white;
    background-color:#181818;  
  }

  .welcome-section > #h1 {
    font-size: 80px;
    font-weight: 300;
    line-height: 10rem;
    margin-top: 10vw;
    
   
  }

  .welcome-section > #p {
    font-size: 50px;
    font-weight: 200;
    font-style: italic;
    color: red;
    text-align: center;
    float: right;
    margin-top: 15vw;
    
    }
    
  .change-icon
{
position: absolute;
bottom: 3vw;

}
.change-icon a > .fas 
{
  font-size: 2em;
}

.change-icon a > .fas + .fas,
.change-icon:hover a > .fas {
  display: none;
  
}
.change-icon:hover a > .fas + .fas {
  display: inherit;
 
}



  .projects-section {
    text-align: center;
    padding: 10rem 2rem;
    background:#181818;
    position: relative;
    
  }
  
  .projects-section-header {
      color: white;
    max-width: 640px;
    margin: 0 auto 6rem auto;
    border-bottom: 0.2rem solid white;
    padding:1vw;
  }  
  @media (max-width: 28.75em) {
    .projects-section-header {
      font-size: 4rem;
    }
  }
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  grid-gap: 1rem;
    margin-left: 5vw;
    width: 100%;
    max-width: 1280px;
   justify-content: center;
   align-items: center;
    margin-bottom: 1rem;
    
  }
  @media (max-width: 30.625em) {
    .projects-section {
      padding: 6rem 1rem;
    }
  
    .projects-grid {
      grid-template-columns: 1fr;
    }
  }

  .project {
    background: #202020;
    border-radius: 4px;
    height: 290px;
    width: 350px;
    justify-content: center;
    align-items: center;
    transition: transform .5s ease;
  }
  
  .project-title {
    color: #202020;
    font-size: 1.8rem;
    font-weight: 300;
    color: white;
    text-align: center;
    
  }
  
  .project:hover .code {
    color: white;
  }

  .project-image {
    height: calc(100% - 4.8rem);
    width: 100%;
    object-fit: cover;
    
  }
  
  .project:hover
  {
    transform: translateY(-10px);
    
  }

  .contact-section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    width: 100%;
    height: 80vh;
    padding: 0 2rem;
    background: #101010;
  }
  
  .contact-section-header > h2 {
    font-size: 5rem;
    color: white;
  }
  
  @media (max-width: 28.75em) {
    .contact-section-header > h2 {
      font-size: 4rem;
    }
  }
  
  .contact-section-header > p {
    font-style: italic;
  }
  
  .contact-links {
    display: flex;
    justify-content: center;
    width: 100%;
    max-width: 980px;
    margin-top: 4rem;
    flex-wrap: wrap;
  }
  
  .contact-details {
    font-size: 2.4rem;
    text-shadow: 2px 2px 1px #1f1f1f;
    transition: transform 0.3s ease-out;
  }
  
  .contact-details:hover {
    transform: translateY(-8px);
    
  }

  
  
 .btn {
  display: inline-block;
  padding: 1rem 2rem;
  border-radius: 2px;
}

footer {
  font-weight: 300;
  display: flex;
  justify-content: space-evenly;
  padding: 1rem;
  background: black;
  color: white;
  width: 100%;
  bottom: 0;
  left: 0;
  position: relative;
  border-top: 1px solid  #202020;
}

footer > p {
  margin: 2rem;
}


@media (max-width: 28.75em) {
  footer {
    flex-direction: column;
    text-align: center;
  }
}
 

  





  
  

  
  

  
  
  
  




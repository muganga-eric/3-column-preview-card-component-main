# Frontend Mentor - 3-column preview card component solution

This is where you can view the product from my own coding. this challenge is from frontend meontor platform that provide diffrent frontend challengs [3-column preview card component challenge on Frontend Mentor](https://3-columns-preview-carde.netlify.app/). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
![this shows my developed page](../frontend_memntor/3-column-preview-card-component-main/screenshot/Capture.PNG)

### Links

- Solution URL: [the link to get you on ](https://3-columns-preview-carde.netlify.app/)
## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
### sinippets below
To see how you can add code snippets, see below:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="style/style.css" />
  <title>Car Categories</title>
</head>
<body>
  <div class="card-container">
    <div class="card sedan">
      <img src="images/icon-sedans.svg" alt="Sedan Icon" />
      <h2>SEDANS</h2>
      <p>
        Choose a sedan for its affordability and excellent fuel economy. Ideal
        for cruising in the city or on your next road trip.
      </p>
      <a href="#">Learn More</a>
    </div>

    <div class="card suv">
      <img src="images/icon-suvs.svg" alt="SUV Icon" />
      <h2>SUVS</h2>
      <p>
        Take an SUV for its spacious interior, power, and versatility. Perfect
        for your next family vacation and off-road adventures.
      </p>
      <a href="#">Learn More</a>
    </div>

    <div class="card luxury">
      <img src="images/icon-luxury.svg" alt="Luxury Icon" />
      <h2>LUXURY</h2>
      <p>
        Cruise in the best car brands without the bloated prices. Enjoy the
        enhanced comfort of a luxury rental and arrive in style.
      </p>
      <a href="#">Learn More</a>
    </div>
  </div>
</body>
</html>

```
```css
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: hsl(0, 0%, 95%);
    padding: 20px;
    display: flex;
    justify-content: center;
    margin-top: 17vh;
  }
  
  .card-container {
    display: flex;
    flex-direction: column;
    width: 100%;
    max-width: 375px;
    border-radius: 10px;
    overflow: hidden;
  }
  
  .card {
    padding: 30px 25px;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  
  .card img {
    width: 50px;
    margin-bottom: 20px;
  }
  
  .card h2 {
    font-size: 1.5rem;
    letter-spacing: 1px;
    margin-bottom: 15px;
    font-weight: bold;
  }
  
  .card p {
    font-size: 0.9rem;
    line-height: 1.6;
    margin-bottom: 25px;
    opacity: 0.9;
  }
  
  .card a {
    background-color: white;
    color: inherit;
    text-decoration: none;
    padding: 12px 25px;
    border-radius: 25px;
    width: fit-content;
    font-weight: bold;
    font-size: 0.9rem;
    transition: background 0.3s;
  }
  
  .card a:hover {
    background-color: rgba(255, 255, 255, 0.85);
  }
  
  .sedan {
    background-color: hsl(31, 77%, 52%);
  }
  .sedan a{
    color: orange;
  }
  
  .suv {
    background-color: hsl(184, 100%, 22%);
  }

  .suv a{
    color: hsl(184, 100%, 22%);
  }

  .luxury {
    background-color: hsl(179, 100%, 13%);
  }
  .luxury a{
    color: hsl(179, 100%, 13%);
  }
  
  @media (min-width: 768px) {
    .card-container {
      flex-direction: row;
      max-width: 1000px;
    }
  
    .card {
      flex: 1;
    }
  
    .card a {
      margin-top: auto;
    }
  }
  
```
### Continued development
putting my container in center on Y-axis

### Useful resources

- git repository to describe and to show more detail about flex box(https://github.com/samanthaming/Flexbox30)
- google font to get diffrent font tobe used (https://fonts.google.com/)

## Author
- Website - [MUGANGA Eric] (https://3-columns-preview-carde.netlify.app/)
- Frontend Mentor - [@Muganga-eric](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@Muganga Eric](https://www.twitter.com/yourusername)

## Acknowledgments

every project have it's own complext so if you start without any specific goal it will cont easy to finish that project. only procedure to finish such lange of project it tostart withi "NEVER GIVE UP THINKING" just to think that there is no thing thatwill couse me to stop my project
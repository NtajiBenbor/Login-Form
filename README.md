# A Responsive Login Page 

## 1. Project Description :memo:

This project involves creating a login form that accepts the user's email address and password as input. To ensure correct information input, HTML **validations**  were implemented.   

For the email input field, the `type="email"` attribute was used to only accept valid email addresses. To keep the user's password hidden, the password input field was set with the `type="password"` attribute. Additionally, a simple **regular expression** in HTML was set up to enforce password criteria - it must be 8 characters long, with lowercase alphabets (a to z), and digits from zero to nine `[a-z0-9]{8,}`. Finally, to enable form submission, both fields are mandatory, achieved through the `required` attribute.

## 2. Screenshots :camera_flash:

![gif of project](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbTE0Z3AwOXdyZm8wNzR3bGFkNnJqZ3B0aWVraThxbzZtd25qNGx4ayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xhgkqcUlObY6ObK39H/giphy.gif)

*screenchot1*

## 3. Challenges :sweat:

- The major challenge I faced during the project was aligning the background image alongside the login form. I resolved this by nesting the form and image div elements within a parent div and applying the `display:flex` property to the parent. 

- The second issue I encountered was positioning the background image correctly to display fully on the right. To fix this, I used the following CSS properties: `background-position: center`, `background-size: cover`, and `background-repeat: no-repeat`. With these adjustments, the background image was displayed as desired. \

*the lines of code use to set the background-image*
``````CSS
#right-pane {
    width: 55vw;
    margin: none;
    background: URL(/images/pexels-phone-headphones.jpg);
    background-position: center center;
    min-width: 300px;
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
}
``````  

## 4. Tools and Resources :wrench::hammer:
 
During the course of building this project, I utilized the following tools and resources (in no particular order):

+ HTML
+ CSS
+ Flexbox
+ Color palettes from [Coolors.co](https://coolors.co) :link:
+ Images from [Pexel.com](https://pexels.com) :link:
+ [FreeCodeCamp.org](https://freeCodeCamp.org) as a guide. :link:
+ Version Control systems Git and GitHub


## 5. Purpose :arrow_right:

The project aims to test and enhance my HTML and CSS skills by building real-world projects.

## 6. Author :pen:

Hi everyone! I'm Benedict, learning web development to become a frontend developer. Check out my blog for learning experiences, projects, and tips. Follow me on Twitter too! 
kindly click on the links below. Thanks!

- Follow me on [Twitter](https://twitter.com/CodewithNtaji) :link:
- Checkout my blog on [Hashnode](https://benneythedev.hashnode.dev/) :book:








# VISUAL-GYM
Visual gym is template with HTML and CSS. 

## Components
### 1.Home
![home](https://github.com/NoorseenQandil/VISUAL-GYM/assets/70522199/069b7503-fa1a-4b39-830a-482393a5b78b)

### 2.About
![About](https://github.com/NoorseenQandil/VISUAL-GYM/assets/70522199/5739400f-4c45-4760-9c7c-cd8b3b9c68db)

### 3.Exercises
![Exercises](https://github.com/NoorseenQandil/VISUAL-GYM/assets/70522199/6ce7af67-f51c-4b96-9973-c9a178af165b)

#### - Section1: Home
  - Consists of 2 parts: The first part includes gym logo image and navbar links. The second one includes main caption that consists of logo image, caption and two buttons.
  - Use Float property and set left to its value to put the logo image in navbar on the left side.
    ```
      #home .navbar img{
       float: left;
      }
    ```
  - Use Float property and set right to value to put the navbar links on the right side.
  - Use list-style property and set none to its value to remove the list style put by default.
    ```
      #home .navbar ul{
        float: right;
        list-style: none;
     }
    ```
  - Its important to use clear with float.
  - Use text-align property and set center to its value to put the caption content in the center.
  - Use grouping to make the two buttons the same padding and border values.

#### - Section2: About
 - Consists of 2 sides: The left side includes an image. The right one includes short paragraph about us and one button.
 - Use span tag in HTML to make difference between the words in title. Then put different color for it in CSS code.
   ```
     <h2><span>Our</span>Stor</h2>
   ```
   ```
     #about .about-info h2 span{
       color: #09c;
     }
   ```

#### - Section3: Exercises
  - This section consists of six parts.
  - Each one includes one image, title and paragraph for description.
  - Put the width of each section is 33.33%.
  - Use Float property to put the four parts on the same line.
  - Use Clear property with float.
  - To make each image in circle shape, Use border-raduis property and set its value to 50%.
    ```
     #exercises .exercise {
        width: 33.3333%;
        text-align: center;
        float: left;
    }
      #exercises .exercise img{
          border-radius: 50%;
      }
    ```
  - To seperate by line between the title and description, you can make empty div tag and set width, height and backgroud-color values for it.
    ```
      #exercises .exercise .break{
      height: 3px;
      background-color: #09c;
      margin: 15px auto;
      width: 100px;
     }
    ```

## Live Demo 
Experience the Tabs Project in action! Click the link below to access the live demo:

[Live Demo] (https://noorseenqandil.github.io/VISUAL-GYM/)

Feel free to interact with the project, browse through different jobs, and explore the user-friendly interface. The live demo provides a hands-on experience to see the Tabs Project in action.

## Contributing
If you have suggestions or find issues with the template, feel free to open an issue or create a pull request. Contributions are welcome!

## Contact
If you have any questions, feedback, or suggestions, please feel free to reach out to us at NourseenQandil@gmail.com We value your input and would love to hear from you!

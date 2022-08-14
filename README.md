# Vanilla-Calender
Vanilla-Calender | HTML | CSS | Vanilla JavaScript

# Introduction

This is JavaScript's small project using HTML, CSS and Venilla JavaScript. Project is about to build an Calender and Filter the dates etc, using Vanilla JavaScript
During this project I have learned some basic of Vanilla JavaScript and much more.


# Tools 
VS Code

# Language 
- HTML
- CSS
- JavaScript -Venilla JavaScript

# Code
- HTML
````
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        // html code here ..............
    </body>
    </html>
````

- CSS
````
<style>

// style code here

</style>

````
- JavaScript 
````
<Script>
// javascript code here

</Script>
````
 Create/Declare the Month and week in .js file
````
let calendar = new VanillaCalendar({
    selector: "#newCalender",
    months: ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"],
    shortWeekday: ['Sun', 'Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat'],
    onSelect: (data, elem) => {
        console.log(data, elem)
    }
})

````
````
// vanilla javascript codes....

````






















# Refernces
- W3 School
- MDN Web Docs
- YouTube, etc.







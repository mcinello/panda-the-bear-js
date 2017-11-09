Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead.
PROTIP: use the inspector to learn the dimensions of the current profile image and use a placeholder image service such as Place Bear to get an image of the same size.

var highlight = document.querySelector('.highlight');
var highlightImg = highlight.querySelector('img');
highlightImg.src = "images/pikachu.jpeg";


Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing.

var portfolioImgClass = document.querySelector('.portfolio-image');
var portfolioImg = portfolioImgClass.querySelector('img');
portfolioImg.src = "images/water.jpeg";

Select the heading that says "Panda the Bear" and change it to your own name.

var h1 = document.querySelector('h1');
h1.innerText = "Michelle";

Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector)

var employment = document.querySelector('#employment');
var empH3 = employment.querySelector('h3');
empH3.innerText = "Experience";

Change the colour of the body.

document.body.style.backgroundColor = "#868686";

Change the colour of each element using the highlight class. Use a for loop to do this.

var list = document.querySelectorAll(".highlight");
list.forEach(function(item) { item.style.color = "#ADD8E6";})

Change the font family of the h1 to 'monospace'.
h1.style.fontFamily = "monospace";

Find a way to select the round icons in the sidebar and then change their colour.

var icon = document.querySelectorAll('.action-icon-bg');
icon.forEach(function(icon){ icon.style.backgroundColor = "black";})

Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself".

Change the placeholder attribute of the message field to "state your business".

Give the name field a "value" attribute of "your nemesis".

Change the value attribute of the email field to "koalathebear@gmail.com".

Change the value of the submit button on the contact form to "En garde!".

We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button (hint: familiarize yourself with the disabled attribute).

We should help Panda protect their privacy by erasing their personal details from the sidebar.

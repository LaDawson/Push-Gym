Push


My project is a website for a gym called "Push". This website was made with the intent to promote and increase the 
number of people that are signed up for the gym. I designed it with the idea of having a simple layout as sometimes
too much information can cause a bad user experience. The simple design is fluent throughout the website in order to 
keep the website organised.

Whilst keeping the website relatively simple, I believe that it provides all of the information that is needed for
the user to understand what the website is for and get an idea of what the gym offers. I feel the website is easy to navigate
with its scrolling feature and the information is laid out in a neat fashion.


As a user I would like a website where I could easily find the information needed however not be overwhelmed with too much unnecessary information.
As a user I would like to be able to easily contact the owners if I had any queeries so I can find out more about the product/service.
As a user I would expect the website to be bug free and run smoothly so I have a positive user experience and am likely to return to the website.

I believe my website addresses the above user experiences.



Features:



My website contains two background images that are out of the normal flow of the website to highlight that the website is for a gym, and that when
the page is moved up or down the images will stay still to make the page look more alive.

There is a navigation bar located in the top right corner hidden behind a dropdown button in order to offer the users a different way of 
traversing the website by having them click on the specific page they would like to view. This navigation menu is hidden off screen, in order to not have the
page cluttered, until the button is hovered over on desktop or clicked on mobile devices. The navigation links are linked to the IDs of the titles of each page.

I used a jumbotron feature from bootstrap in order to contain the main title and the sign up button in the center of the screen so that the users
can easily see the name of the gym and where they need to click to sign up to the service.

For the second page, I made cards to contain the a little bit of information about the gym. I originally created these and styled them completely in css
without realising that bootstrap offered a basic layout for cards that could have saved me a lot of time. The cards display an image and title until 
hovered over on desktop or clicked on mobile. Once this action is performed, the background image will become darkened by an overlay and text will appear
on top of the card.
The cards will change size and positioning depending on the screen size to improve the UX as if the screen size was too small then the cards would be 
difficult to read before I made this change. 

Page three contains the review boxes. For this page I made full use of Bootstrap's grid layout. I give all of the review boxes many grid classes so that
that they would adjust layout and sizing depending on the screen size. This allowed for the text to always be readable and for the page not to be over 
crowded with features. Once the screen gets below a certain screen size the number of visable reviews reduces to two so that the user does not have to scroll
through all of the reviews on a small screen. 

On page 4, the form feature allows the user to contact the company by completing the text boxes provided. I used some of the class names from Bootstrap to aid the
creation of the form, such as "form-control" to help with the sizing of the form. I also made sure to add the "required" attribute to make sure the form was filled in
and the use of the correct type to make sure the correct information was written. The form will not submit unless it is properly completed.

I also created a seperate html page which is only seen once the form is submitted so that the user has an indication that the form has been completed and the company
has received the information. On this page in a button to link back to the home page so that the forward and back buttons on the browser is not needed.



Features to implement in the future:



Once I have more knowledge of html and css there are some features I would like to add to make the website better for the user.

- The home page sign up button:
  Currently the sign up button does not work, but I would like to have a modal pop up with a form to fill in. Once completed this form would give an 
  indication whether it was a successful sign up or not, and the information would be pushed to a server.

- A sign in method:
  I would like to create a method to sign in to your account to manage account details or change/cancel your gym subscription. Also this would help to
  automatically fill in the "Contact Us" page form.

- Video for the background:
  Currently the background for the homepage is a still image, however I have seen websites use videos for a background so I think it would be great to
  implement a repeating video which shows people really pushing themselves at the gym. I feel this would make the homepage more alive and more appealing.


- Video within the cards:
  I would like to place videos within the cards on page 2 instead of the text. In these videos I think it would be great to have employees and customers 
  speak about the specific areas of the gym, this would give the gym a face to look at and is more interactive than plain text.

- Contact Form modal:
  As you complete the contact form, you are taken to a seperate page in order to have an indication that the form was complete. I would like to implement 
  a much small feature such as a pop up modal at the top of the screen to let the user know that the feedback was submitted successfully. This popup would only
  show for a small period of time as to not get in the way of the user.



Technologies used:



- Bootstrap: I used bootstrap for the basic layout of a grid and containers to help me organise the pages,
  for part of the contact form to help style the text boxes, the basic styling of buttons and for the 
  jumbotron which contains the title. After using bootstrap I then customized each element within CSS.

  https://getbootstrap.com/docs/4.3/getting-started/introduction/
  
- Font Awesome: This was used to help with the styling of the nav buttons.

  https://fontawesome.com/icons?d=gallery
  
- Google Fonts: This was used to get the fonts for the entire website.

  https://fonts.google.com/
  
- Pixabay: Pixabay was where I gathered all the images that went into my website, from the background images
  to the images within the cards. All the images taken are copywrite free and do not require any credit.

  https://cdn.pixabay.com/photo/2016/11/19/12/43/barbell-1839087_1280.jpg
  https://cdn.pixabay.com/photo/2017/01/09/14/43/dumbbell-1966704_1280.jpg
  https://cdn.pixabay.com/photo/2015/04/08/23/53/workout-713658_1280.jpg
  https://pixabay.com/photos/barbell-bodybuilding-effort-1839087/
  
- W3schools: I used this website to get all the colors I would need for my css styles.

  https://www.w3schools.com/cssref/css_colors.asp
  
I also used the google developer tools feature to help me visualise my website with different screen sizes, and to
test different features and styles before actually implementing them into my code.



Testing:



In order to test the website, every time I had completed a feature such as the cards, I would go into google developer tools and test the feature repeatedly on different 
screen sizes in order to make sure they functioned exactly how I wanted them to.
I did this along side the production process as I did not want to reach the end of development only to find out I have to change certain aspects due to bugs I had overlooked.

One of the main issues I had when testing was getting the navigation menu to function as intended when it was hovered over. I had many issues, such as the sizing of the container
being wrong, the text inside the container being displaced and the hover function not working at all. To over come the issue I changed the design of the navigation menu from it 
changing z-index to it starting in an off-screen position and moving onto the screen. This change cleared up a lot of the issues I was having with the navigation menu and it made
the hover feature a lot easier to implement.

Another issue I was having was with the cards on page two. The issue was that when the page size changed the cards would not change with it and the entire page would break the orignal layout.
I could not figure out what was wrong and why the divs would not change to the position that was intended. After a bit of trial and error with the css I managed to get the divs to move to the correct
position by changing how they were displayed and the margin or the divs. However, by doing this I created another issue in which the page container would not wrap all of the content with in itself.
For this issue I contacted my mentor as I had already spent enough time trying to figure it out. My mentor explained the problem which was that I was applying a height to the container wrappers. The height
is not needed and without it the container will automatically wrap around all of the content within it. Once I had this knowledge it made the creation of the rest of the website a lot easier as I now understood
the container class a lot better.

The Navigation Menu:

1. Hover over the button in the top right corner of the webpage.
2. Click on any link that is within the menu.
3. The link will take you to the corresponding page.

The Cards on Page 2:

1. Hover over the chosen card.
2. The image should darken and text should appear.
3. Move off of the card.
4. The text should disappear and the image become visable again.
5. Change the screen width above and below 1000px and verify that the cards change position.
6. Verify that once the cards have changed position that the hover feature still works as intended.

The Contact Form:

1. Try submitting the form with no information provided and verify that an error message appears about the relevant fields.
2. Try submitting the form with only two of the boxes filled in and verify that an error message appears about the relevant fields.
3. Try submitting with only one of the boxes filled in and verify that an error message appears about the relevant fields.
4. Try submitting the form with all the boxes filled in but with an incorrect email format and verify an error message appears about the email format.
5. Try submitting a complete form with the correct format and verify it takes you to a page with a thank you message and a link to the homepage.
6. Change the screen width below 900px and verify the form bars change from 50% width to 90%.

The "Thank You" Page:

1. Click the button on the page and verify it takes you to the homepage.
2. Use the forward and back button on the browser and verify it does not cause errors.

The Reviews:

1. Go into google developer tools, change the screen size to responsive and change the width of the screen.
2. Verify that above a width of 1200px, all 4 of the reviews are displayed vertically at a column size of 8.
3. Verify that between a width of 992px and 1200px, all 4 of the reviews are displayed but 2 are at a column size of 4 and 2 are at a column size of 6. Also that the reviews are displayed horizontally in a pair.
4. Verify that between a width of 768px and 992px, all 4 of the reviews are displayed vertically with a column size of 8.
5. Verify that between a width of 576px and 768px, all 4 of the reviews are displayed vertically with a column size of 10.
6. Verify that below a width of 576px, only 2 of the reviews are displayed with a column width of 10.



Deployment:



In order to deploy my project I use GitHub. In order to push the project to GitHub I have to use the terminal.
The first step was to create a local repository. Then I had to add Github as the origin by taking my repository 
which Github provides and using it within the terminal commands. Once this link was inputted I then had to add my files
to the local repository as I created them, then push them to the repository on GitHub with a comment to label the version I 
just uploaded.

The process is:
1. git init (to create the local repository).
2. git remote add origin "the link that Github provides in the created repository"
   git push -u origin master (to push the local repository to GitHub).
3. git add "examplefile.html" (to add the local file to the repository).
4. git commit -m "example comment" (to commit the files in the repository).
5. git push (to push the files to the Github repository, you will need your username and password).

To run my code locally you can visit the website "https://github.com/LaDawson/Push-Gym" which takes you to the repository for my project.
Here you will be able to see the versions I have uploaded over time, and see the most recent version of upload.
The most recent version will be the first few files you can see, you can open these to see my code. There is also a option to
download or clone my code.

You can clone the repository to GitHub Desktop by clicking the "Open in Desktop" button after clicking the "Clone or Download" button.


If you copy the link provided when you click the clone/download button then follow these steps to run it locally:
1. Open Git Bash
2. Change the current working directory to the location where you want the cloned directory to be made.
3. Type git clone, and then paste the URL you copied.
4. Press enter and your local clone will be created.






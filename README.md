# Survey-Form-for-freeCodeCamp
Responsive Web Design Project for freeCodeCamp

## FreeCodeCamp - Survey Form

This is a solution to the [Survey Form project](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-survey-form). 

### Links

- Solution URL: [https://github.com/macdeesh/Survey-Form-for-freeCodeCamp]
- Live Site URL: []

#### What I learned
This is my first form project. I learned how to create a form with an ```id``` and ```method="post"```. Inside the form there is different ```<div>``` some of the divs ```type="text"``` for the name with a ``` <label for="name" id="name-label" class="input-title">Name</label>``` and ```<input type="text" id="name" name="user-name" placeholder="Enter your name" autocomplete="on" required>```. the ```<input>```:```id``` should have the value of the ```<label>```:```for```. The ```placeholder``` to describes the expected value of an input field, the ```autocomlete``` enable the browser to predict the value to the input field and ```required``` specifies that an input field must be filled out before submitting the form.
The ```type="email"```  to let the user enter and an e-mail address and have the same attributes. For the ```type="number"``` i used ```min="10" max="99"``` to specifie the minimum and maximum value for the <input> element, for the age in this case. 
For the the dropdown option i used ```<select>``` with a ```<label>``` before, and then i added ```<option>``` with diffrent value for the choice, but for the first option which has the role of a placeholder i write ```<option disabled selected value>Select your current role</option>``` because i can't use a placeholder inside ```<select>```. I created a list with ```<ul>``` and ```<li>``` then add ```<input type="radio" id="definitely" name="recommendation" value="definitely" checked>``` to create radio button list, ```checked``` was just for the first choice, the same thing i did to create a checkbox list with ```type="checkbox"```. To ask the user for comments i used ```<label for="comments" class="input-title">Any comments or suggestions?</label>``` and ```<textarea name="comments" rows="8" cols="55" placeholder="Enter your comment here..."></textarea>```. The rows and cols was to style the size of the text area with a ```max-widh= 100%``` in CSS. Finally to creat a subit button i did ```<button type="submit" id="submit" form="survey-form" value="Submit">Submit</button>```, and here the ```form="survey-form"``` must be the same as the id of the form.

For the styling of the form i used the ```display=flex; align-items: center; flex-direction: column;``` and for the background image i did ```background-image: url("../code-wallpaper.png"); background-size: cover; background-repeat: no-repeat; background-position: center;```.



##### Author

- Github - [Macdeesh](https://github.com/macdeesh)
- Twitter - [@Macdiish](https://twitter.com/Macdiish)

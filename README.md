




Note: This is based on FreeCodeCamp courses, make sure to join the community in and donate for all of those amazing courses. 

https://www.freecodecamp.org/

In order to put it in practice, use your own examples and make the most of it. 




#BootStrap# 

With responsive design, there is no need to design a mobile version of your website. It will look good on devices with screens of any width.

You can add Bootstrap to any app by adding the following code to the top of your HTML:

href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous"/>

# BootStrap-Examples

> BootStrap exercises for application of responsiveness 

#Adding classes


> Starting to nest all of our HTML in a `<div class="container-fluid">`

: **class="_container-fluid_"**# -  > It will make all content inside of this div responsive;

Add this class to a `<img class="img-responsive">` tag

: #**class="_img-responsive_"**# - Image with the exactly the width of our phone's screen; 

: #**class="_text-center_**"# - Centering elements on the page.

> Bootstrap has its own styles for button elements, which look much better than the plain HTML ones.

: #**_class="btn"_**#

: #**class="_btn btn-default_"**#

: #**class="_btn btn-block_"**# - This button would take up 100% of the available width.

: #**class="_btn btn-primary_"**# - The _**btn-primary**_ class it is useful for highlighting actions you want your user to take.

: #_**class="btn btn-info"**_# - Bootstrap comes with several pre-defined colors for buttons. The **_btn-info_** class is used to call attention to optional actions that the user can take.

> Bootstrap comes with several pre-defined colors for buttons. The _**btn-danger**_ class is the button color you'll use to notify users that the button performs a destructive action, such as deleting contents.

: #_**class="btn btn-danger"**_# - It gives a red color to the button 

'''

    <button class="btn btn-primary btn-block"type="button">Like</button>
    
    <button class="btn btn-block btn-info" type="button">Info</button>
    
    <button class="btn btn-block btn-danger"type="button">Delete</button>
'''

> Use the Bootstrap Grid to Put Elements Side By Side

Bootstrap uses a responsive 12-column grid system, which makes it easy to put elements into rows and specify each element's relative width. Most of Bootstrap's classes can be applied to a div element.

# Responsive-Portfolio

## Information

This repo is 1 of many possible solutions to the jan2018 coding bootcamp Cohort's Homework #2 assignment 1. This repo is provided as a means to help students that struggled with this assignment with a more heavily commented code base.

The front end takes a mobile first appoarch making it responsive for varying screen sizes. 
The instructions in the project had the students start with a viewport width of 640px this will be my static view for the front end. Static in this instance allows me to not have to write a media query at the 640px view.

So the first media query will be defined at 768px. Then we will define a media query at 980px. I'm using the min-width instead of max-width because this allows my layout to be viewable on devices 980px and larger without having to constantly declare media queries.

### Page differences according to the pictures students have

#### 640px view vs the 768px view

All page headers now have the h1 element floated to the left and the main-nav floated to the right. The container for these elements (Header) has a clearfix css class applied to it.

The about me page now has a floated profile image that has its width set to 50% from 100%.

The portfolio page now has the project images floated to the left and their width's set to 50%. This allows for the single column of project photos to become 2. The parent container of the image also get's a clearfix applied to it.

The header and content wrappers have their widths set to 80% from 90%. Allowing the body's background image to show up more.

#### 768px view vs the 980px view

The header and content wrappers have their widths set to 70% from 80%. Allowing the body's background image to show up more.

All pages now have the content floated to the left and the sidebar floated to the right. The content now has a width of 60% and the side bar now has its width set to 35%.

The floated image on the about me page gets unfloated and its width gets set back to 100%.

The projects on the portfolio page now get unfloated and have their widths set back to 100%.


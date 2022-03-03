---
layout: default
title: Prototype
nav_order: 6
---

# Prototype
{: .no_toc }

In Figma, the prototyping feature helps create flows that simulate how a user might interact with your designs. By prototyping our design, it will provide functionality, which will help communicate with your users, and help them understand your design more. 

In this section, we will prototype our To-do app. By the end of this section, you should have a complete understanding of how to prototype your design in Figma.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Task 1: Set Your Starting Page

Before we begin prototyping, let’s start by choosing which page will be your starting point. By setting a starting page, users will be directed to that particular page first before any other. For this mockup, we will set the log-in frame as our starting page.

**1.1** *right-click* on the log-in frame then choose **add starting point**.

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/01_prototype_starting_point.png?raw=true" alt="signUp_button" width="200" height="200">
</div> 
<br>

This will automatically assign the frame as the first flow.
	
> A flow is the network of frames and connections on a single page.

## Task 2: Prototype The Button to naviagte to a different page

After setting our starting page, let’s start prototyping our **components**! For this mockup, let’s prototype the log-in button so that when it is *clicked*, it will redirect us to the **User Dashboard** page. 

**2.1** Go to prototype mode by *clicking* on the right-hand panel under “**Prototype**.”
				
**2.2** Since we want to redirect to the User Dashboard page when we click the log-in button, simply drag the new circle attached to the side of the button and connect it to the User Dashboard frame.


<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/02_prototype_redirect_connection.png?raw=true" alt="signUp_button" width="300" height="300">
</div> 
<br>

<div style="background-color: #ffdfbf; padding: 14px; border-radius: 4px; color: black" >
<img align="left" width="45" height="45" src="https://cdn-icons-png.flaticon.com/128/3209/3209265.png?raw=true" alt="note-icon-png"> <strong>Note:</strong> <br>
Notice that a popup window appeared from the right panel once you created the connection. You can manually change the interaction’s details on this window.
</div>




## Task 3: State Change Design

Before we start prototyping our checkboxes, we will need to add another component that would show the changes when those checkboxes are clicked. 

Remember the plug-in we had to install called **iconify**? We will now be using them to get our component!

**3.1** *Click* on the Figma logo located at the far left of the toolbar. Then select **plugins**, and then **iconify**.

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/03_prototype_iconify.png?raw=true" alt="navigating_to_iconify" width="300" height="300">
</div> 
<br>

**3.2**  A window should pop out, on the search bar, type “checkbox”.

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/04_prototype_iconify_search_bar.png?raw=true" alt="iconify_searchBar" width="400" height="100">
</div> 
<br>

**3.3** In the lists of all the icons, go to the second page of it, and click on the black colored background checkbox located on the second line, the fifth one from the left.

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/05_prototype_select_icon.png?raw=true" alt="iconify_searchBar" width="400" height="200">
</div> 
<br>


**3.4** A dropdown window should opened up when you click on the icon. Set the color of the icon to #FF7461.

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/06_prototype_iconify_color_settings.png?raw=true" alt="iconify_color_settings" width="300" height="200">
</div> 
<br>

**3.5** At the bottom right, click “**Import as Component**.” Then manually close the window.

**3.6** Locate your newly made component, and select it. Make sure that it’s outlined with the color purple which indicates that it is a component and it is being selected.

**3.7** On the design setting, make the following changes:
* W: 22
* H: 22

**3.8** Rename the icon to “checked”

## Task 4: Prototype checkboxes buttons

Remember the **main component** we created from the **Components and Instances** page? We will now prototype the main component and connect it with the icon we just created.

**4.1** Select the main component of an empty box. On the design settings, click Variant.

>Variants are component combinations that we can group as a single component set.

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/07_prototype_create_variant.png?raw=true" alt="create_Variant" width="200" height="500">
</div> 
<br>

Now your main component should look something like below.

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/08_prototype_unchecked_as_variant.png?raw=true" alt="unchecked_as_variant" width="200" height="300">
</div> 
<br>

**4.2** Drag your recently created icon over and on top of the second empty box.	

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/09_prototype_toggle_variant.png?raw=true" alt="toggle_variant" width="200" height="300">
</div> 
<br>

We will now be using them for this step so that users can toggle between completing their tasks or not. 

**4.3** Go to prototype mode by clicking on the right-hand panel under “**Prototype**.”

**4.4** Hover over the first box, then drag the button that appeared attached to the side of it over to the second box.

**4.5** Do the same with the second box, drag the connection from the second box over to the first one. The connection between the two boxes should look something like below.

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/10_prototype_toggle_connection.png?raw=true" alt="toggle_prototype_connection" width="200" height="300">
</div> 
<br>

<div style="background-color: #ffdfbf; padding: 14px; border-radius: 4px; color: black" >
<img align="left" width="45" height="45" src="https://cdn-icons-png.flaticon.com/128/3209/3209265.png?raw=true" alt="note-icon-png"> <strong>Note:</strong> <br>
Since we prototyped on a master component, all the other checkbox components on the User Dashboard frame are prototyped as well! Isn’t Figma very convenient? 😊
</div>



## Task 5: Present Your Prototype

Now that we’ve prototyped our mockup, let’s see how it works! There are two ways to present a mockup in Figma. First, you can *click* the arrow icon on the top right of the screen.



<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/11_prototype_present_method1.png?raw=true" alt="present_method_1_at_far_right_of_toolbar" width="300" height="50">
</div> 
<br>

Or you can click on the arrow icon beside your starting flow.

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/12_prototype_present_method2.png?raw=true" alt="present_method_2_beside_starting_flow" width="200" height="100">
</div> 
<br>

Your mockup now should work the same way as the video below!

<br>

<!-- <video width="320" height="240" autoplay loop>
  <source src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/13_prototype_mockup_complete_vid.mp4" type="video/mp4" />
  Your browser does not support the video tag.
</video> -->

<!-- <video src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/13_prototype_mockup_complete_vid.mp4?raw=true" autoplay loop>
Your browser does not support the video tag
</video> -->

![Prototype Video](https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/13_prototype_mockup_complete_vid.gif?raw=true)

<br>

<div style="background-color: #c1e2be; padding: 14px; border-radius: 4px; color: black" >
<img align="left" width="45" height="45" src="https://upload.wikimedia.org/wikipedia/commons/c/c6/Sign-check-icon.png?raw=true" alt="note-icon-png"> <strong> Success: </strong> <br>
You’ve successfully created a functional mockup! If you wish to learn more about prototyping, check out Molly Hellmuth’s <a href="https://www.uiprep.com/blog/ultimate-guide-to-prototyping-in-figma">‘Ultimate Guide to Prototyping in Figma’</a>
</div>



---

# Conclusion

Now that you’ve reached the end, you have now successfully learned the following:

The importance of setting your starter page and how to do it
Prototyping your mockup so that it’s able to switch between pages
Create an interactive button with toggle effects

Congratulations! If you encountered any issues, please check out the troubleshooting page after this one. Help is on its way!








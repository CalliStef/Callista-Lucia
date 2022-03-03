---
layout: default
title: Components and Instances
nav_order: 4
has_children: true
permalink: docs/utilities
---

# Components and Instances
{: .no_toc }

In Figma, components are elements that you can reuse across your designs. This will help your design stay consistent on every frame. 

Figma has a whole range of components, from buttons to layouts. For this documentation’s mockup, we’re gonna focus on two aspects to a component, a **Main (Master) Component**, and **Instances**.


> 1. A **Main Component** defines the properties of the Component.
> 2. An **Instance** is a copy of the Component you can reuse in your designs. Instances are linked to the main Component and receive any updates made to the Component.

<br> 

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Task 1: Create Log-In/Sign-Up buttons
   
   **1.1** On the very left of the toolbar, access the **Shape Tools** and select the rectangle option.
   
<br>   
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/01_components_shape_tool.png?raw=true" alt="Shape Tool" width="400" height="50" >
</div>

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/02_components_rectangle_option.png?raw=true" alt="Rectangle Option" width="200" height="200">
</div> 
<br>

   **1.2** Once you’ve done this, your pointer now should now be shaped similar to a plus sign (+), which means, you’re now ready to create the shape.

   **1.3** Now, with your pointer, in the log-in frame, below the sentence, “Mori is a simple To-Do list…,” *hold* and *drag* to create a rectangle. Let go of your *hold* once you’re done.
   
On the right-hand panel, under “**Design**,” set the following changes:
* X-position: 84
* Y-position: 699
* W: 236
* H: 53
* Radius: 20
* Color: FF7461

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/03_components_button1_design_Settings.png?raw=true" alt="button1_design_settings" width="200" height="500">
</div> 
<br>

Now your button should look something like the picture below! Isn’t it pretty?

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/04_components_button1.png?raw=true" alt="button1" width="200" height="200">
</div> 
<br>

  **1.4** Let’s add text to the button! Remember what we learned from the previous step? Click on the **Text tool** on the left of the toolbar.
  
<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/05_components_text_tool.png?raw=true" alt="text_tool" width="400" height="50">
</div> 
<br>

Now, your pointer should change to that of the icon! Add text to the button by *clicking* at the center of the button, then type “Log In.”
		
On the right-hand panel under **Design** set the following changes:
* X-position: 159
* Y-position: 707
* Text: Open Sans
* ExtraBold
* Size: 28
* Fill color: FFFFFF

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/06_components_text_settings.png?raw=true" alt="text_settings" width="200" height="500">
</div> 
<br>

  **1.5** Let’s group both elements together, this way we can simply select both the rectangular shape and the text together as a single element.

> Groups in Figma allow you to combine multiple elements together as a single top-level layer.

On the left panel, select both elements by holding and dragging your pointer over the two elements.

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/08_components_select_all.png?raw=true" alt="group_selection" width="400" height="500">
</div> 
<br>

Now, *right-click* on the element and select **Group Selection**.

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/07_components_group_selection.png?raw=true" alt="group_selection" width="200" height="500">
</div> 
<br>

Rename the group name from “Group 1” to “log-in button.”

**1.6** We’ve now created our first group. Since they both have the same design and look, we can simply copy our button layout.

*Click* one time on the new group and make sure that it is positioned with the following setting:
* X-position: 84
* Y-position: 779
		
**1.7** Now we need to change the text of the second group, *double click* on the text of the button to select the text separately.


<br>

<div style="background-color: #ffdfbf; padding: 14px; border-radius: 4px; color: black" >
<img align="left" width="45" height="45" src="https://cdn-icons-png.flaticon.com/128/3209/3209265.png?raw=true" alt="note-icon-png"> <strong>Note:</strong> <br>
When multiple elements are grouped together, to select them individually, you will have to double click on the element.
</div>

<br>

Change the text of the second group to “Sign up.”

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/09_components_logIn:SignUp_buttons.png?raw=true" alt="signUp_button" width="200" height="200">
</div> 
<br>

Congratulations on making it this far! Now we have two button components on our mockup! :raised_hands:

## Task 2: Build components for our task list in the **User Dashboard** frame

**2.1** Using the shapes tool, choose the rectangular option, then create one shape below the underlined text of “Welcome Back.”

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/10_components_shape1.png?raw=true" alt="shape1" width="200" height="500">
</div> 
<br>

On the right-hand panel, set its design settings to the following:
* X-position: 29
* Y-position: 147
* W: 349
* H: 290
* Radius: 15
* Fill Color: FF7461

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/11_components_shape1_design_settings.png?raw=true" alt="shape1_design_settings" width="200" height="500">
</div> 
<br>

We will leave this shape as it is for now. Don’t worry, on the next page/step of the documentation, we will come back to this.

**2.2** Create another rectangular shape below the text “Tasks for Today” and set its design settings to the following:
* X-position: 29
* Y-position: 510
* W: 349
* H: 360
* Radius: 25
* Fill Color: FCF3F0
* Add Effects: Drop shadow

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/12_components_shape2_settings.png?raw=true" alt="shape2_design_settings" width="200" height="500">
</div> 
<br>

Your **User Dashboard** frame should look like the image below! 


<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/13_components_bothShapes.png?raw=true" alt="completeLook_of_UserDashboard" width="200" height="500">
</div> 
<br>

## Task 3: Create checkboxes

Let’s start creating checkboxes for our tasks list! We will be doing this on the second rectangular of the **User Dashboard** frame. Since we would at least need more than 3 of these checkboxes, let’s use Figma’s feature of **components** and **instances**!

**3.1** Outside of the User Dashboard frame, create a small rectangular box with the following properties:
* W: 21.88
* H: 21.88
* Fill with opacity at 0%
* Radius: 2
* Stroke color: 000000
* Stroke width: 1
* Stroke outline: Inside

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/14_components_unchecked_design_settings.png?raw=true" alt="completeLook_of_UserDashboard" width="200" height="500">
</div> 
<br>

Your rectangular box should look like the image below.


<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/18_components_unchecked_box.png?raw=true" alt="component_icon" width="200" height="200">
</div> 
<br>

**3.2** *Click* on the element, make sure the element is outlined in blue to show that it is being selected. Then make it a **component** by *clicking* on the diamond icon located at the center of the toolbar.

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/15_components_componentIcon.png?raw=true" alt="component_icon" width="400" height="50">
</div> 
<br>

<br>

<div style="background-color: #ffdfbf; padding: 14px; border-radius: 4px; color: black" >
<img align="left" width="45" height="45" src="https://cdn-icons-png.flaticon.com/128/3209/3209265.png" alt="note-icon-png?raw=true"><strong>Note:</strong> <br>
&nbsp;&nbsp; Notice how Figma has now highlighted your element in purple? This means, that your element is now a <strong>main component</strong>.
</div>
<br>


Rename your new component to “unchecked/Default”

**3.3** When copying from a **main component**, those pasted elements are called **instances**. These **instances** are connected to the **main component’s** design.  Any changes created on the **main component** will affect all of its **instances**.
		
Copy-paste your component 5 times into the **User Dashboard** frame.


<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/19_components_main_instances.png?raw=true" alt="main_components_and_instances" width="200" height="200">
</div> 
<br>

## Task 4: Add Task Items

**4.1** All that’s left to do is simply add the tasks beside each of these checklists. Using the **Text tool**, create your texts using the following design settings on the right-hand panel:
* Font-family: Open Sans
* Text-style: Regular
* Size: 21
* Fill Color: 000000


<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/16_components_taskItems_text_settings.png?raw=true" alt="task_text_settings" width="200" height="500">
</div> 
<br>

Here's the final look of our task list!

<br>
<div align="center">
  <img src="https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/20_components_taskList_complete.png?raw=true" alt="taskList_complete" width="200" height="200">
</div> 
<br>

<br>

<div style="background-color: #c1e2be; padding: 14px; border-radius: 4px; color: black" >
<img align="left" width="45" height="45" src="https://upload.wikimedia.org/wikipedia/commons/c/c6/Sign-check-icon.png?raw=true" alt="note-icon-png"> <strong> Success: </strong> <br>
You’ve successfully created many components as well as instances for your Mockup! Your mockup should now look similar to the image below.
</div>

<br>

---

# Conclusion

Now that you’ve reached the end, you have now successfully learned the following:

1. How to use the Shape Tools and using the Design settings on the right-hand panel
2. Group elements together
3. Create the main component and its instances
4. The importance of using components for a more consistent and easy design

Congratulations! Continue on to the next page where we will go through one of the biggest features that Figma, plug-ins, and its community files!





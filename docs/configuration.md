---
layout: default
title: Creating & Using Frames
nav_order: 2
description: "Learn how to use and create frames in Figma"
permalink: /docs/configuration
---

# Creating & Using Frames
{: .no_toc }

Frames are one of the most foundational elements of Figma. They can serve as the container or viewport holding your app’s design components, but can also be a component in your design itself. In the coming section, we will be creating our first frame on Figma and getting our workspace ready to be worked with.

{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Task 1.1 Creating Your First Frame on Figma
**1.** To start your new design project, click on the “New design file” button inside the Dashboard. 
![image](https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/just-the-docs.png?raw=true)

**2.** Inside of your new work area, you will be presented with a navigation menu containing eight icons. Click on the grid-like icon highlighted in blue below. 

![image](https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/task1img2.png?raw=true)

**3.** You will notice a new side panel appear on the right side of the work area. These are the preset frame sizes Figma offers to match the dimensions of most devices. Make sure you are in the Design tab, and then click on the “iPhone 11 Pro Max” item from the Phone drop-down.

![image](https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/task1_img3.png?raw=true)

<img align="left" width="45" height="45" src="https://cdn-icons-png.flaticon.com/128/3209/3209265.png" alt="note-icon-png">&nbsp;&nbsp; **Note**:
&nbsp;&nbsp;If a drop-down menu appears, it means you have clicked on the drop-down arrow instead. Click on the first option “Frame” to continue.

**4.** Your work area should now have a frame that looks like the one in the figure below.

![image](https://github.com/CalliStef/Callista-Lucia/blob/gh-pages/assets/images/task1img4.png?raw=true)


## Task 1.2 - Renaming a Frame

**1.** Right click on the name of the desired frame on the left-side panel to activate its context menu. The name should have a blue background color once selected.

**2.** Select the Rename option highlighted below. 

**3.** Type “Login” for the first frame and click enter to confirm the change.

## Task 1.3 - Duplicating a Frame

**1.** Right click on the “Login” frame itself, making sure a blue border forms around the frame. Then, click the first option “Copy”.

**2.** Right click on an area off of the frame and select the option “Paste here”.

## Heading anchor links

```yaml
# Heading anchor links appear on hover over h1-h6 tags in page content
# allowing users to deep link to a particular heading on a page.
#
# Supports true (default) or false
heading_anchors: true
```

## Footer content

```yaml
# Footer content
# appears at the bottom of every page's main content
# Note: The footer_content option is deprecated and will be removed in a future major release. Please use `_includes/footer_custom.html` for more robust
markup / liquid-based content.
footer_content: "Copyright &copy; 2017-2020 Patrick Marsceill. Distributed by an <a href=\"https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt\">MIT license.</a>"

# Footer last edited timestamp
last_edit_timestamp: true # show or hide edit time - page must have `last_modified_date` defined in the frontmatter
last_edit_time_format: "%b %e %Y at %I:%M %p" # uses ruby's time format: https://ruby-doc.org/stdlib-2.7.0/libdoc/time/rdoc/Time.html

# Footer "Edit this page on GitHub" link text
gh_edit_link: true # show or hide edit this page link
gh_edit_link_text: "Edit this page on GitHub."
gh_edit_repository: "https://github.com/pmarsceill/just-the-docs" # the github URL for your repo
gh_edit_branch: "master" # the branch that your docs is served from
# gh_edit_source: docs # the source that your files originate from
gh_edit_view_mode: "tree" # "tree" or "edit" if you want the user to jump into the editor immediately
```

_note: `footer_content` is deprecated, but still supported. For a better experience we have moved this into an include called `_includes/footer_custom.html` which will allow for robust markup / liquid-based content._

- the "page last modified" data will only display if a page has a key called `last_modified_date`, formatted in some readable date format
- `last_edit_time_format` uses Ruby's DateTime formatter; see examples and more information [at this link.](https://apidock.com/ruby/DateTime/strftime)
- `gh_edit_repository` is the URL of the project's GitHub repository
- `gh_edit_branch` is the branch that the docs site is served from; defaults to `master`
- `gh_edit_source` is the source directory that your project files are stored in (should be the same as [site.source](https://jekyllrb.com/docs/configuration/options/))
- `gh_edit_view_mode` is `"tree"` by default, which brings the user to the github page; switch to `"edit"` to bring the user directly into editing mode

## Color scheme

```yaml
# Color scheme supports "light" (default) and "dark"
color_scheme: dark
```
<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Preview dark color scheme';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Return to the light side';
  }
});
</script>

See [Customization]({{ site.baseurl }}{% link docs/customization.md %}) for more information.

## Google Analytics

```yaml
# Google Analytics Tracking (optional)
# e.g, UA-1234567-89
ga_tracking: UA-5555555-55
ga_tracking_anonymize_ip: true # Use GDPR compliant Google Analytics settings (true by default)
```

## Document collections

By default, the navigation and search include normal [pages](https://jekyllrb.com/docs/pages/).
Instead, you can also use [Jekyll collections](https://jekyllrb.com/docs/collections/) which group documents semantically together.

For example, put all your documentation files in the `_docs` folder and create the `docs` collection:
```yaml
# Define Jekyll collections
collections:
  # Define a collection named "docs", its documents reside in the "_docs" directory
  docs:
    permalink: "/:collection/:path/"
    output: true

just_the_docs:
  # Define which collections are used in just-the-docs
  collections:
    # Reference the "docs" collection
    docs:
      # Give the collection a name
      name: Documentation
      # Exclude the collection from the navigation
      # Supports true or false (default)
      nav_exclude: false
      # Exclude the collection from the search
      # Supports true or false (default)
      search_exclude: false
```

You can reference multiple collections.
This creates categories in the navigation with the configured names.
```yaml
collections:
  docs:
    permalink: "/:collection/:path/"
    output: true
  tutorials:
    permalink: "/:collection/:path/"
    output: true

just_the_docs:
  collections:
    docs:
      name: Documentation
    tutorials:
      name: Tutorials
```


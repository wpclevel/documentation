---
layout: default
title: Edit A Menu Item
nav_order: 3
last_modified_date: 2020-10-18T18:54:08+0000
---

# Edit A Menu Item
{: .no_toc}

With smart context aware, Mega Menu Pro clones entire menu context when editing a menu item. It makes everything truly live.

**Table of Content**

1. General Settings section
2. Icon section
3. Mega section
4. Badge section
5. Restriction section
{:toc}


To start editing a menu item, **hover over the menu item** you want to edit and **click on “Edit Item” button**. A menu item editor will show up with original menu context like this:

![start editing a menu item]({{ '/assets/images/start-editing-a-menu-item.webp' | absolute_url }})

Then, click on the **Settings icon** at the bottom left (bottom right for RTL languages) to access editor controls and start editing.

![menu item edit screen]({{ '/assets/images/menu-item-edit-screen.png' | absolute_url }})

### 1. General Settings section

![menu item general settings]({{ '/assets/images/edit-item-general-settings.png' | absolute_url }})

This section contains general settings for the editing menu item. The control labels are descriptive. Try it yourself to see how things work.

### 2. Icon section

![menu item icon settings]({{ '/assets/images/menu-item-icon-section.png' | absolute_url }})

Currently, there's only one control which allows you to choose menu item icon in this section.

### 3. Mega section

![menu item mega settings]({{ '/assets/images/menu-item-mega-section.png' | absolute_url }})

1. **Enable Mega**: Enable mega menu for the editing menu item or not.
2. **Enforce Mobile Layout**: When displaying Mobile Menu on Desktop, Elementor still renders columns for Desktop layout. If you're lazy to add custom CSS code, try this option.
3. **Mega Panel Fits To**: Select full screen width or an HTML element to sync the width and alignment of [the Mega Submenu]({{site.baseurl}}/#33-mega-submenu) with that element. If you inspect Elementor's HTML code, the options are based on this structure:
![mega panel fits to anatomy]({{ '/assets/images/mega-panel-fit-to-anatomy.png' | absolute_url }})

4. **Fit-To Element**: When the "Mega Panel Fits To" option is "Custom", you may use this option to use a custom HTML element instead of using the default options. Note that the DOM on the menu item editor is different from the actual DOM where the menu will be rendered. So, there may be notices about Fit-To element not found, just ignore it.
5. **Mega Panel Width**: If you want a fixed width, use this option. The position of the mega submenu will be calculated automatically to make sure everything is responsive.

### 4. Badge section

![menu item badge settings]({{ '/assets/images/menu-item-badge-section.png' | absolute_url }})

The control labels in this section are descriptive. Please try it out if you're not sure how things work. Note that Badge DOES NOT support global colors.

### 5. Restriction section

![menu item Restriction]({{ '/assets/images/menu-item-restriction.png' | absolute_url }})

Use this control to limit users who can see the editing menu item.

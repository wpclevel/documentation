---
layout: default
title: Getting Started
nav_order: 1
description: "This page shows you what are the requirements of Elemental Menu and its basic concepts to help you get started quickly."
permalink: /
last_modified_date: 2020-10-18T17:54:08+0000
---

# Getting Started
{: .no_toc }

Through out the documentation, I use [Hello Theme](https://elementor.com/hello-theme/?ref=17235) and [Elementor's Dark Mode](https://elementor.com/help/dark-mode/?ref=17235).

**Table of Content**

1. Requirements
2. Installation
3. Terminologies
    1. WordPress Menu
    2. Elementor Widget
    3. Mega Submenu
    4. Flyout Submenu
    5. Top Menu Bar, Top Level Submenu and Sub Level Submenu
    6. Off-Canvas Panel
    7. Dropdown Panel
    8. Current Menu Item
    9. Paged Menu Header
4. First steps
{:toc}

## 1. Requirements

For performance and security, Elemental Menu requires:

* WordPress version 5.5 or greater.
* At least 512MB of [PHP memory limit](https://wordpress.org/support/article/editing-wp-config-php/#increasing-memory-allocated-to-php).
* [Elementor Page Builder](https://elementor.com/?ref=17235) version 2.9.4 or greater.
* PHP version 7.2 or greater (PHP 7.4 or greater is recommended).
* MySQL version 5.5 or greater (MySQL 5.7 or greater is recommended).

## 2. Installation

If you're familiar with installing a WordPress plugin, just go ahead with the standard routine.

If you're new to WordPress plugin, please refer to WordPress codex's [installing plugins](https://wordpress.org/support/article/managing-plugins/#installing-plugins) instruction to know how to install this plugin.

## 3. Terminologies

### 3.1. WordPress Menu

If you are new to WordPress, please check out [WordPress Menu User Guide](https://codex.wordpress.org/WordPress_Menu_User_Guide) to know how to interact with WordPress Menu System.

### 3.2. Elementor Widget

If you're new to [Elementor Page Builder](https://elementor.com/?ref=17235), please checkout [Elementor's Getting Started](https://elementor.com/getting-started/?ref=17235) to grab some basic ideas.

### 3.3. Mega Submenu

A Mega Submenu is a submenu of a mega menu item:

![Elementor Mega Submenu]({{ '/assets/images/elemenentor-mega-submenu.png' | absolute_url }})

### 3.4. Flyout Submenu

A Flyout Submenu is a submenu of a non-mega menu item and contains sub menu items:

![Elementor Flyout Submenu]({{ '/assets/images/elementor-flyout-submenu.png' | absolute_url }})

### 3.5. Top Menu Bar, Top Level Submenu and Sub Level Submenu

1. **Top Menu Bar** is the menu bar (either vertical or horizontal) which contains top level menu items.
2. **Top Level Submenu** is a Mega Submenu or the very first Flyout Submenu.
3. **Sub Level Submenu** is a submenu of a submenu.

![Elementor Submenu Hierarchy]({{ '/assets/images/elementor-submenu-hierarchy.png' | absolute_url }})

### 3.6. Off-Canvas Panel

Off-Canvas Panel is a panel which is hidden by default. By clicking on the menu toggle button, this panel will slide out (from left or right), cover entire screen with an overlay and temporarily block the page behind it from interaction:

![Elementor Mega Menu Off-Canvas Panel]({{ '/assets/images/elementor-mega-menu-off-canvas-panel.webp' | absolute_url }})

You can close the Off-Canvas panel by either clicking on anywhere outside the panel or the close/back button.

### 3.7. Dropdown Panel

Dropdown Panel is a panel which is also hidden by default. By clicking on the menu toggle button, this panel will slide down as you can see in the image below. It does not cover entire screen or block the page behind it from interaction.

![Elementor Mega Menu Dropdown Panel]({{ '/assets/images/elementor-mega-menu-dropdown-panel.webp' | absolute_url }})

You can close a Dropdown Panel by clicking on the menu toggle button only.

### 3.8. Current Menu Item

A Current Menu Item is a menu item linked to the page that is being viewed by an user.

### 3.9. Paged Menu Header

![paged menu header]({{ '/assets/images/paged-menu-header.png' | absolute_url }})

Paged Menu Header is the top section of a Mobile Menu displaying in "Paged" layout.

## 4. First steps

Ok, you have installed the plugin successfully. Now,

1. Create a menu by go to **Dashboard** > **Appearance** > **Menus** > **Create a new menu**
2. Open your Elementor editor. (A page, a template...)
3. Enter "menu builder" on the search box of the Elementor Widgets Panel.
![searching for elementor mega menu widget]({{ '/assets/images/elementor-search-for-mega-menu.png' | absolute_url }})
4. Drag and drop the "Elemental Menu" widget into the location where you want to show this menu.
5. From "Menu" control, select the menu you just created at step 1.
![selecting a menu to edit]({{ '/assets/images/elementor-select-menu.png' | absolute_url }})
6. Click on the Elementor editor's "**PUBLISH**" or "**UPDATE**" button.

That's all to get started with the plugin. Let's move to the next topic: [Adjust Menu Appearance]({{ '/adjust-menu-settings' | absolute_url }})

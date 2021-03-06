---
title: Juxta: Recreating the Demo - Utility
description: Your Guide to Recreating Elements of the Juxta Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/juxta:Juxta

---

Utility Section
-----

![][demo]

Here is the widget breakdown for the Utility section:

#### Gantry Login Button

The **Gantry Login Button** widget activates the **Login** pop-up which allows members to log in to their accounts on the frontend of the site. Simply drag this widget to the widget section (there's a separate widget section for the **Gantry Login Form**) and complete the following to replicate the demo.

* Enter `Member Login` in the **Login Text** field.
* Enter `Logout` in the **Logout Text** field.
* Leaving everything else at its default setting, select **Save**. 

This button doesn't do anything if there isn't a widget in the **Popup** widget position. In our demo, we use the **Gantry Login Form** widget. Below are the settings used in our demo.

#### Gantry Login Form

![][demo2]

The login form located on the front page is actually a **Gantry Login Form** widget. Here are the widget options you will need to change in order to match the demo.

| Option        | Setting     |
| :----------   | :---------- |
| Title         | `Login`     |
| User Greeting | Hi,         |
| Pre-text      | Blank       |
| Post-text     | Blank       |

[demo]: assets/demo_3.jpeg
[demo2]: assets/demo_6.jpeg
[menu]: ../../start/menus.md
[faq]: faq.md

# Baizonn Learning Center Theme

Welcome to the Baizonn Learning Center theme. This theme is designed to provide a clean and modern look for educational websites, specifically tailored for learning centers, schools, or online educational platforms.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [File Structure](#file-structure)

## Overview

The Baizonn Learning Center theme is developed to create an engaging and intuitive experience for both students and educators. It emphasizes simplicity, ease of navigation, and responsiveness, ensuring accessibility across all devices.

## Features

- **Responsive Design**: Fully responsive layout that works on desktops, tablets, and mobile devices.
- **Modern Aesthetic**: Clean and modern design with a focus on readability and usability.
- **Navigation Bar**: A fixed navigation bar for easy access to different sections of the website.
- **Customizable Header**: An attractive header with options to include images and branding elements.
- **Blog Integration**: Built-in support for blog posts and announcements.
- **Contact Form**: Integrated contact form for inquiries and registrations.
- **Social Media Links**: Easily connect with social media platforms like Twitter, Facebook, and GitHub.
- **Class Schedule Section**: Display upcoming classes with an interactive schedule.

## Usage

This theme is structured with HTML, CSS, and JavaScript files to make customization straightforward. Here are the primary components:

    Home Page (index.html): The main landing page featuring announcements and recent updates.
    About Page (about.html): Information about the Baizonn Learning Center and its mission.
    Registration Page (registration.html): A form to register for classes, with fields for personal information and class selection.
    Schedule Page (schedule.html): Displays the schedule of upcoming classes and events.

- **Home Page**: The home page contains the following sections:
    Navigation Bar: Includes links to other pages such as Home, About, Registration, and Schedule.
    Header: Features the site's name and a background image.
    Posts: Lists recent announcements and news with links to full articles.
    Footer: Contains social media links and copyright information.

- **About Page**: The about page includes:
    Introductory Text: Describes the center's history, values, and educational approach.
    Footer: Social media links and copyright notice.

- **Registration Page**: The registration page allows users to sign up for classes:
    Form Fields: Name, email, phone number, and class selection.
    Submit Button: Sends the registration information to the server.

- **Schedule Page**: The schedule page shows class timings:
    Schedule Image: A background image representing the class schedule.
    Footer: Social media links and copyright notice.

## Customization

You can customize the theme by modifying the following files:

    CSS (css/stylesheet.min.css): Adjust colors, fonts, and layout styles.
    HTML Files: Update text, add sections, or change images.

- **Changing the Header Image**: To change the header image on any page, locate the <header> tag and update the background-image URL. For example, in index.html:

<header class="intro-header" style="background-image: url('image/Centre\ Logo\ 5.jpg')">

- **Modifying Navigation Links**: Update the navigation bar links by editing the <nav> section in each HTML file. Example from index.html:

<nav class="navbar navbar-default navbar-custom navbar-fixed-top">
    <ul class="nav navbar-nav navbar-right">
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="registration.html">Registration</a></li>
        <li><a href="schedule.html">Schedule</a></li>
    </ul>
</nav>

- **Social Media Links**: Update the social media icons in the footer with your links:

html

<li>
    <a href="https://twitter.com/yourhandle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-circle fa-stack-2x"></i>
            <i class="fa fa-twitter fa-stack-1x fa-inverse"></i>
        </span>
    </a>
</li>

## File Structure

Here's a breakdown of the project's file structure:

python

baizonn-learning-center-theme/
│
├── css/
│   ├── stylesheet.min.css      # Main stylesheet
│
├── images/
│   ├── Centre Logo 5.jpg       # Header background image
│   ├── Centre Logo 8.jpg       # Registration page header image
│   ├── schedule.png            # Schedule background image
│
├── index.html                  # Home page
├── about.html                  # About page
├── registration.html           # Registration page
├── schedule.html               # Schedule page
│
└── README.md                   # Project overview
|__ deployment.md               # Deployment workflow
|__ theme.md                    # Features our theme has (This file)
|__ site.md                     # WordPress
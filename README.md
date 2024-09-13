
# Moon Light Spa

**Moon Light Spa** is a simple multi-page website built with HTML and CSS. It consists of various pages such as a homepage, pricing page, contact page, and a thank-you page. This project is designed to showcase a professional spa service, allowing users to explore offered services, view pricing details, and contact the spa for inquiries. Having worked in the hospitality industry for years (Spa and Fitness to be precised), i gained experience in understanding the needs and expectations of guests from different parts of the world seeking relaxation,rejuvenation and over-all sense of wellbeing. This inspisred me to develop the concept of **Moon Light Spa**, which combines the luxurious services of traditional spa with a unique,immersive experience that appeals to both body and mind.

![Reference image](/assets/images/screenshot12.png)

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Pages](#pages)
5. [User Experience](#user-experience)
7. [Typography](#typography)

## Overview

Moon Light Spa is a website designed to provide information about spa services, including service pricing and a contact form for customer inquiries. The website uses pure HTML and CSS, making it lightweight and easy to navigate. It is fully responsive and ensures an optimal user experience across various devices, from desktop to mobile.

The website includes the following key pages:

- **Homepage (index.html)**: An overview of the Moon Light Spa services.
- **Pricing Page (prices.html)**: Detailed pricing information for various spa services.
- **Contact Page (contact.html)**: A contact form for customers to submit inquiries or make reservations.
- **Thank You Page (thank-you.html)**: A confirmation page that appears after a successful form submission, below is the sample code

 ![Reference image](/assets/images/screenshot9.png)


## Features

- **Responsive Design**: The website is fully responsive and adjusts to different screen sizes for desktop and mobile.
- **Multi-Page Layout**: Consists of multiple HTML pages that are interlinked, providing a smooth user navigation experience.
- **Contact Form**: it is a functional form where users can submit their name, email, and inquiries. After submitting, they are redirected to a confirmation page.

## Project Structure

```
├── index.html
├── prices.html
├── contact.html
├── thank-you.html
├── assets
└── css/styles.css
    └── images/
```

## Pages

### 1. `index.html`
The homepage serves as an introduction to Moon Light Spa. It contains the following:
- A welcome message.
- An overview of available services.
- Navigation links to the pricing and contact pages.

### 2. `prices.html`
This page outlines the pricing structure for different spa services, such as massages, facials, and other treatments. The prices are presented in a simple table or grid format.

![Reference image](/assets/images/screenshot4.png)

There are also prices for special treatment such as couple's massage,scalp massage ,pregnant women massage etc.

![Reference image](/assets/images/screenshot3.png)

### 3. `contact.html`
The contact page includes a form for visitors to fill out. The form typically includes fields for:
- Name
- Email address
- Message

![Reference image](/assets/images/screenshot5.png)


When the form is submitted, users are redirected to the thank-you page to confirm that their message was sent successfully.

### 4. `thank-you.html`
The thank-you page is displayed after a user successfully submits the contact form. It includes a message thanking the visitor for their inquiry and may provide further instructions or a link to return to the homepage.

![Reference image](/assets/images/screenshot1.png)

## User Experience 

* As a user, i want to easily book an appoinment online and personalized my treatment.
* As a user, after booking, i want to receive a confirmation message.
* As a user, upon arrival at the spa, the staff already knows my preference because of my online booking.
* As a user, my treatment is customized according to the preference i made during online booking.

## Typography

I used courier New fonts since it makes code easier to read and is one of the most commonly used in some programming.

## Styles

### Header Topic Styling

A large serif font with bold styling and uppercase transformation were used for emphasis.

```
header h1 {
    font-size: 4.5rem;
    font-family: 'Playfair Display', serif;
    font-weight: 700;
    text-transform: uppercase;
    text-shadow: 0 8px 16px rgba(0, 0, 0, 0.6);
}

```
In this project the primary font used here is Arial which is part of the sans-serif family.

## Features Left to Implement

* I would like to integrate a referral feature where users earn rewards for referring friends and realtives.

## Main Technologies Used 
* Html (Hyper Text Markup Language) used to structure the content of web page.
* Css(Cascading Style Sheets) used for styling and layout of the page.
* Javascript used for form validation.
* Github pages used for hosting the deployed site.

## Responsive Testing
* Responsive Testing On Screen Devices and Browsers
  * The game is responsive,looks good and works on all standard sizes.
  * The game is functional and looks good when tested with Chrome, Firefox, Microsoft Egde browsers.

## Bugs

* Solved Bug
I discover my project was broken when viewed on mobile device. Media query was added to make it responsive on mobile device.


## Validation Testing

* CSS
   * No errors where found when tested through [css validator](https://jigsaw.w3.org)

   ![Reference image](/assets/images/screenshot11.png)

* HTML
   * No errors were found when tested through [w3c validator](https://validator.w3.org)

    ![Reference image](/assets/images/screenshot10.png)

## Accessibilty

* Lighthouse Report was used to measure the quality of the project performance,accessibilty, best pratices SEO scores.

![Reference image](/assets/images/screenshot13.png)
## Deployment

* The site was deployed to Github as follows:
   * Navigate to setting area in the Github repository, and then page section.
   * Select main branch from the source section and save.
   * Deployment to the site starts.
   The live link can be found here:

   https://ozi-cheri.github.io/moon-light-spa/


   ## Local Clone
   * Sign up or log in on Github
   * Click "code" button and copy the provided link.
   * Enter git clone in the terminal,paste the link and run it.

   ```
   git clone https://github.com/ozi-cheri/moon-light-spa.git
   ```

   ## Forking The Github Repository

   * Locate the Github log in[repository](#repository)
   * Click the "fork" button at the the right top corner of the page.

   ## Credits

   ### Content

  * Code Institute LMS (https://codeinstitute.net)
  * Image used for the home page taken from pexel (https://www.pexels.com)
  * Home  page content from  Wanpen Thaimassage (https://www.wanpen-thaimassage.com) 
  * w3school (https://www.w3schools.com)
  * Stack overflow (https://stackoverflow.com)
   

   ## Acknowledgement

   Code Institute for the platform






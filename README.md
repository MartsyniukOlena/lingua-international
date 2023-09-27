___
# Lingua International

Lingua International is a dynamic platform designed to empower individuals from diverse backgrounds with the invaluable skill of English proficiency. 

The school caters to a broad spectrum of learners, including beginners eager to embark on their English learning journey and those seeking to refine their existing skills. Language acquisition is not just about mastering grammar and vocabulary but also about engaging in meaningful conversations. That's why the school host an open speaking club accessible to all, encouraging students to discuss various topics, bridging cultures and perspectives. The club welcomes English learners and also native speakers who wish to connect, share their experiences, and contribute to a vibrant language exchange environment. 

The platform ensures that whether you're a non-native speaker striving for fluency or a native speaker eager to share your language and culture, Lingua International has something enriching for everyone.

![mockup](readme-media/mockup.png)

>Business Goals:

1. To establish Lingua International as a leading platform for English language learning and language exchange.

2. To create a vibrant and inclusive community of English learners and native speakers.

>User Needs:

1. Provide a platform for individuals of all levels (beginner to advanced) to improve their English language skills.

2. Offer a space for native English speakers to connect, share experiences, and engage in language exchange.
___

## Features

The Lingua International website offers several key features for its users.

__Existing Features__
___
- __Navigation Bar:__

The Navigation Bar is featured on all pages of the website. It is fixed, so the user should not scroll up to switch between the pages. It includes the Logo with the link to the homepage, Home page, Courses page and Enroll page.
![Navigation bar](readme-media/navigation-bar.png)
This section will allow to explore and access various sections of the website easily. It provides value by offering quick and convenient navigation, enabling users to find the information they seek efficiently. 

___
- __Home Page:__

The home page provides a welcoming introduction to Lingua International, emphasizing its dedication to English language education and its transformative approach to elevating English proficiency.
It is for potential students and individuals interested in learning English.
![Hero](readme-media/hero-section.png)
___
- __About Us:__

The "About Us" section introduces Lingua International's mission and commitment to providing top-quality English language education, creating a sense of trust. It contains a call to action paragraph and a button to go to the course offerings.
It's for potential students who want to learn more about the school and its values.
![About us](readme-media/aboutus-section.png)

___
- __Why Choose Lingua International?:__

This section highlights the key benefits of choosing Lingua International, such as experienced instructors, interactive learning, a supportive community, flexibility, and inclusivity.
It's for potential students who evaluate their options and want to understand why Lingua International stands out.
![Why Choose Lingua International](readme-media/why-section.png)
___
- __Speaking Club:__

The Speaking Club provides a platform to practice English speaking skills in a supportive and interactive environment, fostering fluency and community building.
It's for current students and anyone interested in improving their English speaking skills and connecting with others. It is also open for native speakers. Below the section, there is an enroll button to sign up.
![Speaking Club](readme-media/speaking-club-section.png)
___
- __Photo caurousel:__

The Photo carousel consists of three photos from the course to demonstrate the friendly and positive atmosphere in which students learn. 
This feature aims to appeal to prospective students, helping them envision the welcoming environment students will be a part of and encouraging them to choose the school for its nurturing educational atmosphere.
![Photo caurousel](readme-media/carousel.png)
___
- __Courses:__

This section details the various English language courses offered by Lingua International, helping users understand the available options and how to achieve their language learning goals. The School offers English language courses for individuals at different proficiency levels. The courses are two basic courses (beginner level and intermediate level).
![Basic Courses](readme-media/courses-section-basic-levels.png)

And two advanced courses (business English and academic English).
![Advanced Courses](readme-media/courses-section-pro-levels.png)

Each course has a content description that aligns with each user's goals and needs, duration, flexible scheduling options and costs. And enroll button to enroll on the desired course easily.
It's for prospective students seeking information about the courses offered.
___
- __Enroll:__

The enrollment section provides a pathway for interested individuals to take the next step in their language-learning journey by signing up for courses. The form consists of the following elements: First Name, Last Name, Email, Phone Number, Address, select area for a course of interest, and Message.
![Enroll](readme-media/enroll-page.png)
This is for prospective students who are ready to enroll in a course.
___
- __Footer__

It is featured on all pages of the website.
![Footer](readme-media/footer-section.png)

The footer section caters to language learners, prospective students, and individuals interested in services.

The footer consists of the following elements:

Social Media Links (Facebook, Twitter, Instagram, YouTube): These links allow users to connect with the school on various platforms easily.This feature is especially useful for language enthusiasts, potential students, and anyone interested in staying connected with Lingua International.

Copyright © Lingua International 2023: The copyright paragraph in the footer protects intellectual property and also assures users that the content is up-to-date.

Working Hours: It helps users to plan their interactions with the school. It benefits students and clients who want to visit a physical location or contact the school during working hours.

Address: Physical address allows users to locate the school quickly. This information is essential for potential students and clients who want to visit the premises for consultations, classes, or other inquiries.

Email Address and Phone Number: It offers users additional communication channels. This is valuable for inquiries, support, and general correspondence. Users can easily reach out to the school for any language-related questions or concerns.
___
- __Thank you page__
![Thank you page](readme-media/thankyou-page.png)
After registering, a user is redirected to a thank you form to confirm that their registration is successful and express gratitude.

## Features Left to Implement:
- Online lessons, masterclasses, webinars
- Blog
- Downloadable resources like speaking tips, presentations, and reading materials
- Access to recordings or transcripts of past club meetings and events
- Calendar of upcoming events and courses
- Chat for members to discuss speaking topics, share ideas, and seek advice
- A pop-out window to subscribe to a newsletter for updates and event notifications
- Testimonials and Stories

## Testing
I conducted the following testing:

__Functionality Testing:__

- Verified that all links work correctly
- Tested the form
- Ensured that the site's navigation menu and buttons work as expected

__Compatibility Testing:__

- Checked how the website works on different web browsers - Chrome, Firefox, Edge
- Tested the website on desktop and mobile
- Tested the website on Windows and Android

__Performance Testing:__

Performance testing was done with Lighthouse.
The current results are the following:
![Lighthouse current report](readme-media/lighthouse-report.png)

The bugs that Lighthouse showed and that were fixed are:

- resized images and converted them to webp
- added alt to images in the carousel
- added  header "Day" to the table element
- removed stray tags - body, header, main, div
- changed colors for contrast on the carousel and navigation menu

__The issues left to fix__ (to improve performance and SEO)
- Serve static assets with an efficient cache policy 
- make the links crawable on the carousel for previous and next buttons

__Validator Testing__

HTML: No errors were found when passing through the [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmartsyniukolena.github.io%2Flingua-international%2F)

CSS: No errors were found when passing through the [Jigsaw validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmartsyniukolena.github.io%2Flingua-international%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

## Deployment

The site was deployed to GitHub pages.

In the GitHub repository, go to Settings --> In the Code and automation section on the left side, Press Pages --> Under the Source, select 'Deploy from a branch' --> Under the Branch, select Main and press the Save button.
Refresh the page. The link will be at the top.

The live link can be found here - https://martsyniukolena.github.io/lingua-international/

## Credits
Color palette was generated at [MyColor](https://mycolor.space/?hex=%2331809A&sub=1)

Favicon was downloaded at [Icons8](https://icons8.com/icons/set/book)

Icons were downloaded from [Fontawesome](https://fontawesome.com/search)

Pictures were downloaded from [Pexel](https://www.pexels.com/search/group%20of%20people/?orientation=landscape&size=large)

Carousel was copied from [w3schools](https://www.w3schools.com/howto/default.asp) (it includes HTML code, CSS and JavaScript)

Description for business english was taken from [British Counsil](https://learnenglish.britishcouncil.org/business-english)

To check grammar and edit text, I used [Grammarly](https://app.grammarly.com/)

I referenced the Love Running project as a guide(to create header, general styles, for hero image and cover text, registration form) and also Coders Coffeehouse(to create the table for working hours).

I used address generator to create the address.







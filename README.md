# Footlose Run Club
Run Club Global is your gateway to an active, like-minded community of runners—whether you’re training for your first 5K or dreaming of a world-tour marathon. With a bold, full-screen hero image and three compelling reasons to lace up, our site immediately shows you why running with us matters. Explore five of the most iconic marathons around the globe through richly illustrated feature cards, then get in touch via our embedded map and contact details or join directly with a simple, validated sign-up form. Finally, soak up the club spirit in our photo gallery of past events. Built with Bootstrap and flexbox for seamless responsiveness, clear navigation, and accessible design, Run Club Global makes it effortless to find inspiration, connect with fellow runners, and take your next stride.

[Contents](#contents)
  * [User Goals](#user-goals)
  * [User Stories](#user-stories)
  * [Website Goals and Objectives](#website-goals-and-objectives)
  * [Wireframes](#wireframes)
  * [Design Choices](#design-choices)
    + [Typography](#typography)
    + [Colour Scheme](#colour-scheme)
    + [Images](#images)
    + [Responsiveness](#responsiveness)
- [Features](#features)
  * [Existing Features](#existing-features)
    + [Header](#header)
      - [Instructions](#instructions)
      - [Feedback](#feedback)
    + [Landing View](#landing-view)
    + [Question View](#question-view)
    + [Final Score View](#final-score-view)
    + [Footer](#footer)
  * [Future Enhancements](#future-enhancements)
- [Technologies Used](#technologies-used)
  * [Languages](#languages)
  * [Libraries & Framework](#libraries---framework)
  * [Tools](#tools)
- [Testing](#testing)
  * [Bugs Fixed](#bugs-fixed)
  * [Responsiveness Tests](#responsiveness-tests)
  * [Code Validation](#code-validation)
    + [HTML](#html)
    + [CSS](#css)
    + [JavaScript](#javascript)
  * [User Story Testing](#user-story-testing)
  * [Feature Testing](#feature-testing)
  * [Accessibility Testing](#accessibility-testing)
  * [Lighthouse Testing](#lighthouse-testing)
  * [Browser Testing](#browser-testing)
- [Deployment](#deployment)
  * [To deploy the project](#to-deploy-the-project)
  * [To fork the project](#to-fork-the-project)
  * [To clone the project](#to-clone-the-project)
- [Credits](#credits)



## User Goals

* Find club info quickly: Clear, intuitive navigation to Home, Marathons, Contact, Sign-Up, Gallery.
* Understand club benefits: Three compelling reasons to run with us showcased up front.
* Browse inspiring races: Glimpse five top global marathons with imagery and key facts.
* Get in touch easily: Club email, phone, meetup address & map embedded.
* Join the club: Simple, validated sign-up form collecting name, email, preferred training time.
* See club spirit: Photo gallery of past runs conveys community vibe.
* Use on any device: Fully responsive from mobile through desktop.

## User Stories 

* As a first-time visitor, I want intuitive navigation and a responsive layout, so I can explore the running club site on any device.
* As a prospective member, I want to read three clear reasons to join, so I understand the club’s value.
* As a runner, I want a showcase of five remarkable global marathons, so I can dream about my next race.
* As an interested runner, I want to see contact details and an embedded map, so I can plan a visit.
* As a new member, I want a quick sign-up form with validation, so I can join the club without confusion.
* As a curious visitor, I want a gallery of past events, so I feel the community energy.
* As a social runner, I want social-media links and share buttons, so I can follow and spread the word.
* As a returning fan, I want to subscribe to a “Club Roundup” newsletter, so I never miss news.
* As a frequent visitor, I want the site to load fast and stay legible, so I have a smooth experience.
* As an accessibility-minded user, I want good contrast and alt text on images, so the site is inclusive.



## Website Goals and Objectives

* Inform & inspire by present club benefits and global marathons in a concise, visually engaging way.
* Convert Visitors to Members by guiding readers through reasons → contact → sign-up flow.
* Showcase the community using a gallery of real runners emphasizes club spirit.
* Maintainability & Performance using clean, semantic HTML & CSS; optimized assets; mobile-first responsiveness.
* Make it accessible & SEO conform by using proper headings, alt text, ARIA where needed; meta tags for discoverability.


## Target Audience

* Local and visiting runners (all levels)
* Marathon dreamers looking for inspiration
* Community-oriented athletes seeking group training
* Casual site visitors curious about global races

[Back to top](#contents)

## Wireframes
### Mobile-first sketches created in Figma:
* Hero + reasons stacked
* Marathon cards in single column
* Contact info → map → form
* Gallery thumbnails scrollable

### Tablet & Desktop:
* Hero full-width with overlay text; reasons as three-column grid
* Marathon cards in two- or three-column grid
* Contact/map side-by-side
* Gallery as responsive grid

## Design Choices

### Typography
* Headings: Montserrat, sans-serif — bold, modern, energetic
* Body: Open Sans, sans-serif — highly legible for paragraphs and lists

### Colour Scheme 
Base the palette on energetic “sunrise” and “track” hues to evoke motion and community:

| CSS Name                 | HEX       | Comment                       |
| ------------------------ | --------- | ----------------------------- |
|     --primary-color      | #2E8B57 | Buttons, links, highlights    |
|     --secondary-color    | #FF8C00 | Font color for the quiz       |
|     --bg-light           | #F9F9F9 | Page background               |
|     --text-dark          | #333333 | Body text                     |
|     --accent-color       | #1E90FF | Hover states, card borders    |
|     --muted-gray         | #666666 | Secondary text                |

## Imapges

### Responsiveness

## Features

### Existing Features

#### Header & Navigation
* Sticky Bootstrap navbar with anchor links to each major section.
* Smooth scroll on click (CSS scroll-behavior: smooth;).
* Collapsible mobile menu with clear “hamburger” icon.

#### Home (Landing) View
* Hero: Full-width background image + overlay heading, subheading.
* 3 Reasons: Bootstrap cards/flex items with icons (e.g., 🏃, 🤝, 🌍), titles, 1–2-line blurbs.
* Quick Contact: Email & phone snippet under hero.

#### Marathons View
* Section title “Our Favorite Global Marathons.”
* Five Bootstrap cards laid out responsively, each with:
   * Race image (alt text)
   * Name, location, date
   * One-sentence highlight (e.g., “Run across Venice’s canals!”)

#### Contact View
* Club email (mailto:) and phone (tel:) links.
* Physical meetup address.
* Embedded Google Map iframe showing meetup spot.

#### Sign-Up View
* Form collecting: Name, Email, Preferred Training Day/Time dropdown.
* HTML5 validation (required, type="email").
* Submits to thank-you.html.

#### Gallery View
* Responsive grid of at least 6 thumbnails.
* Clicking opens full-size image in a new tab or lightbox.

#### Footer
* Social icons (Facebook, Instagram, Strava) linking to club profiles.
* Newsletter signup form (email only) with inline validation.
* © Year + club name.

#### Future Enhancements
* Events Calendar: visual calendar of upcoming runs.
* Testimonials Slider: rotating quotes from members.
* Dynamic Map: filterable map of training routes.
* Multi-language Support: English + local language toggles.
* Blog Section: articles on training tips & race recaps.
* Social Sharing: “Share this Marathon” buttons via Twitter/FB intents.
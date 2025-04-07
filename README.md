# nandakishan
This project is a responsive personal portfolio website built using HTML and CSS. It includes multiple sections like Home, About, Projects, Contact, and Achievements. The site features a dark theme, smooth animations, a rotating border around the profile image, interactive social icons, and a clean layout.
1. Head Section
Includes:

Character encoding

Viewport settings for responsiveness

Google Fonts (Poppins)

Boxicons CDN for social and UI icons

Title of the website

Link to style.css (external CSS file)
2. Navigation Bar (<nav class="navbar">)
A fixed navigation bar at the top of the page with:

A logo (text-based)

A list of navigation links (Home, About, Projects, Contact, Achievements)

Uses position: fixed to stay visible at the top while scrolling

Entry animation fades it in smoothly
3. Home Section (<section class="home">)
Contains:

Text info: Name, personal tagline, and a short description

Social media icons with hover effects (GitHub, Instagram, etc.)

Profile image inside a circular container with a rotating animated border
4. About Section
Describes:

Background and interests

Educational journey

Talents 

Languages spoken

Coding languages known
5. Projects Section
Highlights:

Personal or academic projects

Option to display project names, images, and descriptions
6. Contact Section
Includes:

Email address

Phone number

Social icons
Resets default margin and padding

Uses box-sizing: border-box for better sizing control

Applies a serif font and light text color for contrast

Sets a dark background
The navbar fades in smoothly after a short delay

This provides a polished entry effect
Icons get a hover highlight with a glowing box shadow

Makes them feel tactile and interactive
Optional effect (e.g. intro loader or background flair)

Bars slide down with staggered timing using --i variable
On larger screens, the layout switches from vertical to horizontal (side-by-side profile + info)

Image size adjusts for better layout balance
Boxicons: Provides modern, lightweight icons for GitHub, LinkedIn, etc.

Sticky Navbar: Keeps navigation at the top while scrolling

Semantic HTML: Easy to read, accessible structure


Feature	Implementation
Animated Navbar	@keyframes show-content
Rotating Image Border	@keyframes rotate-border, ::before/after
Hover Effects (Icons)	Color and shadow on hover
Responsive Design	@media screen and (min-width: 768px)
Section-Based Navigation	Smooth jump via anchor links
Dark Theme	Dark background + light text
Personalization	Custom profile, talents, achievements

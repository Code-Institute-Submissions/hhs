# First Milestone Project - Herts Home Security

For my first milestone project I decided I wanted to make a website that meant something to me personally,
potentially something that I could use. Alongside my current employment and my studies, I run a small family
business with my two brothers. Our business is in the home security sector, supplying and installing CCTV,
intruder alarms, etc for homes and comercial properties. As we are a small company we only cover the county
of Hertfordshire. The aim of the website is to attract new customers, who can see our previous work and see
all the services we have to offer. Any potential customers can then get in touch with us directly by a number
of methods, be it through the enquiry form, or the many links to our contact details/social media pages.

When planning on how I wanted the website to look, I researched other home security websites. Most of which
covered the whole nation, as such have taken the approach of an urban feel with high rise city landscapes as
backgrounds and modern city centre style offices. This obviously attracts a different market to what we as a
company reach out to, we cover Hertfordshire which predominantley is known for it's countrysides and rural
landscapes. For that reason, I wanted my website to look different from other home security websites but offer
the same features. I've gone for a less traditional header image of a rural landscape of Hertfordshire, and
used green and grey colours throughout the website as I believe they compliment each other well, with the green
tying in to the rural feel.

## UX and Features

The design of this website was built in mind for new potential customers, who are looking for CCTV,
intruder alarms, etc. to be installed to their properties. The website has a static header and footer that is
the same across all the pages, that way the essential links are always available. The header image/writing is a
link back to the home page, the footer has contact details that includes a link to sending a direct email and
the social media links are always on the footer also. 

### Home

Once I had created the header and footer this was my framework for all pages. I felt that the home page didn't
'shout' out what the company done, so that is why I decided to add an image of security products directly below the
header, followed by a brief description of our business.

### Services

I decided the services page would suit being the next page along from 'Home', as customers will want to see what
services we have to offer. The layout and content of this page could be in much more detail and could have sub
pages coming from it, but due to time restrictions I went for a simpler approach. As we only offer a few services,
I wrote a brief description of each accompanied with an image of said service. Going forward I would like to
improve this page by having sub pages for each service to go into more detail of the different equipment we have
on offer for each service. I also added a link to our contact page so that if the customer was happy with what
they saw then they could go straight to getting in touch with us.

### Our work

Following on from the 'Services' page, I thought the 'Our Work' page next would be appropriate due to if customers
liked the look of the services we offer then they would like to see our previous work. As we are a new business and
haven't completed many jobs, I only had a few images to use. I decided to use a carousel to display the images
because that way the images can be large, as opposed to having multiple images displayed on one page. I had blank
white space either side of the carousel so I thought a good idea would be to display reviews from previous customers,
not only to fill the blank space but it linked in to the features of the page.

### Contact

The last page, quite traditionally is the 'Contact' page. My design before I set out to make the website always
involved having an enquiry form and a map of where we are located as a visual representation. The enquiry form
involves the customer inputting their email address, a section to select what service they require and a text box
for them to write any additional information they wish to add. Prior to creating this page I knew how to create a
form and I presumed it would be easy to link the submit button to our business email address. Unfortunately, upon
researching on how to achieve this, it seems to involve JavaScript and learning quite a lot of this language. Going
forward I would like to make the submit button send an email to the company email address with the information from
the enquiry form.

## Technologies Used

* HTML 5: Used to create the website
* CSS 3: Used to style the wesite
* [Bootstrap v4.4.1](https://getbootstrap.com/): Used for CSS shortcuts, Carousel, Form, etc.
* [Google Fonts](https://fonts.google.com/): Used to change from default Fonts
* [Font Awesome](https://fontawesome.com/): Used to create icons
* [Google Maps](https://www.google.co.uk/maps/): Used to create map for contact page.
* Windows Photo Editor: Used to change size of images to suit website

## Testing

To test the functionality and how my website looked on varying scren sizes/devices I used Chrome Developer tools
throughout the project. There were plenty of challenges along the way with how making sure my website was acceptable
and fit for purpose on different screen sizes. Starting at the top, my navbar included icons on larger screens but
became too cramped on smaller screens so used media queries to hide them when the screen went below a certain width. 
I could've made a burger style navbar but preferred the horizontal look throughout the whole site. Whilst testing, I also
noticed that my 'Services' page did not suit smaller devices by having the passage of writing and image next to it, as
the screen width is too narrow on smaller devices. The images aren't a neccessity so I hid the images when on smaller
devices using the built in bootstrap col rules, e.g col-3 d-none d-lg-block to only show image on large devices. Again,
on the 'Our Work' page, the quotes along either side of the carousel work nicely on larger screens but became too
elongated on smaller devices so they become hidden on smaller devices. The quotes were mostly to fill the white space
either side of the bootstrap carousel which is the main purpose of the page, to show images of previous work. Lastly,
on the 'Contact' page, it is displayed in a simple 50/50 split vertically, with enquiry form on the left and interactive
map on the right, this works perfectly fine and is responsive all the way up to mobile devices where they then cascade,
one underneath each other which works very well on mobile. All other areas of the website are automatically reponsive,
including images and text so only a few media queries have been needed. 

There are not too many areas of the website where the user has to interact with the page to achieve something, but where
there is a user interaction I have tested it by using the following steps:

* Header Image is a link that will take the user back to the home page.
  1. Go to 'Services' page, click on header image, takes you back to 'Home'
  2. Go to 'Our Work' page, click on header image, takes you back to 'Home'
  3. Go to 'Contact' page, click on header image, takes you back to 'Home'

* Check buttons on home page direct to correct page.
  1. Go to 'Home' page, scroll down to the 'Our Services' button, click on button and takes to 'Services' page.
  2. Go to 'Home' page, scroll down to the 'Contact Us' button, click on button and takes to 'Contact' page.

* Ensure that the email link in the footer opens up option to email the company
  1. Go to all pages and scroll down to the footer section, click on email address link, opens up option to email company.

* Check that all social media icons in the footer link to relevant/correct social media pages and opens in new browser tab.
  1. Go to all pages and scroll down to the footer section, click on Facebook icon, opens up correct Facebook page in new tab
  2. Go to all pages and scroll down to the footer section, click on Twitter icon, opens up correct Twitter page in new tab
  3. Go to all pages and scroll down to the footer section, click on Instagram icon, opens up correct Instagram page in new tab
  4. Go to all pages and scroll down to the footer section, click on YouTube icon, opens up correct YouTube page in new tab

* Check button on 'Services' page directs to 'Contact' page
  1. Go to 'Services' page
  2. Click on the 'Contact Us' button, takes you to 'Contact' page

* Ensure Bootstrap Carousel
  1. Go to 'Our Work' page
  2. Use arrows on Bootstrap Carousel to go through all images making sure they appear correctly.
  3. Watch the carousel cycle through images automatically, ensuring all images feature correctly.

* Interactive Map
  1. Go to 'Contact' page
  2. Click and drag on the map to check it can be interacted with
  3. Use the -/+ buttoms on the map to check minimise and maximise works
  4. Ensure the pin on the map is correctly located for the company's location.

* Enquiry From
  1. Submit button ideally would send the information in the form to the company in the form of an email.
  2. Details do not submit as code to do this is unknown as yet.

Other testing tools used included: https://www.browserstack.com/ to test how my site looked and worked on different internet
browsers such as Google Chrome, Mozilla Firefox, Internet Explorer, etc.

## Deployment

The code for this website was written using GitPod and deployed to GitHub pages. The way this was achieved was by
using the following commands; when a section of the site was completed/edited I would add this to GitHub by using the
command git add followed by the files I wanted to add. I would then commit this add by using the command git commit -m
followed by a message of what I am exactly adding, whether it be an edit to a sectiion or a finalised section of code.
The final stage is to then use the command git push which completes the deployment process and adds the work to the master
branch. To create the URL I then went ino the settings on my repository and went to GitHub pages section,
and chose the GitHub pages site to be built from the Master Branch. To run the code locally for example on GitPod, use 
the following command in the terminal:

python3 -m http.server

For other IDEs, pease refer to their help section on how to run.

## Credits

### Content

* All text content in the website was written by myself, with no other influences.
* Navigation bar code was obtained from: https://www.w3schools.com/howto/howto_css_navbar_icon.asp
    * I customised the code to suit the website including the styling in CSS
* 

### Media

* The header image (.logo) was obtained from: https://hertfordshire-focus.co.uk/
* The Home page banner image was obtained from: https://www.alarm-supplies.co.uk/
* CCTV Camera image was obtained from: https://images.app.goo.gl/qUvqHeTfy25Ump7KA
* Alarm panel image was obtained from: https://images.app.goo.gl/pBh5zbXe4dxhoA6c9
* Access Control image was obtained from: https://images.app.goo.gl/Eg3mE9YLwWM61FU97
* Fire Alarm image was obtained from: https://images.app.goo.gl/AdAGorrB53ZmSitQ7

## Acknowledgements 

* I received inspiration for this project from the Code Institute tutorial videos. I liked the idea of
having the Header and Footer the same for each webpage, taught on the videos. Linking to the footer element,
again, inspiration from the tutorial videos on the layout and sectioning of the footer which I really liked 
the design of and thought would suit my website.
* I researched local competitors for inspiration on content/layout from: https://www.shebangsecurity.co.uk/
* I used https://www.browserstack.com/ to test how site looked on different Internet Browsers
# Portfolio - Vanessa Nimmo

[Live website](https://vanessanimmo.github.io/)

[GitHub Repository](https://github.com/VanessaNimmo/portfolio)

[The Website](#the-website)

[The Design](#the-design)

[The Process](#the-process)

[Short Answer Q&A](#short-answer-q&a)

# The Website
## Purpose

This website is intended to represent me and develop my reputation in the tech industry in the long term.

## Functionality / features

My portfolio website is a one-page scrolling website with the following features:

- Pictures of me looking friendly
- Short bio which introduces my interests, both professional and personal, and invites people to get in touch
- Skills list, including all the technologies covered by the end of the CA course
- Portfolio with links to projects I have created
- Blog page with a link to the tech-related blog I run with co-author King, as well as links to several articles on the blog written solely by me
- Contact form through which people can reach me, which emails their information and message to me

## Sitemap

As a one-page site, a sitemap is not necessary.

## Screenshots

**Very small screen navigation**

![Small screen navigation](docs/navigation-tiny-screen.png)

**Mobile Site**

![Mobile site](docs/mobile-website.png)

**Tablet Site**

![Tablet site](docs/tablet-website.png)

**Desktop Site**

![Desktop site](docs/desktop-website.png)

## Target Audience

The usual audience for a professional profile is employers and recruiters. Knowing that I have a job at MYOB directly after the CA course impacted my design decisions and encouraged me to think longer-term. I've considered the target audience for this website to be my existing employer (for understanding what internal roles I might suit) and also MeetUp and Conference organisers, who are often other developers.

At the end of this assignment I feel that the basic design is strong and suits me, and so will be relevant for some time to come. There are, however, many small tweaks I wish to make before the end of the CA course.

## Tech stack (e.g. html, css, deployment platform, etc)

The site is built using html and css. It is hosted on Github Pages, which desploys continuosly from the GitHup Repository, with each push triggering a build.

# The Design
## Inspiration

Begun by gathering together images I liked on Pinterest. I'm into maths and nature, so focussed on these areas looking for common themes.

[Pinterest Board](https://pin.it/o2zl7vze7ca2xa)

![Section of Pinterest Board](docs/pinterest-section.png)

Also spent time looking at websites with 'design eyes' on. What did I like about the websites I use every day? How were they fit for purpose? How were they not? And what have other developers used for their portfolios?

Chose a colour palette with the help of coolors.co: [Colour Palette](https://coolors.co/55cea7-fffeff-fffdf7-0a2342-f0f7ee)

![Colour Palette](docs/colour-palette.png)

## Wireframes

All wireframes for the project can be found in [this Figma file](https://www.figma.com/file/ND9mk1S2PJvtuXOZ18vqxJja/portfolio?node-id=0%3A1). Here are some screenshots of the relevant final designs.

A few changes were made over the course of the design as a result of how the pages looked once they were built.

Mobile Design

![First half of mobile design](docs/phone-design-1.png)
![Second half of mobile design](docs/phone-design-2.png)

Tablet Design

![Tablet design](docs/ipad-design.png)

Desktop Design

![Desktop design](docs/laptop-design.png)

## Usability considerations

HTML Markup: aimed to choose the most appropriate tags for each element to aid screen readers in navigating the site.

Colours: used to colours to ensure high contrast ratios for all text.

Font choices: as well as using clean sans serif fonts to aid in readability, I set font size using points in the body, and then using ems for the rest of the site. This means that even on screens with high pixel density the font won't get too small. Font is also smaller for mobile devices, as they are generally held closer to the user.

Responsive design: checked many sizes to choose suitable break-points for this particular design. Due to the flowing nature of the background image the background svg had to change for different screen sizes to keep the same feeling.

# The Process
## Project plan & timeline

**Pre-work**

Before receiving the assignment information on Canvas, we knew we were creating a personal portfolio website. Knowing that I'm fairly confident with code but far less confident with design, I spent my time on populating a Pinterest board with images that I connected with and investigating what other developers had done for their websites. There are also awards for well-designed websites, so I looked at websites that had recently won in order to see what was possible.

**Monday**

Worked on content - biography, skills, portfolio, blog and pictures.

**Tuesday**

Finalise design and colour choices and finish wireframing in Figma. Set up project resources (e.g. GitHub, Trello, README, file system as described in Canvas).

**Wednesday**

Get final approval for website design. Begin coding with plain HTML, focussing on using appropriate tags for content to make the site accessible to screen readers. Set up Netlify deployment.

NB: Netlify deployment didn't work, and discovered github.io, so went with that as it was very doable in a short amount of time.

**Thursday**

Finish coding the static webpage.

NB: Had finished mobile design but not tablet and desktop.

**Friday**

Write presentation. Play with CSS animation.

NB: Ended up working over the weekend to finish the three designs and have time to play a little with animation. I would like to play a lot more with css animations.

**Monday**

Presentation

## Screenshots of Trello board(s)

Trello board at setup:

![Starting Trello board](docs/trello-board-start.png)

Trello board Wednesday afternoon: 

![Wednesday afternoon board](docs/trello-wed-afternoon.png)

Trello board Friday afternoon:

![Friday afternoon board](docs/trello-Friday-afternoon.png)

Trello board Sunday afternoon:

![Sunday afternoon board](docs/trello-board-Sunday-afternoon.png)

# Short Answer Q&A 

*Describe key events in the development of the internet from the 1980s to today (max. 150 words)*

The work of Vint Cerf and co. in creating the first internetwork protocol (TCP/IP) in the 1970s laid the path for the joining of existing computer networks into one vast network. On January 1st, 1983, the ARPANET (a computer network of US educational and government institutions) switched to this new protocol and became the core of what is now the internet, using IPv4 for addressing.

In the 1980s Tim Berners-Lee proposed the information management system on which the internet is based (HTTP) and did the first successful HTTP communication in March 1989 – this breakthrough allowed the web to scale.

Commercial internet providers begun in the late 80s and took off in the 90s. It became clear that we were going to run out of IP addresses. An updated standard was created – IPv6. In January of 2011 we ran out of addresses in IPv4, and the migration to IPv6 is ongoing.

*Define and describe the relationship between fundamental aspects of the internet such as: domains, web servers, DNS, and web browsers (max. 150 words)*

The location of files or resources on the internet is addressed using the Domain Name System (DNS). Rather than requiring humans to remember the IP addresses used by routers, the DNS uses text-based addressing, which is converted as it moves down the layers of the network. Routers are the traffic directors of the internet, forwarding network traffic along on its journey – an HTTP request will go through many routers on the way to and from the server. When you put a website into the address bar, the browser sends an HTTP request to the relevant web server (found using the DNS tree). The server receives and interprets the request, finds the files it has that you asked for, and sends them back to your browser. The web browser interprets the files sent by the server, be they HTML, CSS, jpg, etc., and renders the web page on your screen.

*Reflect on one aspect of the development of internet technologies and how it has contributed to the world today (max. 150 words)*

Right from its inception the internet was intended to be an open protocol, and the information about how to communicate on it was always freely available. The development of Wi-Fi, from the first test packet on the ALOHAnet in 1971 to the release of the first version of the 802.11 protocol in 1997, has been a significant part of both opening up the internet and making it even more useful. Wi-Fi allows the internet to be accessible on a much wider variety of devices and therefore by more people, opening up the spread of information and driving the creation of devices that utilize this feature – that we have information on-demand from all over the world in a moment. Anyone with a Wi-Fi enabled device has access to information which previously may have only been in libraries, and can contribute to the collective knowledge stored on the internet.

**References**

Tanenbaum, Andrew S. "Computer Networks" Fourth Edition. Pearson Education Inc. (2003)
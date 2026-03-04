A less formal README, recording considerations about the project, e.g. the development roadmap and design decisions.
============
This kind of document should ideally be started before a line of code/script is written, outlining the project and providing guidance, especially when it's a team effort.
In this case, it is still on-scene early enough.
The purpose of this project is to create a website we can use as a portfolio, showcasing our skills in software development and related fields.
*(As an aside, don't be confused, I often use 'we' when 'I' is meant.)*

Initially we considered hosting the website on a site such as https://nekoweb.org/, but realized that we have the hardware to host a low-traffic website locally.
Also it would be a good exercise in acquiring some new skills. To that end, we plan on setting up a web server using nginx as a Docker container on a Raspberry Pi. 
This server would then be available to the internet (read: employment prospects) via https://www.duckdns.org/. 

The site itself is slated to be simple, version 1 to be very static. As frontend development and especially -design is not my métier, it will be rather function over form.
That means HTML and CSS, less so JavaScript. If we find pertinent reason to use JavaScript, we'll ideally use TypeScript, simply because we prefer knowing the type of our data.

Anything in this roadmap may be subject to change as we continue to learn as part of this project.

Tasks (not necessarily in order of importance):
- [x] Set up a clean Raspberry Pi machine (bare-metal).
- [x] Install Docker on Pi
- [ ] Set up an nginx Docker container on Pi
- [ ] Create basic 1-page website
- [ ] Host website on the server in our local network
- [ ] Set up safe access to the website from outside the network
At this point it behooves us to shift our focus to other projects, to serve as actual content to be shown off on that site.
Further tasks below will have lower priority than working on those other projects.
- [ ] Expand the website to be more aesthetically pleasing and host more content
- [ ] Clean up codebase and documentation
- [ ] Research about further smart things to do in regards to the website

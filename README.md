# The following are highlights of some of the projects that I am excited to showcase!

## NOTE:
- Below are the descriptions and some screenshots to display what the apps look like and to give a general overview of the design.
- CANtrackv3 also contains AFTER / BEFORE pictures

## CANtrack v3
- Code & Live site are private, no link to demo :|
- Rewritten our SSR CANtrack (v1 / legacy) from brand new in React as an SPA
- Followed Material UI design
- Fully responsive
- Theme, shortcuts, templates and more customizations
- Also setup a brand new rest API on the backend
- Improved load speeds by taking advantage of the new API, along with smart react components
	- i.e. caching, lazy loading and virtualization
	- From 5-30 seconds load time to immediate loads 

#### Dashboard / Case List
![comments](assets/cantrackv3/cases.png)
#### BEFORE in v1 / Legacy
![cases](assets/cantrackv1-legacy/cases.png)

&nbsp;

#### Adding a new comment
![add-new-comment](assets/cantrackv3/add-new-comment.png)
#### BEFORE in v1 / Legacy
![add-new-comment](assets/cantrackv1-legacy/add-new-comment.png)

&nbsp;

#### Case Details
![case-details](assets/cantrackv3/case-details.png)
#### BEFORE in v1 / Legacy
![case-screen](assets/cantrackv1-legacy/case-details.png)

&nbsp;

#### Comment Details
![comment-details](assets/cantrackv3/comment-details.png)
#### BEFORE in v1 / Legacy
![comments](assets/cantrackv1-legacy/comment-details.png)

&nbsp;

#### Scheduler
![scheduler](assets/cantrackv3/scheduler.png)
#### BEFORE in v1 / Legacy
![scheduler](assets/cantrackv1-legacy/scheduler.png)

&nbsp;

#### Attachments
![attachments](assets/cantrackv3/attachments.png)
#### BEFORE in v1 / Legacy
![attachments](assets/cantrackv1-legacy/attachments.png)

&nbsp;

#### Theme & UI Preferences
![preferences-light-mode](assets/cantrackv3/preferences-light-mode.png)

&nbsp;

---

&nbsp;

## slide-scott
- Live at: [git.io/slide-scott](https://numanaral.github.io/slide-scott/)
- Code at: [github.com/numanaral/slide-scott](https://github.com/numanaral/slide-scott)
- Project built in CPSC 405 / ENTI 415 course
- First place winner in the end term pitch competition (industry voters)
- Single-handedly built the core project along with "good to have" features under 10 days
	- Team quit on me so had to build it myself
- Real time presentation
	- Cursor, drawings, slides and updates are shared with students in real time
- Interactive components
	- Can answer MC questions, have pop quizzes and collect data for analytics
- ...more
#### Landing
![landing](assets/slide-scott/landing-page.png)
#### First Place Winner
![first-place](assets/slide-scott/first-place.jpg)
#### Profile
![profile](assets/slide-scott/gifs/profile.gif)
#### Dashboard Page
![dashboard](assets/slide-scott/dashboard-page.png)
#### Slide Creator
![slide-creator](assets/slide-scott/gifs/slide-creator.gif)
#### Synchronous Mode / Present (real-time updates)
![synchronous-mode](assets/slide-scott/gifs/synchronous-mode.gif)
#### Asynchronous Mode (real-time updates)
![asynchronous-mode](assets/slide-scott/gifs/asynchronous-mode.gif)
#### Analytics
![analytics](assets/slide-scott/analytics-page.png)
#### Resources
![resources](assets/slide-scott/resources-page.png)

&nbsp;

---

&nbsp;

## bomba-man (Work In Progress)
- Live at: [git.io/bomba-man](https://numanaral.github.io/bomba-man/)
- Code at: [github.com/numanaral/bomba-man](https://github.com/numanaral/bomba-man)
- Fun side project
- Built purely with web without using WebGL or any game library/framework
- Online/Local multi-player
- Configurable game mode
- NPC *(Shoutout to @Pujan Bhatta)*
- Game API built based on factory pattern
	- Any provider can easily extend and create a wrapper following the factory
		- redux (local) and firebase (online) are the two providers as of now
		- Chose firebase for easy setup + easy auth, but a node server with socket.io is what I plan to implement in the future. I didn't want to deploy a server just yet and just get it up and running, firebase can be integrated on a static app so it's perfect to get the ground up.
#### Landing Page
![landing page](assets/bomba-man/gifs/landing.gif)
#### Game Screen
![local-game](assets/bomba-man/gifs/local-game.gif)
#### Experimental 3D (via perspective)
![experimental](assets/bomba-man/gifs/experimental.gif)
#### Room Creator
![room-creator](assets/bomba-man/room-creator.png)
#### Waiting Room For Online Multi-Player
![waiting-room](assets/bomba-man/gifs/waiting-room-and-join-game.gif)
#### End Game
![game-end](assets/bomba-man/gifs/game-end.gif)
#### Instructions
![instructions](assets/bomba-man/gifs/instructions.gif)

&nbsp;

---

&nbsp;

## chin-scraper
- Live at: [git.io/chin-scraper](https://numanaral.github.io/chin-scraper/)
- Frontend Code at: [github.com/numanaral/chin-scraper](https://github.com/numanaral/chin-scraper)
- Backend Code at: [github.com/numanaral/chin-scraper-backend](https://github.com/numanaral/chin-scraper-backend)
- Another side project, built for helping me and other students learn / practice writing Hanzi (Chinese characters)
- [Details](https://github.com/numanaral/chin-scraper#pages--modules)
- [Why create this?](https://github.com/numanaral/chin-scraper#why-create-this)
#### Landing Page
![landing-page](assets/chin-scraper/landing-page.png)
#### Learn Page
![learn-page](assets/chin-scraper/learn-page.png)
#### Analytics
![analytics](assets/chin-scraper/analytics.png)

&nbsp;

---

&nbsp;

## Meng Wei Portfolio
- Live at: [mengwei.ca](https://mengwei.ca/)
- A portfolio site
- Wrote a script to parse images and generate a json map that contains
	- LQIP (Low Quality Image Placeholder) version
	- Caption fetched from the files
- LQIP ensures fast load time along with perfectly matching loading placeholders
- Also gives a nice "blur-effect" on full-screen gallery without using "filter: blur()" and creating a workaround
#### Landing Page
![landing-page](assets/meng-wei-portfolio/landing-page.png)
#### Photojournalism Page w/ Gallery
![photojournalism](assets/meng-wei-portfolio/photojournalism.png)
#### Lazy Loading on Gallery
![lazy-loading](assets/meng-wei-portfolio/lazy-loading.png)
#### LQIP blur-effect on Full-Screen Gallery
![lazy-loading-with-lqip](assets/meng-wei-portfolio/lazy-loading-with-lqip.png)
+++
project_id = "B5"
title = "Nexum"
subtitle = "Free, anonymous interaction for talks and classes"

claim = "An open, easy-to-use platform for live Q&A, polls, and audience engagement in talks or lectures."

abstract = "Nexum is a lightweight audience engagement platform that supports live polls and Q&A features – designed to be anonymous, easy to use, responsive, and entirely browser-based."

card_image = "images/logo.webp"

team = ["Vu Duc Le", "Andrey Krasavin", "Daria Myronova", "Júlia Vieira de Souza", "Mariia Manzon", "Charlotte John"]
supervisor = "Prof. Dr. Gefei Zhang"

draft = false

source_link = "https://gitlab.htw-berlin.de/s0592097/weslido"
website_link = "http://nexum.f4.htw-berlin.de/home"
+++


{{<section title="Our Goal">}}

Our project is inspired by Slido, a popular platform that adds low-threshold interactive elements like Q&A, polls, rankings, and ratings to presentations, making it easy for speakers to engage their audience. In contrast, nexum is more focused on providing a smaller feature set which is essential to interactive presentations, without subscription barriers.

Our project is inspired by Slido but focuses on providing a smaller, free alternative with the core features needed for live interaction. The goal was to build a simple, easy to access tool that supports anonymous participation and real-time feedback, particularly to help improve teaching and presentations without subscription barriers.

The goal was to build a simple, easy to access tool that supports anonymous participation and real-time feedback, particularly to help improving teaching and presentations without subscription barriers.

* **What we wanted to solve**

Many existing tools either come with a steep learning curve or require subscriptions for key features. We wanted to create a straightforward, easy-to-use solution that allows everybody to participate in interactions, without cumbersome hurdles like registration or sign in. 

{{</section>}}


{{<section title="Process">}}

We began the project by defining core features based on user stories. From there, we followed a lightweight Scrum-inspired process: weekly meetings with our supervisor, regular team check-ins, and a shared GitHub backlog to track progress.

Initially, roles were informal, but after about two weeks we defined responsibilities, which helped the team work more efficiently. Most development happened on feature branches in GitLab, with regular communication via chat and short calls. Merge conflicts and integration were addressed in the dedicated weekly team meetings. Code reviews weren’t formalized but happened organically as part of pair debugging or through Assignees for merge requests during integration.

After deploying the web app on a server, we tested it as a team and gathered usability feedback from each other and Prof. Zhang, leading to several improvements.

For a more detailed description of our process click [here](process). 

{{</section>}}

{{<section title="Outcome">}}

The result is a working web app called *Nexum*. 

{{<image src="images/homepage.webp" alt="Our Homepage">}}
{{<image src="images/session.webp" alt="An example how a session can look">}}

It’s a compact tool that offers:

- Live Q&A   
- Multiple-choice polls  
- WordClouds    
- Open text input  
- Rating and ranking polls  
- Image polls
  <br></br>
- Reusable templates for polls
- Session analytics for deeper insights

Click [here](outcome) for images and some details.
{{</section>}}


{{<section title="Team">}}

**Vu Duc Le**
Backend development and some frontend tasks  

**Andrey Krasavin**
Lead frontend developer 

**Daria Myronova**
UI/UX design and testing

**Júlia Vieira de Souza**
UI/UX design and frontend feedback

**Mariia Manzon**
UI/UX design and frontend feedback

**Charlotte John**
Team coordination, backend development, server setup and some frontend tasks

{{<gallery>}}
{{<team-member image="images/team/vu.webp" name="Vu Duc Le">}}
{{<team-member image="images/team/andrey.webp"  name="Andrey Krasavin">}}
{{<team-member image="images/team/daria.webp"  name="Daria Myronova">}}
{{<team-member image="images/team/julia.webp"  name="Júlia Vieira de Souza">}}
{{<team-member image="images/team/mariia.webp"  name="Mariia Manzon">}}
{{<team-member image="images/team/charlotte.webp"  name="Charlotte John">}}
{{</gallery>}}

{{</section>}} 



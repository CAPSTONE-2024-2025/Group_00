## Developers
| Name        |   Role |     Github    | Email       |
| ----------- | --------- | --------- | --------------------------- |
| Marcel Jar  | Back-End Dev | marceljar | marcel.jar@senecapolytechnic.ca |
| Tony Stark  | Front-End Dev |tonystark | tony.stark@senecapolytechnic.ca |
| Bruce Banner  | Database Specialist | brucebanner | bruce.banner@senecapolytechnic.ca |

## Project Description
In this project, a website tailored for faculty members at a college setting is developed. This website will feature tools to aid faculty during the process of delivering these courses. The most important tools are: web pages for individual courses, a setup for delivering slide presentations, and a timeslot picking tool for meetings with groups. These tools are presented in more details in what follows:

### Individual Courses Web Pages
Each course delivered by the faculty should have its own web page. On this web page, the faculty should be able to display basic information about the course, such as a description, the evaluation criteria, and the calendar. This web page should also serve as a gateway for students to access slide presentations for the course, as well as to access the timeslot-picking tool for courses with group meetings.

### Slide Presentations
All slide presentations delivered throughout the course should be stored and viewed directly on the website. The slides should be integrated into the course calendar and utilize web technologies instead of relying on presentation software such as PowerPoint or PDF files. Furthermore, these slides should be responsive to different screen sizes.

### Timeslot Picking Tool
This tool will allow faculty members to create meeting timeslots available for groups of students. After the timeslots are created, students should be able to pick the preferred timeslots for their groups. This tool should also send a message to all group members with details about the chosen timeslots. Note that the tool does not have an option to allow students to change their chosen option. This is done by design. The idea is to prevent students from picking a timeslot as a placeholder first, and then discussing timeslots with other teammates later.

## Tech Stack

### Backend

The website is served by an [Nginx](https://nginx.org/en/) reverse proxy running on an Ubuntu 24.04 OS, hosted by [DigitalOcean](https://www.digitalocean.com/). Its backend runs on [Node.js](https://nodejs.org/en) and uses the [Express.js](https://expressjs.com/) network to process HTTP requests. 

### Frontend

In its frontend, the website uses [Bootstrap 5.3.3](https://getbootstrap.com/docs/5.3/getting-started/introduction/)  as a CSS framework to create a responsive experience. Slides are created using the [Reveal](https://revealjs.com/) presentation library. No other front-end frameworks or JavaScript libraries are used.

### Developing Tools

This website was developed using [Visual Studio Code](https://code.visualstudio.com/) with a number of extensions. [Postman](https://www.postman.com/) was used to test HTTP requests in order to decouple back-end and front-end tasks.



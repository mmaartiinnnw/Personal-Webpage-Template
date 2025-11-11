# My Personal Portfolio (DAW Student)

This repository holds the source code for my personal portfolio website. I built this as a static, single-page site to showcase my skills, projects, and experience as a junior web developer and a 2nd-year "Desarrollo de Aplicaciones Web" (DAW) student.

## 🚀 Key Features

* **Single-Page Design**: Smooth navigation between sections (Home, About Me, Projects, Skills, Contact) without page reloads.
* **Responsive Design**: Fully adaptable to mobile, tablet, and desktop screens, built using CSS Flexbox, Grid, and Media Queries.
* **"About Me" Section**: A professional introduction featuring my photo (`yo.jpg`).
* **"Projects" Gallery**: A showcase of my work using a card-based layout (featuring my Pokémon, Bundesliga, and Movie projects), with each card linking directly to its GitHub repository.
* **Animated "Skills"**: A tech stack section with progress bars that dynamically animate on scroll. I achieved this using JavaScript's `IntersectionObserver`.
* **Functional Contact Form**: A working contact form integrated with the `FormSubmit` service.
* **Downloadable CV**: A direct link to download my curriculum vitae (`DIego Martín GArcía (3).pdf`).

## 💻 Tech Stack

I built this project purely with fundamental front-end technologies:

* **HTML5**: For the semantic structure of the content.
* **CSS3**: For all visual styling, layout, and responsiveness.
    * Heavy use of **CSS Variables** (check out `--c-principal` for the neon theme).
    * **Flexbox** and **Grid** for the layout.
    * **Media Queries** for the adaptive design.
* **Vanilla JavaScript**: I used this for interactivity, specifically to detect when the "Skills" section is visible and then trigger the progress bar animations.
* **Font Awesome**: For the social icons (GitHub, LinkedIn, Email).
* **Google Fonts**: For the typography (Montserrat and Open Sans).

## 🛠️ Usage and Installation

This is a static project, so it doesn't require a build process.

1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  Navigate into the project folder:
    ```bash
    cd your-repo-name
    ```
3.  Open the `index.html` file in your web browser.

> **Recommendation:** For the best experience and to ensure the JavaScript animations (`IntersectionObserver`) work correctly (as some browsers restrict this on `file:///`), I recommend serving the files from a local server.
>
> If you use Visual Studio Code, you can use the [**Live Server**](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension to launch a server with a single click.


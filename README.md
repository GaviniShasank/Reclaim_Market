ReclaimMarket
=============

A simple and clean e-commerce web application designed to showcase and manage products using Node.js, Express, and EJS templates. The project follows a structured MVC pattern and includes SCSS for styling.

* * * * *

Table of Contents
-----------------

-   Overview

-   Features

-   Tech Stack

-   Installation

-   Usage

-   Project Structure

-   Contributing

-   License

* * * * *

Overview
--------

**ReclaimMarket** is a basic e-commerce website template built with Node.js and Express. It uses EJS for server-side rendering and SCSS for modular styles. It's structured using the Model-View-Controller (MVC) approach, making it scalable and maintainable.

You can use this as a foundation for a fully functional online store, marketplace, or product showcase platform.

* * * * *

Features
--------

-   Dynamic product pages with EJS

-   SCSS styling compiled into CSS

-   Organized MVC project structure

-   Responsive and modern UI

-   Static asset management (CSS, fonts, images)

* * * * *

Tech Stack
----------

| Layer | Technologies |
| --- | --- |
| Backend | Node.js, Express.js |
| Templating | EJS |
| Styling | SCSS, CSS |
| Structure | MVC Architecture |
| Assets | FontAwesome, Google Fonts, etc. |

* * * * *

Installation
------------

Clone the repository and install dependencies:

`# Clone the repository

# Rename the folder (optional)
mv amado-master reclaimmarket

# Navigate into the directory
cd reclaimmarket

# Install dependencies
npm install

# Start the development server
npm start`

By default, the app should be available at `http://localhost:3000`.

* * * * *

Usage
-----

Once running:

-   Visit `http://localhost:3000/` to view the home page.

-   Navigate through product listings and other pages.

-   Static assets are served from the `public/` directory.

* * * * *

Project Structure
-----------------
<pre>
reclaimmarket/
├── app.js
├── package.json
├── controllers/
├── models/
├── routes/
├── views/
│   └── [EJS templates]
├── public/
│   ├── css/
│   ├── fonts/
│   ├── images/
│   └── js/
├── scss/
│   └── [SCSS source files]
├── style.css
└── README.md
  </pre>


### Directory Overview

-   **app.js** -- Main server entry point

-   **controllers/** -- Route logic handlers

-   **models/** -- (Optional) Data models or schema definitions

-   **routes/** -- Route definitions

-   **views/** -- EJS templates for rendering pages

-   **public/** -- Static files (CSS, JS, fonts, images)

-   **scss/** -- Raw SCSS files for styling

* * * * *

Contributing
------------

Contributions are welcome! Here's how to get started:

1.  Fork this repository

2.  Create your feature branch: `git checkout -b feature/your-feature`

3.  Commit your changes: `git commit -m "Add your feature"`

4.  Push to the branch: `git push origin feature/your-feature`

5.  Open a Pull Request

# Bootcamp code 

This is a Vite-based project that leverages modern build tools and development servers for a fast and efficient development experience.

## Table of Contents

- [Installation](#installation)
  - [Step 1: Clone the Repository](#step-1-clone-the-repository)
  - [Step 2: Project Structure](#step-2-project-structure)
  - [Step 3: Install Dependencies](#step-3-install-dependencies)
- [Running the Project](#running-the-project)
- [Available Scripts](#available-scripts)
- [Learn More](#learn-more)

## Installation

To get started with this project, you'll need to have [Node.js](https://nodejs.org/) installed on your machine. We recommend using the latest LTS version.

### Step 1: Clone the Repository

First, clone this repository to your local machine using Git:

```bash
git clone https://github.com/your-username/vite-project.git
cd vite-project
``` 

### Step 2: Project structure

```
.
├── index.html
├── js
│   ├── callback
│   ├── promise
│   │   ├── delay-with-a-promise.js
│   │   ├── loadscript.js
│   │   ├── rewrite-with-async.js
│   │   └── whats-the-output.js
│   └── prototypes
│       ├── proto.js
│       ├── searching.js
│       └── where-does-it-write.js
├── main.js
├── package.json
├── package-lock.json
├── public
│   └── vite.svg
├── README.md
└── style.css
```

The ```main.js``` file contains all the js code, in order to include a file just uncomment the import in main.js
if you want to add a new js file, just add it in the js folder and include it in the ```main.js`` file.


### Step 2: Running the file

install the necessary dependencies using npm or yarn:

```bash
npm install
```

Once the dependencies are installed, you can start the development server:

```bash
npm run dev
```



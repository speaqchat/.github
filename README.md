<div align="center">
  <img src="https://i.imgur.com/AqPZyXR.png" alt="logo" width="full" height="auto" />
  <h1>speaq</h1>
  
  <p>
    Modern chat app built with React, Tauri and Express. 
  </p>
</div>

<br />

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Tech Stack](#space_invader-tech-stack)
  * [Features](#dart-features)
<!--   * [Environment Variables](#key-environment-variables) -->
- [Getting Started](#toolbox-getting-started)
  * [Prerequisites](#bangbang-prerequisites)
  * [Installation](#gear-installation)
  * [Run Locally](#running-run-locally)
<!-- - [Roadmap](#compass-roadmap) -->
- [Contact](#handshake-contact)

<!-- About the Project -->
## :star2: About the Project

<div align="center"> 
  <img src="https://i.imgur.com/oCHcTG1.png" alt="screenshot" />
</div>


<!-- TechStack -->
### :space_invader: Tech Stack

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://www.typescriptlang.org/">Typescript</a></li>
    <li><a href="https://reactjs.org/">React</a></li>
    <li><a href="https://tailwindcss.com/">TailwindCSS</a></li>
    <li><a href="https://tauri.studio/">Tauri</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://www.typescriptlang.org/">Typescript</a></li>
    <li><a href="https://expressjs.com/">Express.js</a></li>
    <li><a href="https://socket.io/">Socket.IO</a></li>
    <li><a href="https://www.prisma.io/">Prisma</a></li>    
    <li><a href="https://github.com/auth0/node-jsonwebtoken">jsonwebtoken</a></li>    
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

### :dart: Features

- [x] User and auth implementation.
- [ ] Realtime chat using Socket.IO.

<!-- Env Variables -->
<!-- ### :key: Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

`ANOTHER_API_KEY` -->

<!-- Getting Started -->
## 	:toolbox: Getting Started

### :bangbang: Prerequisites

This project uses Yarn as the package manager.
You must also have [Tauri and its dependencies](https://tauri.studio/v1/guides/getting-started/prerequisites#installing) installed.

### :running: Run Locally

Clone the project

```bash
  git clone https://github.com/franciscosilva00/speaq
```

Go to the project directory

```bash
  cd speaq/
```

Install dependencies

```bash
  yarn
```

Start the dev server

```bash
  yarn tauri dev
```

This project is distributed under the MIT License.

<!-- Contact -->
## :handshake: Contact

Francisco Silva - 000franciscosilva000@gmail.com | 190309@epvc.pt

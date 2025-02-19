# DayTranquil

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#screenshots">Screenshots</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

DayTranquil is an application designed to manage daily notes and shopping lists with premium features.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![React][React.js]][React-url]
* [![Vite][Vite.js]][Vite-url]
* [![TypeScript][TypeScript]][TypeScript-url]
* [![Java][Java]][Java-url]
* [![Spring Boot][Spring-Boot]][Spring-Boot-url]
* [![Docker][Docker]][Docker-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* Java 21
* Maven
* Docker
* Node.js

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/DayTranquil.git
    cd DayTranquil
    ```

2. Build the Docker images and start the containers:
    ```bash
    docker-compose up --build
    ```

3. Set environment variables for your database and API keys in the `DayTranquil/tree/main/backend/src/main/resources/application.properties` file:
    ```env
    DB_NAME=yourdbname
    DB_USERNAME=yourdbuser
    DB_PASSWORD=yourdbpassword
    DB_URL=jdbc:postgresql://db:5432/yourdbname
    SECRET_KEY=yourjwtsecret
    ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- SCREENSHOTS -->
## Screenshots

![Screenshot 1](https://github.com/sabligeri/DailyEase/blob/main/images/%20signup.png)
![Screenshot 3](https://github.com/sabligeri/DailyEase/blob/main/images/cappuccino.png)
![Screenshot 5](https://github.com/sabligeri/DailyEase/blob/main/images/note.png)
![Screenshot 6](https://github.com/sabligeri/DailyEase/blob/main/images/premium.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Gergely Sábli - [LinkedIn](https://www.linkedin.com/in/gergely-s%C3%A1bli-357110293/) - sabligergo@gmail.com

Project Link: [https://github.com/sabligeri/dailyease](https://github.com/sabligeri/dailyease)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

### Contributors
* [Gergő Korodi](https://github.com/korodigergo)
* [Kekalma](https://github.com/Kekalma)
* [Francisco Kpodotay](https://github.com/francisco-kpodotay)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/your-username/dailyease.svg?style=for-the-badge
[contributors-url]: https://github.com/your-username/dailyease/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/your-username/dailyease.svg?style=for-the-badge
[forks-url]: https://github.com/your-username/dailyease/network/members
[stars-shield]: https://img.shields.io/github/stars/your-username/dailyease.svg?style=for-the-badge
[stars-url]: https://github.com/your-username/dailyease/stargazers
[issues-shield]: https://img.shields.io/github/issues/your-username/dailyease.svg?style=for-the-badge
[issues-url]: https://github.com/your-username/dailyease/issues
[license-shield]: https://img.shields.io/github/license/your-username/dailyease.svg?style=for-the-badge
[license-url]: https://github.com/your-username/dailyease/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/gergely-sábli-357110293
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vite.js]: https://img.shields.io/badge/Vite-2B8DBD?style=for-the-badge&logo=vite&logoColor=FFFFFF
[Vite-url]: https://vitejs.dev/
[TypeScript]: https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white
[TypeScript-url]: https://www.typescriptlang.org/
[Java]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white
[Java-url]: https://www.java.com
[Spring-Boot]: https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white
[Spring-Boot-url]: https://spring.io/projects/spring-boot
[Docker]: https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white
[Docker-url]: https://www.docker.com

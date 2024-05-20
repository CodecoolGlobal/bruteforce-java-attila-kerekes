<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/CodecoolGlobal/bruteforce-java-attila-kerekes">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h1 align="center">Brute Force Password Breaker</h1>

  <p align="center">
    <br />
    <a href="https://github.com/CodecoolGlobal/bruteforce-java-attila-kerekes"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/CodecoolGlobal/bruteforce-java-attila-kerekes/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/CodecoolGlobal/bruteforce-java-attila-kerekes/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#overview">Overview</a>
    </li>
    <li>
      <a href="#technologies">Technologies</a>
    </li>
    <li>
      <a href="#usage">Usage</a>
    </li>
    <li>
      <a href="#contact">Contact</a>
    </li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

Brute forcing is a method of trying to break a password by systematically checking all possible combinations until the correct one is found. This project aims to experiment with brute force attacks on passwords stored in an SQL database using Java and SQLite.

## Overview

The project contains embedded database files in the resources folder, called Users.db and CrackedUsers.db to store user credentials on each rerun of the program. After setting up a predefined number of users with a predefined maximum password length, the program implements a brute-force password breaker algorithm to crack passwords stored in the database. The application consists of components such as password and user generators, an authentication service, and a password breaker. 

To set the initial values, in the Application.java file modify these values:
```java
int userCount = <num>;
int maxPwLength = <num>;
```

After the program successfully runs, a list of cracked users, their passwords, and the required time in milliseconds is saved in the CrackedUsers.db.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Technologies

* [![Java][Java]][Java-url]  Java 21
* [![Maven][Maven]][Maven-url]  Dependency management and build tool.
* [![SQLite][SQLite]][SQLite-url]  Serverless database for storing user credentials (Or any similar technology for visualizing .db files)
* JUnit: Unit testing framework for Java.
* DB Browser for SQLite: GUI application for inspecting and managing SQLite databases.

## Usage

1. Clone the repository:
git clone <repository-url>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

  <!-- CONTACT -->
## Contact

Attila Kerekes - attila.g.kerekes@gmail.com

Project Link: [https://github.com/CodecoolGlobal/bruteforce-java-attila-kerekes](https://github.com/CodecoolGlobal/bruteforce-java-attila-kerekes)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/CodecoolGlobal/bruteforce-java-attila-kerekes.svg?style=for-the-badge
[contributors-url]: https://github.com/CodecoolGlobal/bruteforce-java-attila-kerekes/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/CodecoolGlobal/bruteforce-java-attila-kerekes.svg?style=for-the-badge
[forks-url]: https://github.com/CodecoolGlobal/bruteforce-java-attila-kerekes/network/members
[stars-shield]: https://img.shields.io/github/stars/CodecoolGlobal/bruteforce-java-attila-kerekes.svg?style=for-the-badge
[stars-url]: https://github.com/CodecoolGlobal/bruteforce-java-attila-kerekes/stargazers
[issues-shield]: https://img.shields.io/github/issues/CodecoolGlobal/bruteforce-java-attila-kerekes.svg?style=for-the-badge
[issues-url]: https://github.com/CodecoolGlobal/bruteforce-java-attila-kerekes/issues
[license-shield]: https://img.shields.io/github/license/CodecoolGlobal/bruteforce-java-attila-kerekes.svg?style=for-the-badge
[license-url]: https://github.com/CodecoolGlobal/bruteforce-java-attila-kerekes/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/attila-g-kerekes/

[Java]: https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white
[Java-url]: https://www.oracle.com/java/
[Maven]: https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white
[Maven-url]: https://maven.apache.org/
[SQLite]: https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white
[SQLite-url]: https://www.sqlite.org/

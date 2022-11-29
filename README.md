[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="https://t3.ftcdn.net/jpg/03/13/32/16/360_F_313321649_Sz7LZHKenwRtu3rFDbuyO28oJ7udepXw.jpg" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Realtime Chat App</h3>

  <p align="center">
    Realtime chat app is an application that allows you to communicate with the person or people in front of you in real time. You can create a room in the application and communicate with your friends in the relevant room. You can also sign up for an existing room and read previous messages.
    <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a>
    <br />
  </p>
</div>



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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

The project was implemented with python's 'Django' framework. 'SQLite' embedded in django is used as database. The 'Dockerfile' of the project has been written so that the project can be tested more easily by other users. In the project, instead of server client architecture, ajax was used to display the messages in real time.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Python][Next.js]][https://upload.wikimedia.org/wikipedia/commons/thumb/0/0a/Python.svg/1200px-Python.svg.png]
* [![Django][Next.js]][https://w7.pngwing.com/pngs/159/366/png-transparent-django-python-computer-icons-logo-python-text-label-rectangle-thumbnail.png]
* [![SQLite][Next.js]][https://e7.pngegg.com/pngimages/778/255/png-clipart-sqlite-database-android-mysql-android-text-logo-thumbnail.png]
* [![JavaScript][Next.js]][https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/480px-Unofficial_JavaScript_logo_2.svg.png]
* [![Ajax][Next.js]][https://raw.githubusercontent.com/github/explore/8be26d91eb231fec0b8856359979ac09f27173fd/topics/ajax/ajax.png]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

If you have Docker Desktop on your computer, you can test the application with one command!

### Prerequisites

https://docs.docker.com/desktop/install/windows-install/

### Installation

If there is no docker desktop application, you can use the following commands.


1. Clone the repo
   ```sh
   git clone https://github.com/MelihSelamiUrkmezz/Realtime-ChatApp.git
   ```
2. Install Django packages
   ```sh
   pip install -r requirements.txt
   ```
3. Make migrations and migrate 
   ```sh
   python manage.py makemigrations && python manage.py migrate
   ```
4. Run the project
   ```sh
   python manage.py runserver
   ```

If you have docker desktop installed, you can run the project with a single command like this!

docker container run -p 8000:8000 melihselamiurkmez/chatapp:v5

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>





<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>





<!-- CONTACT -->
## Contact

Melih Selami URKMEZ - melih.s.urkmez@gmail.com

Project Link: [https://github.com/MelihSelamiUrkmezz/Realtime-ChatApp](https://github.com/MelihSelamiUrkmezz/Realtime-ChatApp)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[stars-shield]: https://img.shields.io/github/stars/MelihSelamiUrkmezz/Realtime-ChatApp.svg?style=for-the-badge
[stars-url]: https://github.com/MelihSelamiUrkmez/Realtime-ChatApp/stargazers
[issues-url]: https://github.com/MelihSelamiUrkmezz/Realtime-ChatApp/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/MelihSelamiUrkmezz
[product-screenshot]: images/screenshot.png
[Python][Next.js]: https://upload.wikimedia.org/wikipedia/commons/thumb/0/0a/Python.svg/1200px-Python.svg.png
[Django][Next.js]: https://w7.pngwing.com/pngs/159/366/png-transparent-django-python-computer-icons-logo-python-text-label-rectangle-thumbnail.png
[SQLite][Next.js]: https://e7.pngegg.com/pngimages/778/255/png-clipart-sqlite-database-android-mysql-android-text-logo-thumbnail.png
[JavaScript]: https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/480px-Unofficial_JavaScript_logo_2.svg.png
[Ajax]: https://raw.githubusercontent.com/github/explore/8be26d91eb231fec0b8856359979ac09f27173fd/topics/ajax/ajax.png

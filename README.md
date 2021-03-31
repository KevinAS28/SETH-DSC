<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/KevinAS28/SETH-DSC">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">SETH</h3>

  <p align="center">
    Safe Electronic Ticket for Health
    <br />
    <br />
    <br />
    <a href="https://www.youtube.com/watch?v=nMipBSv4ch8">View Demo</a>
  </p>
</p>


  
<!-- TABLE OF CONTENTS -->
<details open="open">
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
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

SETH - Solution Challenge 2021 - Gadjah Mada University - Google Developer Student Club

Components:
* [SETH Server](https://github.com/KevinAS28/SETH-Server)
* [SETH Mobile](https://github.com/delkirawan/SethCMobileApp)
* [Face Recognition Module](https://github.com/KevinAS28/Django-HTTP-Streaming-Face-Recognition)

### Built With

* [Tensorflow](https://www.tensorflow.org/)
* [Flutter](https://flutter.dev/)
* [Google Cloud Platform](https://cloud.google.com/)
* [Python](https://www.python.org/)
* [Django](https://www.djangoproject.com/)


### Prerequisites

* UNIX based system (We haven't test it yet on Windows)
* Wifi network (Allow the port: 80, 81, 8080, 8000)
* Google Cloud Platform API Key: [https://console.cloud.google.com/apis/credentials](https://console.cloud.google.com/apis/credentials) (Make sure you have enabled the GMAPS API)


### Installation

1. Clone the repo [SETH](https://github.com/KevinAS28/SETH-DSC)
   ```sh
   git clone --recurse-submodules -j8 https://github.com/KevinAS28/SETH-DSC
   ```
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```JS
   const API_KEY = 'ENTER YOUR API';
   ```

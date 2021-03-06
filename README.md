<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GPL License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Leo-Thomas/AI-based-red-rose-counting-webapp">
    <img src="Images/logo.png" alt="Logo" width="80" height="100">
  </a>

<h3 align="center">AI rose counting system web application</h3>

  <p align="center">
    Web application that recognizes and counts the number of red roses using an artificial intelligence model.
    <br />
    <a href="https://github.com/Leo-Thomas/AI-Rose-counting-system-web-app"><strong>Explore the docs »</strong></a>
    <br />
    <br />
  </p>
</div>



<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#os-suported">Os Suported</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a>
                    <ul>
        <li><a href="#windows">Windows</a></li>
        <li><a href="#linux">Linux</a></li>
      </ul></li>
        <li><a href="#installation">Installation</a>
            <ul>
        <li><a href="#windows">Windows</a></li>
        <li><a href="#linux">Linux</a></li>
      </ul>
        </li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a>
    <ul>
        <li><a href="#counting-by-uploading-a-file">Uploading a file</a></li>
        <li><a href="#counting-using-the-camera">Using the camera</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

This is a web application that recognizes and counts the number of red roses using artificial intelligence. The user can upload an image or take a picture with the camera. Once the image is processed, the application will display on screen the number of roses found and the average accuracy. The user can also download the resulting image, or generate and download a report.

This web application was developed by Leo, Mike, Carlos and Juan, students at Yachay Tech University.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [HTML](https://html.spec.whatwg.org/multipage/)
* [CSS](https://www.w3.org/Style/CSS/Overview.en.html)
* [JavaScript](https://www.javascript.com/)
* [Python](https://www.python.org/)
* [Django](https://www.djangoproject.com/)
* [Bootstrap](https://getbootstrap.com)
* [TensorFlow](https://www.tensorflow.org/)
* [ReportLab](https://www.reportlab.com/)

### OS Suported

* Microsoft Windows: 10, 11
* Lunix: Ubuntu 20.04

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* Python (3.8.8 recomended)
  
  [Download Python](https://www.python.org/downloads/)


**Important** (_for Windows only_)

   1. Make sure to add Python to path during Python installation

  <img src="Images/P2.png" alt="Logo" width="660" heigh="406">

  2. Make sure to disable path length limit during Python installation

  <img src="Images/P1.png" alt="Logo" >

#### Windows

* Latest pip
  ```sh
  pip install --upgrade pip
  ```
* Numpy
  ```sh
  pip install numpy
  ```  
* Django
  ```sh
  pip install Django
  ```
* TensorFlow
  ```sh
  pip install tensorflow
  ```
* OpenCV
  ```sh
  pip install opencv-python
  ```
* ReportLab
  ```sh
  pip install reportlab
  ```
* Pillow
  ```sh
  pip install pillow
  ```
  
#### Linux

* Upgrade Repositories
  ```sh
  sudo apt-get upgrade -y
  ```
* Pip for Python3
  ```sh
  sudo apt install python3-pip
  ```
* Upgrade Pip for Python3
  ```sh
  sudo pip3 install --upgrade pip
  ```
* Django
  ```sh
  sudo pip3 install django
  ```
* TensorFlow
  ```sh
  sudo pip3 install tensorflow
  ```
* OpenCV
  ```sh
  sudo pip3 install opencv-python
  ```
* ReportLab
  ```sh
  sudo pip3 install reportlab
  ```
* Pillow
  ```sh
  sudo pip3 install pillow
  ```

### Installation



#### Windows


1. Clone the repo
   ```sh
   git clone https://github.com/Leo-Thomas/AI-based-red-rose-counting-webapp.git
   ```
2. Inside "AI-based-red-rose-counting-webapp" directory, open a terminal and initialize the server
   ```sh
   python manage.py runserver
   ```
3. Open the generated link in the browser
   ```sh
   Starting development server at **http://127.0.0.1:8000/**
   ```
  
<p align="right">(<a href="#top">back to top</a>)</p>
  


#### Linux

1. Clone the repo
  ```sh
  sudo git clone https://github.com/Leo-Thomas/AI-based-red-rose-counting-webapp.git
  ```
2. Inside "AI-based-red-rose-counting-webapp" directory, open a terminal as administrator and initialize the server
  ```sh
  sudo python3 manage.py runserver
  ```
3. Open the generated link in the browser
  ```sh
  Starting development server at **http://127.0.0.1:8000/**
  ```
  
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

### Counting by uploading a file 

* Click the "Choose file" button

<img src="Images/21.png" alt="Logo">

* Select the file you want to process and upload it

<img src="Images/22.png" alt="Logo">

* Once the file is loaded, click the "Count" button to start counting.

<img src="Images/23.png" alt="Logo">

* A waiting screen will be displayed while your image is being processed. (_You can cancel the process at any time by clicking the "Cancel" button._)

<img src="Images/6.png" alt="Logo">

* After a few seconds, the original image will be displayed on the screen together with the image with the rose detection. Also, the number of roses found and the average accuracy will be displayed in the results panel.

<img src="Images/24.png" alt="Logo">

* If you wish, you can download the resulting image by clicking on the "Download Image" button.

<img src="Images/25.png" alt="Logo">


* You can also generate a report of the count by clicking on the "Generate report" button, which will take you to a new window.

<img src="Images/26.png" alt="Logo">


* In the new window, you can download the report by clicking on the "Download report" button.

<img src="Images/27.png" alt="Logo">
<img src="Images/28.png" alt="Logo">

* Finally, you can go to the home page to process another image

<p align="right">(<a href="#top">back to top</a>)</p>

### Counting using the camera

* Click on the "Camera" button

<img src="Images/20.png" alt="Logo">

* Give permissions to access your camera

<img src="Images/2.png" alt="Logo">

* Then, a box with the image of your camera will be displayed.

<img src="Images/3.png" alt="Logo">

* Place the desired image in front of the lens and press the "Shoot" button to capture it. (_You can click the "Shoot" button as many times as you wish until you capture the right image._)

<img src="Images/4.png" alt="Logo">

* Once the image is captured, click on the "Count" button to start counting. 

<img src="Images/5.png" alt="Logo">

* A waiting screen will be displayed while your image is being processed. (_You can cancel the process at any time by clicking the "Cancel" button._)

<img src="Images/6.png" alt="Logo">

* After a few seconds, the original image will be displayed on the screen together with the image with the rose detection. Also, the number of roses found and the average accuracy will be displayed in the results panel.

<img src="Images/7.png" alt="Logo">

* If you wish, you can download the resulting image by clicking on the "Download Image" button.

<img src="Images/8.png" alt="Logo">


* You can also generate a report of the count by clicking on the "Generate report" button, which will take you to a new window.

<img src="Images/10.png" alt="Logo">


* In the new window, you can download the report by clicking on the "Download report" button.

<img src="Images/11.png" alt="Logo">
<img src="Images/12.png" alt="Logo">

* Finally, you can go to the home page to process another image

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Leo Ramos - [LinkedIn](https://www.linkedin.com/in/leo-thomas-ramos/) - leo.ramos@yachaytech.edu.ec

Mike Bermeo - [LinkedIn](https://www.linkedin.com/in/mike-bermeo-1a8869128/) - mike.bermeo@yachaytech.edu.ec

Juan Brito - [LinkedIn](http://www.linkedin.com/in/juan-brito-a93497b9) - juan.brito@yachaytech.edu.ec

Carlos Macancela - [LinkedIn](https://www.linkedin.com/in/leo-thomas-ramos/) - carlos.macancela@yachaytech.edu.ec

<br>
<br>

Project Link: [https://github.com/Leo-Thomas/AI-Rose-counting-system-web-app](https://github.com/Leo-Thomas/AI-based-red-rose-counting-webapp)

<p align="right">(<a href="#top">back to top</a>)</p>




<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [IBM MAX Object Detector](https://github.com/IBM/MAX-Object-Detector-Web-App)
* [TFJS Object Detection](https://github.com/eisbilen/TFJS-ObjectDetection)
* [Piotr Płoński](https://www.deploymachinelearning.com/)
* [Towards Data Science](https://towardsdatascience.com/creating-a-machine-learning-based-web-application-using-django-5444e0053a09)

<p align="right">(<a href="#top">back to top</a>)</p>
<!--Links-->

[contributors-shield]: https://img.shields.io/github/contributors/Leo-Thomas/AI-based-red-rose-counting-webapp.svg?style=for-the-badge
[contributors-url]: https://github.com/Leo-Thomas/AI-based-red-rose-counting-webapp/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Leo-Thomas/AI-based-red-rose-counting-webapp.svg?style=for-the-badge
[forks-url]: https://github.com/Leo-Thomas/AI-based-red-rose-counting-webapp/network/members
[stars-shield]: https://img.shields.io/github/stars/Leo-Thomas/AI-based-red-rose-counting-webapp.svg?style=for-the-badge
[stars-url]: https://github.com/Leo-Thomas/AI-based-red-rose-counting-webapp/stargazers
[issues-shield]:https://img.shields.io/github/issues/Leo-Thomas/AI-based-red-rose-counting-webapp.svg?style=for-the-badge
[issues-url]:https://github.com/Leo-Thomas/AI-based-red-rose-counting-webapp/issues
[license-shield]: https://img.shields.io/github/license/Leo-Thomas/AI-based-red-rose-counting-webapp.svg?style=for-the-badge
[license-url]: https://github.com/Leo-Thomas/AI-based-red-rose-counting-webapp/blob/main/LICENSE
[product-screenshot]: Images/product.png

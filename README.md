<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
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
<br />
<div align="center">
  <!-- <img src="images/rizumu-logo.png" alt="Logo" width="80" height="80"> -->

<h3 align="center">Object Tracking for Cars Using a Pre-trained YOLO Model</h3>

  <p align="center">
    Object Tracking for Cars Using a Pre-trained YOLOv8 Model
  </p>
</div>

<div>
<h3 align="center">Oleh: </h3>
  <p align="center">
    Muhammad Faqih A - 1301213056
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#Screenshots">Screenshots</a>
    </li>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
  </ol>
</details>

<!-- Screenshots -->
## ScreenShots

Input:
<div align="center">
  <img src="before 1.png" width="400" />
  <img src="before 2.png" width="400" />
</div>

Output:
<div align="center">
  <img src="after 1.png"  width="400" />
  <img src="after 2.png" " width="400" />
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ABOUT THE PROJECT -->
## About The Project
This project focuses on **Object Tracking for Cars Using a Pre-trained YOLO Model**. The implementation is done using **YOLOv8** in **Google Colab**, enabling efficient object detection and tracking in real-time scenarios. The main objective is to track car movements using video footage captured from two different CCTV cameras installed on public roads.

### Arsitektur Model

- Utilizes **YOLOv8** (You Only Look Once version 8), a state-of-the-art object detection model developed by Ultralytics.
- Employs a **pre-trained model based on the COCO (Common Objects in Context) dataset**, which includes car classes.
- Combines **object detection** and **object tracking** pipelines to consistently follow the same vehicle across video frames.
- Uses deep learning-based tracking algorithms (e.g., DeepSORT) integrated with YOLO for assigning unique IDs to each detected car.

### Dataset
- The dataset consists of **video recordings from two different CCTV cameras** located on public roads.
- Each video contains continuous traffic footage used for testing the car detection and tracking pipeline.
- Videos are processed frame-by-frame, and YOLOv8 is applied to detect cars, which are then tracked across frames.

**CCTV Video Sources:**
- [Video CCTV 1](https://drive.google.com/file/d/1krf3znKFYcXseeWuVsQPvpDcZ0-JiHFO/view?usp=drive_link)
- [Video CCTV 2](https://drive.google.com/file/d/1wF6DZHSniimzsOq3wnqFZpPMl73F6wlR/view?usp=drive_link)

### Output Videos

The following are the results of the object tracking process applied to the CCTV footage:

- [Output Video 1](https://drive.google.com/file/d/1xkZheE6Nj0YcTJwFRd9oJuFJj23HNN7b/view?usp=drive_link)
- [Output Video 2](https://drive.google.com/file/d/1fO98ZYEYHLiUvpJ0VEO2qLfTTJe7aPFs/view?usp=drive_link)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With
- **Google Colab** – Cloud-based platform for coding and training the model.
- **Python** – Core programming language used for development.
- **YOLOv8 by Ultralytics** – Pre-trained object detection model.
- **OpenCV** – For video processing and visualization.
- **NumPy & Pandas** – For data manipulation and preprocessing.
- **Matplotlib** – For displaying sample results and plots.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 

# Intermovie

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">Intermovie</h3>

  <p align="center">
    Create your future video library, for great evenings on the sofa! And this without additional cost! Intermovie is the future benchmark in the growing world of video on demand!
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Usage](#usage)

<!-- ABOUT THE PROJECT -->
## About The Project

[![Intermovie Screen Shot][product-screenshot]](https://simplonline-v3-prod.s3.eu-west-3.amazonaws.com/media/image/jpeg/33e920cb-ac57-41da-81e2-f7174d2139ca.jpeg)

### Built With

* [Anaconda](https://www.anaconda.com/)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

1. Clone the repo

    ```sh
    git clone https://github.com/Intermovie/Intermovie.git
    ```

2. Create a conda virtual environment with

    ```sh
    conda create --name <env> --file requirements.txt
    ```

<!-- USAGE EXAMPLES -->
## Usage

* Run intermovie.ipynb
* Outputs
    1. Actors by movie : cast.movies.csv
    2. US movies (keeping french title) and avrage ratings : movies.us.ratings.csv
    3. Average ratings of different genres : genres.ratings.csv
    4. Average rating of each actor based to the movies in which he appears : actor.ratings.csv

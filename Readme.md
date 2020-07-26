[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <!--
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>
  -->
  <h3 align="center">GermanMelGen</h3>

  <p align="center">
    An awesome AI model to generate German Pop melodies
    <br />
    <a href="https://github.com/PratikSavla/GermanMelGen"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/PratikSavla/GermanMelGen">View Demo</a>
    ·
    <a href="https://github.com/PratikSavla/GermanMelGen/issues">Report Bug</a>
    ·
    <a href="https://github.com/PratikSavla/GermanMelGen/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

I have made many projects in AI. This time I decided to make something very simple and fun in this time. This is an LSTM model trained on [German Pop Melodies](https://kern.humdrum.org). It is an amazing way to learn the basics of LSTMs and music data preprocessing.

A list of commonly used resources that I find helpful are listed in the acknowledgements.



### Built With
This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Python](https://www.anaconda.com/)
* [Tensorflow](https://www.tensorflow.org/)
* [Music21](http://web.mit.edu/music21/)



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

* [Anaconda Python](https://www.anaconda.com/)
* [Musescore](https://musescore.org/en)



### Installation

1. Clone the repo
```sh
git clone https://github.com/PratikSavla/GermanMelGen.git
```
2. Create Conda Virtual Environment
```sh
cd GermanMelGen
conda create -n germelgen python=3.7 anaconda
```
3. Activate your virtual environment
```JS
source activate germelgen
```
4. Install packages
```sh
conda install --force-reinstall -y --name germelgen --file requirements.txt
```
5. Additional requirements may be needed to setup musescore.



<!-- USAGE EXAMPLES -->
## Usage

1. Download the [dataset](https://kern.humdrum.org/cgi-bin/ksdata?l=essen/europa/deutschl&format=recursive) for training the model
```sh
python preprocess.py
python train.py
```
2. Use Pretrained [Model](link) to generate melody.
```sh
python melodygenerator.py
```



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/PratikSavla/GermanMelGen/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@pratik_savla_](https://www.linkedin.com/in/pratik-savla-b5973815b/) - pratiksavla07@gmail.com

Project Link: [https://github.com/PratikSavla/GermanMelGen](https://github.com/PratikSavla/GermanMelGen)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/PratikSavla/GermanMelGen/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/PratikSavla/GermanMelGen/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/PratikSavla/GermanMelGen/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/PratikSavla/GermanMelGen/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/PratikSavla/GermanMelGen/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/pratik-savla-b5973815b/

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="https://www.washingtonpost.com/resizer/2sIm8CkBmFnHUp_7nKgB1jsw-cM=/arc-anglerfish-washpost-prod-washpost/public/6Y2CV66OA5AU5KB3IGANEXDXGM.jpg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">GPT Decoder</h3>

  <p align="center">
    This is a neural network that decodes/babbles language similar to whatever data you provide it with. For my purposes I trained it on the works of author Cormac McCarthy!
    <br />
    <a href="https://github.com/jkat-codes/MNIST-Neural-Network"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/jkat-cdoes/MNIST-Neural-Network/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/jkat-codes/MNIST-Neural-Network/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
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
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

This is an nth layer neural network built in Python, using Torch, that is able to digest text and return in it a form with a similar style to the data/text provided.

Here's how:

- I implemented a basic encoding algorithm to convert text into digits that computers can understand
- I implemented a neural network to receive the ecoded data and trained it

Follow the `README.md` to get started!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

- [![Python][python.io]][python-url]
- [![Pandas][pandas.io]][pandas-url]
- [![Numpy][numpy.io]][numpy-url]
- [![Torch][torch.io]][torch-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

- Basic usage --> Run main.py to train, this model will not be able to train on a basic CPU, I highly recommend the usage of a CUDA compatible GPU (NVIDIA only)

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Download the MNIST dataset from Kaggle [https://www.kaggle.com/c/digit-recognizer](https://www.kaggle.com/c/digit-recognizer)
2. Clone the repo
   ```sh
   git clone https://github.com/jkat-codes/MNIST-Neural-Network.git
   ```
3. Create a Python virtual environment
   ```sh
   python -m venv venv
   ```
4. Install required dependencies
   ```
   pip install numpy && pip install pandas && pip install torch
   ```
5. Find any data that you would like! I prefer PDF documents of books that I can copy and past into simple .txt files!
6. Change the data path to your specific path
   ```
   data = read_csv('YOUR PATH')
   ```
7. Run train.py to train the model
   ```sh
   python main.py
   ```
8. Once the model is done training, it will output about 5000 characters of decoded output. It will also save 10000 characters to a separate file. Both of these file paths and character amounts can be changed in main.py

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] Add encoding/decoding algorithm
- [ ] Train and iterate until the GPT can produce coherent language, similar to Cormac McCarthy's writing
- [ ] Add encoder to enable the user to communicate with the GPT
- [ ] Train the decoder on thousands of math problems
- [ ] Add different optimization algoritms (ADAMW)

See the [open issues](https://github.com/jkat-codes/MNIST-Neural-Network/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- [Andrej Karpathy's GPT Tutorial](https://www.youtube.com/watch?v=kCc8FmEb1nY&t=6125s)
- [Attention Is All You Need Paper](https://arxiv.org/abs/1706.03762)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[python.io]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[python-url]: https://www.python.org/
[pandas.io]: https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas
[pandas-url]: https://pandas.pydata.org/
[numpy.io]: https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white
[numpy-url]: https://numpy.org/
[torch.io]: https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white
[torch-url]: https://pytorch.org

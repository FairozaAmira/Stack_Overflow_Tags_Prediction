<!-- PROJECT LOGO -->
<br />

  <h3 align="center">Stack Overflow Tags Prediction</h3>

  <p align="center">
    Predicting Tags Based on Stack Overflow Dataset
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

Given a dataset that have `Title`, `Body` and `Tags` in the dataset, predict the `Tags` according to the title and body. 


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Install the necessary packages in your own environment.
```
jupyter notebooks, Python 3.6, Scikit-Learn, Keras, Tensorflow, NLTK, WordCloud, pandas, Matplotlib, Seaborn
```

### Installation
 
1. Clone the repo
```sh
git clone https:://github.com/FairozaAmira/Stack_Overflow_Tags_Prediction.git
```
2. Download the data from [here](https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/data).
3. Run the `load_data.ipynb` files to partition the data into smaller parts if you train it using Google Colaboratory or depending on your computing resources.
4. Run both other notebooks.

### Predicting the Tags architecture

1. Data analysis
2. Data preprocessing
3. Data cleaning
4. Predicting by using TF-IDF and Logistic Regression with OneVsRestClassifier
5. Predciting with LSTM and GRU models

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

Distributed under the Apache 2.0 License. See `LICENSE` for more information.

<!-- CONTACT -->
## [fairozaamira@gmail.com](fairozaamira@gmail.com) 


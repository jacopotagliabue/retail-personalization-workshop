# retail-personalization-workshop
Code for the In-Session Personalization workshop for eCommerce, April 2021

## Overview
This repo hosts the code for the [In-Session Personalization](https://www.eventbrite.ca/e/machine-learning-in-retail-sales-marketing-e-commerce-summit-tickets-138507063355) workshop at the _Machine Learning in Retail Summit_. The workshop is a hands-on meeting on in-session personalization, including slides and this open source repository: our aim is to implement a sound and readable version of the models found in our research papers, showcasing tried and tested personalization strategies on real e-commerce data.

While the notebook is heavily commented, please refer to the slides and the references below for the full context behind the product features and some design choices.

## How to run the code

### Setup
Make sure to install all the required dependencies, as listed in the `requirements.txt` file. Launch `jupyter notebook` and run the code as a standard notebook. 

### Data
The code works out of the box with the real-world dataset shared by Coveo for the [SIGIR Data Challenge 2021](https://github.com/coveooss/SIGIR-ecom-data-challenge): download the data, put it in a local folder, and then change the `LOCAL_FOLDER` variable in the notebook to point to the `train` folder in your computer. Remember that use of the Coveo dataset implies the acceptance of the accompanying T&C.

If you wish to use your own e-commerce data, all the "ML code" can be kept intact, as long as you replace the functions devoted to prepare session data from the training set.

## Contacts
For questions related to tools and models, or if you wish to organize a similar workshop together, please contact [me](https://www.linkedin.com/in/jacopotagliabue/).

## References
The theory of in-session personalization through product spaces and the related use-cases have been developed, tested and benchmarked at Coveo AI in several research papers during 2020. In particular:

* ["An Image is Worth a Thousand Features": Scalable Product Representations for In-Session Type-Ahead Personalization](https://dl.acm.org/doi/10.1145/3366424.3386198)
* [Fantastic Embeddings and How to Align Them: Zero-Shot Inference in a Multi-Shop Scenario](https://arxiv.org/abs/2007.14906)
* [Shopping in the Multiverse: A Counterfactual Approach to In-Session Attribution](https://arxiv.org/pdf/2007.10087.pdf)
* [The Embeddings That Came in From the Cold: Improving Vectors for New and Rare Products with Content-Based Inference](https://dl.acm.org/doi/10.1145/3383313.3411477)
* [How to Grow a (Product) Tree: Personalized Category Suggestions for eCommerce Type-Ahead](https://www.aclweb.org/anthology/2020.ecnlp-1.2/)

If you find this workshop (and code) useful, please remember to cite our work!

## Acknowledgments
[Patrick John Chia](https://www.linkedin.com/in/patrick-john-chia-b0a34019b/) helped co-authoring the session and preparing the materials. We also wish to thank our co-authors, which co-developed some of the models and ideas we presented. In particular:

* [Ciro Greco](https://www.linkedin.com/in/cirogreco/) - Coveo AI Labs
* [Federico Bianchi](https://www.linkedin.com/in/federico-bianchi-3b7998121/) - Postdoctoral Researcher at Università Bocconi
* [Bingqing Yu](https://www.linkedin.com/in/bingqing-christine-yu/) - Coveo

Finally, the authors wish to thank Coveo for supporting our research, and [Luca Bigon](https://www.linkedin.com/in/bigluck/) for help in data collection and preparation.

## How to Cite our Work

If you find this code and dataset useful, please cite our work:

```
@inproceedings{CoveoSIGIR2021,
author = {Tagliabue, Jacopo and Greco, Ciro and Roy, Jean-Francis and Bianchi, Federico and Cassani, Giovanni and Yu, Bingqing and Chia, Patrick John},
title = {SIGIR 2021 E-Commerce Workshop Data Challenge},
year = {2021},
booktitle = {SIGIR eCom 2021}
}
```

## License
All code is provided "as is" under a standard MIT License.

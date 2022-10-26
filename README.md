# Image-Classification-by-Federated-Learning
Project aimed to provide introduction to and insights of the implementation of Fedarated Learning.

---

<img src="https://federated.withgoogle.com/assets/comic/panel046_2x.png" align="right" height="225px" width="225px">

Standard machine learning algorithms necessitate storing training data on a single computer or in a datacenter. And, in order to improve our services, Google has constructed one of the most secure and strong cloud infrastructures. We're now presenting a new technique for models trained through user interaction with mobile devices: Federated Learning.

## What is Federated learning?
Federated learning is a technique for machine learning that enables models to learn from several data sets located at various locations (such as regional data centres or a central server) without sharing training data. This minimises the likelihood of personal data breaches by allowing personal data to stay in local locations.

Federated learning is a technique for training other machine learning algorithms that uses many local datasets without exchanging data. This enables businesses to build a common global model without storing training data in a centralised location.


<img src="https://federated.withgoogle.com/assets/comic/panel034_2x.png" align="right" height="225px" width="225px">

## Implementation
- Implementation of Federated Learning gist of which are:

    - Train your model without uploading client's data on cloud
    - Provides assurance of privacy in terms of interests and activity
    - Model hosted on cloud only uplaods the results back to the server
    - Thus, full-flegded security and assurance of none sort of fetching data/leakage.
    - More Details on Federated Learning : **https://federated.withgoogle.com/**

- Uses MNIST dataset of different writing styles considering them as data of various client's.
- Train model on federated data; predicting and customizing model implementation for accurate results.

## Enhanced Data Security and Use Cases:

Federated learning works without storing user data in the cloud, but that is not all. There has been a **Secure Agression Potocol** put in place which used crytographic techniques so a server(cloud) can decrypt **average update** only when 100s or 1000s of users/devices have participated - no individual data cannot be accessed befor averaging. Federated Averaging was designed so that the coordinating server only needs the average update, allowing Secure Aggregation to be used; however, the protocol is general and can be applied to other problems as well.


Applying Federated Learning requires machine learning practitioners to adopt new tools and a new way of thinking: model development, training, and evaluation with no direct access to or labeling of raw data, with communication cost as a limiting factor.

#### Use Cases:

- Gboard query suggestions. 
- Photo rankings based on what kinds of photos people look at, share, or delete.
- There are many ML problems which federated learning cannot solve.( Example: Find the species of flower, diffrent dog breeds).

---

## Dependencies
- tensorflow_federated_nightly also bring in tf_nightly, which can causes a duplicate tensorboard install, leading to errors.
- Follow the commands below to set up your environment correctly
  - ```pip uninstall --yes tensorboard tb-nightly``` removing previous versions to avoid duplicate installations
  - ```pip install --quiet --upgrade tensorflow-federated-nightly``` upgrading the package
  - ```pip install --quiet --upgrade nest-asyncio``` installing/upgrading other dependencies
  - ```pip install --quiet --upgrade tb-nightly``` or tensorboard, not both
- This project has been setup in Google Colaboratory Notebook. To have better experience and to keep focus on main thing, use Google Colaboratory Notebooks for easy environment setup.
- Check out https://www.tensorflow.org/federated/ for more details on `tensorflow_federated`

---
## Getting started
* Fork this repository (Click the Fork button in the top right of this page, click your Profile Image)
* Clone your fork down to your local machine

```markdown
git clone https://github.com/your-username/mage-Classification-by-Federated-Learning.git
```

* Create a branch

```markdown
git checkout -b branch-name
```

* Make your changes
* Commit and push

```markdown
git add .
git commit -m 'Commit message'
git push origin branch-name
```

* Create a new pull request from your forked repository (Click the `New Pull Request` button located at the top of your repo)
* Wait for your PR review and merge approval!
* __Star this repository__ if you had fun!

---
---

## Contributors

<a href="https://github.com/paxF3E/Image-Classification-by-Federated-Learning/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=paxF3E/Image-Classification-by-Federated-Learning" />
</a>

---
---

## Goals

- Implementation of self-customized models on your own.
- Extend the application of Federated Learning to various problems related to data privacy concerns.
- Have a better understanding in the sub-field of implementing data models using Federated Learning approach.

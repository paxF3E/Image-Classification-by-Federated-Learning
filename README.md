# Image-Classification-by-Federated-Learning
<img src="https://federated.withgoogle.com/assets/comic/panel034_2x.png" align="right" height="250px" width="250px">
Project aimed to provide insights of the implementation of Fedarated Learning.

_________________________________________________________________________________________________________________________________________________________________
_________________________________________________________________________________________________________________________________________________________________

## Description
<img src="https://federated.withgoogle.com/assets/comic/panel046_2x.png" align="left" height="250px" width="250px">

- Implementation of Federated Learning gist of which are:

    - Train your model without uploading client's data on cloud
    - Provides assurance of privacy in terms of interests and activity
    - Model hosted on cloud only uplaods the results back to the server
    - Thus, full-flegded security and assurance of none sort of fetching data/leakage.
    - More Details on Federated Learning : **https://federated.withgoogle.com/**

- Uses MNIST dataset of different writing styles considering them as data of various client's.


- Train model on federated data; predicting and customizing model implementation for accurate results.
_________________________________________________________________________________________________________________________________________________________________
_________________________________________________________________________________________________________________________________________________________________

## Dependencies
- tensorflow_federated_nightly also bring in tf_nightly, which can causes a duplicate tensorboard install, leading to errors.
- Follow the commands below to set up your environment correctly
  - ```pip uninstall --yes tensorboard tb-nightly``` removing previous versions to avoid duplicate installations
  - ```pip install --quiet --upgrade tensorflow-federated-nightly``` upgrading the package
  - ```pip install --quiet --upgrade nest-asyncio``` installing/upgrading other dependencies
  - ```pip install --quiet --upgrade tb-nightly``` or tensorboard, not both
- This project has been setup in Google Colaboratory Notebook. To have better experience and to keep focus on main thing, use Google Colaboratory Notebooks for easy environment setup.
- Check out https://www.tensorflow.org/federated/ for more details on `tensorflow_federated`

_________________________________________________________________________________________________________________________________________________________________
_________________________________________________________________________________________________________________________________________________________________

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

_________________________________________________________________________________________________________________________________________________________________
_________________________________________________________________________________________________________________________________________________________________

## Contributors

<a href="https://github.com/paxF3E/Image-Classification-by-Federated-Learning/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=paxF3E/Image-Classification-by-Federated-Learning" />
</a>

_________________________________________________________________________________________________________________________________________________________________
_________________________________________________________________________________________________________________________________________________________________

## Goals
- Implementation of self-customized models on your own.
- Extend the application of Federated Learning to various problems related to data privacy concerns.
- Have a better understanding in the sub-field of implementing data models using Federated Learning approach.

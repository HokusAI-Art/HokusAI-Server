# HokusAI-Server
![](https://img.shields.io/badge/-Google%20Colab-orange?style=for-the-badge&logo=google%20colab)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)

**How does this work?**
We are using Google Colab as our backend compute server. The notebook sets up a worker service in Colab, which takes in tasks from a queue we fetch from Firebase, and then executes it in Colab, then uploads the result back to our Firebase

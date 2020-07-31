# A toy breast cancer ML classification model deployed in Flask and Docker

## How to run this demo
The demo requires Docker and Python 3.X. We suggest creating a new virtual environment, then running:
```
git clone https://github.com/HongleiXie/breast-cancer-API.git
cd breast-cancer-API/
sudo docker build -t breast_cancer_api .
docker run -p 5000:5000 breast_cancer_api
```

## More details
Please check out this [blog post](http://hongleixie.github.io/blog/deploy-model-flask/) for explanations and instructions.

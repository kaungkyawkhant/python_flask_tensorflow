#Flask Application with Tensorflow

`python3 app.py`

https://www.tensorflow.org/

#Docker run command to serve tensorflow app
Docker Commands

`sudo docker run -p 8501:8501 --name=pets -v "/Users/User/tensorflow/pets/:/models/pets/1" -e MODEL_NAME=pets tensorflow/serving`
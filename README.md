# ML-project

## create container
docker run -it -p 8888:8888 -v /home/josue/borra/ML-project:/tf/ML-project tensorflow/tensorflow:latest-jupyter

## generate requirements
diff requirements_before.txt requirements_after.txt | grep '>' | sed 's/> //' > requirements.txt

## how to store in git?
model - score

notebook: name - score: number
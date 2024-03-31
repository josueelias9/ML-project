# ML-project

## create container
docker run -it -p 8888:8888 -v PATH/REPOSITORY_NAME:/tf/REPOSITORY_NAME tensorflow/tensorflow:latest-jupyter

## generate requirements
diff requirements_before.txt requirements_after.txt | grep '>' | sed 's/> //' > requirements.txt

## how to store in git?
model - score

notebook: name - score: number

## source
https://www.tensorflow.org/decision_forests/tutorials/model_composition_colab
https://pypi.org/project/fuzzywuzzy/
https://www.youtube.com/watch?v=MiqoA-yF-0M

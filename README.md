# AzureDevops-Java-ECS

Se deben de crear las siguientes variables en azure devops:

se debe de poner como: $(AWS_ACCESS_KEY)

AWS_ACCESS_KEY = access key de la cuenta de aws 
AWS_SECRET_KEY= secret de la cuenta de aws
ID= id de la cuenta de aws
REPOSITORY= nombre de repositorio de ecr
AWS_REGION = la region de aws donde se creó el ecs y el ecr
APP_NAME: nombre de la app, en mi caso es apiimage
TAG = tag de la imagen , en mi caso es latest
SERVICE_NAME = nombre del servicio del ecs
ARN_CLUSTER= Arn del cluster

En aws se debe de tener creado el ecs con la tarea y su servicio respectivo, tambien se debe de tener el repositorio en ecr creado. Para crear el ecs nos podemos ayudar con el siguiente link: https://towardsdatascience.com/deploying-a-docker-container-with-ecs-and-fargate-7b0cbc9cd608

Postdata: del link solamente hacer la parte de ECS, del resto no es necesario.

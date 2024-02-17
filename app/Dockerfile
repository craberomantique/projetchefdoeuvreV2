#----------Début de la couche OS----------
FROM python:3
#----------Fin de la couche OS------------

#Répertoire de travail
WORKDIR /appli

#-----Début de la couche installation-----
COPY . /appli
RUN pip install -r requirements.txt
#-----Fin de la couche d'installation-----

#Ouverture du port
EXPOSE 3000

#Commandes au lancement
CMD python ./app.py

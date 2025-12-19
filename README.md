# Fall Detection – Computer Vision Project
**Mathéo STEPHAN & Florian VITOUX**

Ce projet implémente une solution de détection de chutes (fall detection) à partir de vidéos et images en utilisant des techniques de vision par ordinateur.

L’objectif est de détecter automatiquement lorsqu’une personne chute, pour des futures applications de surveillance, sécurité et assistance aux personnes par exemple.

Le projet est très efficace sur des images. En revanche, sur des séquences vidéo, la méthode doit encore être améliorée : elle est particulièrement fiable lorsque la caméra est fixe, mais ses performances diminuent lorsque la caméra est mobile (déplacements, zoom, variations d’angle). 

Dans ces conditions, les indicateurs basés sur la position verticale normalisée des articulations et sur le ratio largeur/hauteur de la boîte englobante deviennent plus sensibles aux changements de perspective. Une amélioration consiste à stabiliser la scène ou à utiliser des critères invariants à la caméra (angles du corps, orientation du tronc, vitesse relative).
## Description

L’ensemble du travail est regroupé dans le notebook [dataset.ipynb](dataset.ipynb).

Ce notebook contient :
- l’exploration et la préparation du dataset,
- la visualisation des images et vidéos,
- l’utilisation de modèles de détection (YOLO / pose estimation),
- l’analyse des résultats pour la détection de chutes.

Des modèles pré-entraînés sont utilisés pour détecter les personnes et analyser leur posture afin d’identifier des situations de chute.

## Objectif

Ce projet a pour but de fournir une base fonctionnelle et pédagogique pour :
- comprendre la détection de chutes par vision par ordinateur,
- expérimenter avec des modèles de détection et de pose humaine,
- analyser des séquences vidéo pour des applications de sécurité.



## Technologies utilisées

- Python
- OpenCV
- YOLO (Object Detection & Pose Estimation)
- Vision par ordinateur


*Pour plus de détails sur l’implémentation et les résultats, [Voir le notebook principal](dataset.ipynb)*


![gif](https://github.com/user-attachments/assets/1dcdee0b-9a06-44ed-b381-4b58f9c06264)



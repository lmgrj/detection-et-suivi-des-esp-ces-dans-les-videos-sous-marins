# Réseaux de nouerons parallèles pour la détection et le suivi des espèces dans les vidéos sous-marines

## voire le Rapport ici:
Le travail principal de ce stage sera donc composé de deux grandes phases principales : la détection des espèces de poissons dans un premiers lieux, et le suivi de ces derniers dans une vidéo sous-marine en utilisant l’apprentissage profond. Les contributions se résument dans ce qui suit :

 — Tout d’abord, nous implémentons une approche pour la détection de poissons dans des images vidéo sous-marines. Cette approche est basée sur la fusion de deux réseaux profonds en parallèles. Un premier réseau extrait les caractéristiques d’apparence de chaque image vidéo couleur. Ces caractéristiques peuvent être de type texture, forme et couleur. Tandis que l’autre réseau extrait les caractéristiques de mouvement à partir des images successives. Les caractéristiques de mouvement peuvent être très pertinentes. Le poisson apparaît dans plusieurs images d’une vidéo, et peut changer de direction et de posture en nageant, ce qui a également un impact sur la représentation des caractéristiques. Nous exploitons cette information temporelle en plus de l’information de l’apparence pour améliorer les performances de la détection.

— Ensuite, nous abordons le problème de suivi d’espèces de poissons. L’apprentissage profond requiert des bases de données de grande taille pour une meilleure per- formance. Toutefois, les bases d’images de poissons disponibles sont de petite taille. Pour surmonter ce problème, nous utilisons l’approche d’apprentissage par transfert dans différentes stratégies tout en abordant diverses problématiques (choix de l’es- pace colorimétrique, élimination ou non d’arrière-plan, et manière d’augmentation artificielle de données).


<iframe src="https://github.com/lmgrj/detection-et-suivi-des-esp-ces-dans-les-videos-sous-marins/Presentation-PFE.pptx.pdf" width="100%" height="800px"> </iframe>

https://github.com/lmgrj/detection-et-suivi-des-esp-ces-dans-les-videos-sous-marins/blob/main/Presentation-PFE.pptx.pdf

[View the PDF](https://github.com/lmgrj/detection-et-suivi-des-esp-ces-dans-les-videos-sous-marins/blob/main/Presentation-PFE.pptx.pdf)



![Capture](https://user-images.githubusercontent.com/54851310/193289414-2fdd824d-cb41-46ab-9461-cce2db39e5c8.PNG)
![image](https://user-images.githubusercontent.com/54851310/193421470-48ec92de-702e-4aaf-a5b1-46d1aaf27439.png)


![b](https://user-images.githubusercontent.com/54851310/193290670-71f3cf49-d5bb-44be-b3d3-00089f5aeed4.PNG)

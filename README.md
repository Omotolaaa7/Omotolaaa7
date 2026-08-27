<div align="center">

# Omotola AFOUDA

**Étudiante en 3ᵉ année de licence d'Intelligence Artificielle · Cotonou, Bénin**

[Mon portfolio](https://portfolio-omotola.vercel.app) ·
[LinkedIn](https://www.linkedin.com/in/omotola-afouda) ·
[andreaafouda@gmail.com](mailto:andreaafouda@gmail.com)

</div>

---

Je construis des modèles qui regardent des choses réelles : des carrefours
saturés, des récoltes, des clients sur le point de partir. Ce que je préfère
dans ce travail, c'est le moment où un tableau de chiffres bruts commence à
répondre.

Ma méthode tient en trois mots que je dois autant aux échecs qu'à un poème
que mon père m'a offert : **itérer, douter, recommencer**. Le troisième est
celui qui coûte.

> *« Si tu peux voir détruit l'ouvrage de ta vie, et sans dire un seul mot te
> mettre à rebâtir »*
> Rudyard Kipling, *Tu seras un homme, mon fils*

---

## Les projets qui comptent

### [Détection de véhicules en trafic dense](https://github.com/Omotolaaa7/-traffic-vehicle-detection-yolov8)

Un YOLOv8 pré-entraîné voit très bien une voiture qui remplit l'image. Filmé
d'en haut, dans un embouteillage, il décroche. Ce projet mesure proprement ce
qu'un fine-tuning change, et surtout ce qu'il change **sur les petits objets**.

| | Pré-entraîné | Après fine-tuning |
|---|---:|---:|
| mAP@0.5 | 0.438 | **0.825** |
| Rappel, petits véhicules | 0.122 | **0.694** |
| Rappel, véhicules moyens | 0.373 | 0.879 |
| Débit | 37.2 FPS | 43.2 FPS |

Le chiffre qui m'a servi de leçon est le 0.12. Le mAP global était bon, je m'y
suis arrêtée, et c'est en découpant par taille d'objet que j'ai vu que neuf
petits véhicules sur dix passaient à travers. Une moyenne peut être bonne
pendant qu'un modèle rate l'essentiel.

`Python` `YOLOv8` `PyTorch` · jeu de données BMD-45, environ 3 000 images

### [ChurnClient](https://github.com/Omotolaaa7/ml_projet_ChurnClient)

Prédire quels clients vont partir avant qu'ils ne le décident eux-mêmes.
7 043 clients, une analyse exploratoire complète, un pipeline de bout en bout.
J'étais sûre de savoir qui partait : l'analyse a dit autre chose.

`Python` `pandas` `scikit-learn` `Jupyter`

### [Prédiction des rendements agricoles en Afrique de l'Ouest](https://github.com/Omotolaaa7/west_africa-crop_yield_prediction)

Maïs, riz, sorgho, mil. Une régression sur des données climatiques,
socio-économiques et agronomiques venues de sources différentes, avec des
unités et des granularités qui ne s'accordent pas. Le vrai travail était le
nettoyage.

`R`

### [Répartition équitable de l'eau](https://github.com/Omotolaaa7/equitable-water-distribution)

Répartir l'eau sur un réseau de distribution quand la demande est incertaine.
Optimisation quadratique par pénalisation, descente de gradient projetée,
validation par simulation Monte-Carlo.

`Python`

### SkillZ, deuxième prix du hackathon HACKBYIFRI 2026

Une place de marché de compétences étudiantes pensée pour le contexte
béninois : paiement MTN MoMo, Moov Money et Celtiis Cash, séquestre, notation
dans les deux sens, connexion par matricule universitaire. De l'idée au
prototype en 48 heures, en équipe.

---

## Ce que je sais faire, et à quel point

**Mon terrain quotidien.** Python, pandas, NumPy, scikit-learn, Matplotlib et
Seaborn, et l'analyse exploratoire, qui est la partie que je préfère.

**En cours.** Vision par ordinateur avec YOLOv8, R, SQL et MySQL, Streamlit.

**Touché, compris, à approfondir.** React, Django et DRF, Java, Laravel.

Pas de barre de pourcentage ici : chaque ligne est adossée à un dépôt ou à un
projet qu'on peut ouvrir.

---

## Ailleurs

Les échecs, où mon souvenir le plus net est une défaite. Les histoires
dessinées, Vinland Saga en tête. Et de la musique en fond, presque tout le
temps, parce que le bon morceau est parfois la seule chose qui fait tenir un
débogage.

Un stage, une mission, une partie d'échecs, ou une série à me conseiller :
[écrivez-moi](mailto:andreaafouda@gmail.com).

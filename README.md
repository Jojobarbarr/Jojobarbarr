# Titre

Je suis **Basile Gandon**, étudiant en 3e année à l'**Ecole Nationale Supérieure de Géologie** de Nancy. Je développe des intérêts pour les **mathématiques**, l'**informatique**, en particulier la **modélisation**, l'**analyse** et l'**exploitation** de données, notamment en utilisant l'**intelligence artificielle**. J'ai réalisé plusieurs stages, et formations, variés car je veux être multidisciplinaire, capable de comprendre en profondeur les sujets sur lesquels je travaille, ne pas hésiter à cliquer sur les sujets pour voir en détail ce que chacun m'a apporté :
 - [**Modélisateur** à l'équipe prospective de la **Direction de la Stratégie d'ENEDIS** (stage de mai à septembre 2025, Paris).](#modélisateur-à-léquipe-prospective-de-la-direction-de-la-stratégie-denedis)
 - [**Apprentissage Profond pour l'inversion de données de Tomographie par Résistivité Electrique** à l'équipe **Research for Integrative Numerical Geology** du laboratoire **GéoRessources** (projet de master de août à mai 2025, Nancy).](#apprentissage-profond-pour-linversion-de-données-de-tomographierpar-résistivité-electrique-à-léquipe-research-for-integrative-numerical-geology-du-laboratoire-géoressources)
 - [**Statistical Physics of Complex Systems** (Summer school juillet 2024, Madrid).](#statistical-physics_of_complex_systems)
 - **Assistant de terrain** aux biologistes de l'**Instituto de Investigación en Recursos Cinegéticos (IREC)** (stage de césure de mai à juillet 2024, Espagne).
 - **Développeur de modèle de vie artificielle** à l'équipe BEAGLE de l'**INRIA** (stage de césure de février à mai 2024, Lyon).
 - **Chercheur en IA générative** dans l'équipe **PREV** de **Météo France** (stage de césure de juillet à décembre 2024, Toulouse).
 - **Analyse de faisabilité d'un stockage de chaleur géothermique** (module de gestion de projet au cours de la formation de l'ENSG, septembre 2021 à novembre 2022).
Ces expériences ont accompagné ma formation, également variée :
 - **Master Economie de la transition énergétique, environnementale et numérique**, **mention Très Bien** (septembre 2025, Université de Lorraine).
 - **Master Sciences de la Terre et des Planètes, Environnement - Géologie Numérique**, **mention Très Bien** (septembre 2025, Université de Lorraine).
 - **Diplôme d'Ingénieur Géologue**, spécialisation **Géologie Numérique** (septembre 2025, Ecole Nationale Supérieures de Géologie).
 - **Formation Introduction au Deep LEarning (FIDLE)**, formation du **CNRS** (décembre 2024, MOOC).
 - **Classe Préparatoire aux Grandes Ecoles Biologie, Chimie, Physique, Sciences de la Terre** (septembre 2021, Lycée du Parc à Lyon).


## Projets récents
### **Modélisateur** à l'équipe prospective de la **Direction de la Stratégie d'ENEDIS**
Enedis est le gestionnaire du réseau de distribution d'électricité pour 95% des utilisateurs. Ses missions vont du raccordement à la gestion et l'entretien du réseau de distribution. Avec la transition énergétique qui conduit à une électrification des usages, et à une production électrique de plus en plus locale et non pilotable, Enedis fait face à de nouveaux défis et doit avoir une vision sur l'avenir. C'est le travail de l'équipe prospective de la Direction de la Stratégie. Pour ma part, la modélisation se concentre sur la partie production éolienne et photovoltaïque. Le modèle prend en entrées les trajectoires globales gouvernementales de production et les décline localement, à l'échelle de la commune. Ce projet m'a amené à réécrire le modèle afin de le rendre le plus maintenable, robuste et clair possible. Cela est passée par une abstraction, tant au niveau des noms des données que du code, avec une utilisation de la Programmation Orientée Objet et de l'héritage permettant un code adapté à chaque expérience, et apportant une maintenabilité et une robustesse.

De plus, la mission nécessite de comprendre précisément le sujet : la distribution de l'électricité, au sein d'un système européen mélant monopoles régulés (gestionnaires de réseaux) et concurrence (producteurs et fournisseurs). Le tout au sein de l'espace socio-économique que constitue l'Union Européenne. Pour cela, j'ai assisté à de nombreuses réunions de la direction de la Stratégie qui m'ont permis de développer les connaissances métier et les enjeux rencontrés par Enedis.

### **Apprentissage Profond pour l'inversion de données de Tomographie par Résistivité Electrique** à l'équipe **Research for Integrative Numerical Geology** du laboratoire **GéoRessources**
La tomographie par résistivité électrique (Electrical Resistivity Tomography - ERT) est une méthode d'observation du sous-sol non destructive, utilisée dans de nombreux cas, de l'archéologie à l'hydrogéologie en passant par la géotechnique ou l'étude du pergélisol. Si l'aquisition des données est relativement simple et peu chère, leur interprétation est difficile car nécessite de résoudre un problème inverse, un problème mathématique qui est mal posé au sens de Hadamard. Le problème consiste à trouver le modèle de résistivité du sous-sol qui explique les données observées. Le paradigme de résolution actuel consiste à échantillonner l'espace des modèles puis de résoudre le problème direct (simuler les données qu'on obtiendrait avec ce modèle) et comparer les données simulées avec les données mesurées. Avec une descente de gradient, on essaie alors d'échantillonner un nouveau modèle plus explicatif des données observées.

L'approche réalisée dans le cadre de ce travail est différente : il s'agit d'entraîner un réseau de neurone profond à apprendre l'opérateur pseudo-inverse afin de générer un modèle de résistivité à partir de données observées. Pour cela, de nombreux couple (modèle de résistivité synthétique, données simulés) ont été générés puis utilisés en tant qu'entraînement pour le réseau. Une validation a été effectuée sur la Plateforme Expérimentale Géophysique Géotechnique Hydrogéologie (PEGGHy) de l'ENSG, qui fournit un milieu réel dont on connaît le sous-sol.

Le modèle fournit des résultats prometteurs, moins précis qu'une inversion basique par approche classique mais en allant plus en profondeur. La piste est vraiment prometteuse, mais nécessite de s'assurer de la généralisation de l'apprentissage.

### **Statistical Physics of Complex Systems**
Cette summer school a été destiné

### 🔹 Kansas Instrument (C++)
Développement d'un **parser** en C++ permettant la construction d'un arbre binaire pour gérer les priorités d'opérations. Ce projet met en avant des compétences en gestion de projet de développement, en gestion d'équipe, en structuration de données, en programmation orientée objet, en CI/CD et en Github actions.

## 🎯 Objectifs et aspirations

Je souhaite devenir un profil **multidisciplinaire**, associant mon expertise en informatique et deep learning, avec des compétences plus socio-économique, et scientifique. Mon objectif est de contribuer aux avancées dans la modélisation et la compréhension du monde, particulièrement améliorer les problèmes liés aux enjeux sociétaux et environnementaux (marché de l'énergie par exemple).

## 📫 Contact

- [LinkedIn](https://www.linkedin.com/in/basile-gandon)

Merci d'avoir pris le temps de visiter mon profil ! N'hésitez pas à me contacter pour échanger sur des projets, des idées ou des opportunités !

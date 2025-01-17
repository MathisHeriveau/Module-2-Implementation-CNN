# Module-2-Implementation-CNN

## 🧠 Qu'est-ce qu'un Convolutional Neural Network (CNN) ?

Les **Réseaux de Neurones Convolutionnels (CNN)** sont une architecture de réseau de neurones principalement utilisée pour le traitement d'images, la reconnaissance d'objets, et d'autres tâches liées à la vision par ordinateur. Leur principal atout réside dans leur capacité à extraire des caractéristiques locales et hiérarchiques des images à travers l'application de **filtres convolutionnels**.

Les CNN sont composés de plusieurs couches qui permettent d'extraire progressivement des informations de plus en plus complexes à partir des pixels d'une image. Ces couches comprennent des couches de **convolution**, de **pooling** et des couches **entièrement connectées (fully connected)**.

---

## 🎮 Utilisation de Gymnasium pour l'IA de Doom

Dans ce projet, nous utilisons **Gymnasium** (anciennement OpenAI Gym) pour créer un environnement d'entraînement pour l'IA. Gymnasium est une bibliothèque populaire permettant de simuler des environnements dans lesquels les IA peuvent être testées et entraînées. Nous avons choisi de tester notre modèle sur l'environnement **Doom**, un jeu vidéo où l'IA doit naviguer dans un monde complexe en prenant des décisions pour survivre.

### 🕹️ L'Environnement Doom

**Doom** est un jeu vidéo de type FPS (First Person Shooter), où l'agent (l'IA) doit se déplacer dans un environnement, éviter les ennemis, collecter des objets et réussir des missions. C'est un environnement parfait pour tester l'apprentissage par renforcement.

Grâce à **Gymnasium**, il est facile de connecter notre modèle d'IA à l'environnement Doom et de l'entraîner à l'aide de réseaux de neurones convolutifs (CNN).

---

## 🧑‍💻 Code & Installation

Pour entraîner l'IA à jouer à Doom avec un **CNN**, voici les étapes et le code à suivre :

Vous devez d'abord installer **Gymnasium** et ses dépendances pour pouvoir utiliser l'environnement Doom :

```bash
pip install gymnasium
pip install "gymnasium[atari]"
```

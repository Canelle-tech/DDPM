# Implémentation SimCLR et DDPM

## Description

Ce projet consiste en deux implémentations d’algorithmes avancés en apprentissage automatique : SimCLR (Simple Framework for Contrastive Learning of Visual Representations) et DDPM (Denoising Diffusion Probabilistic Models). Ces deux algorithmes sont utilisés pour l’apprentissage auto-supervisé et la génération d’images, respectivement.

## SimCLR

SimCLR est une méthode d’apprentissage contrastif qui permet d’apprendre des représentations visuelles sans avoir recours à des données étiquetées. L’implémentation se fait en PyTorch en utilisant le dataset STL-10. Le modèle effectue une classification après un pré-entraînement auto-supervisé.

## DDPM

DDPM est un modèle de diffusion probabiliste qui génère des images en supprimant progressivement le bruit d’une distribution de bruit gaussien. Dans ce projet, nous utilisons le dataset MNIST pour entraîner le modèle à générer des images de chiffres.

## Structure du Projet

	•	SimCLR.ipynb : Notebook contenant l’implémentation de SimCLR, avec les classes Net, SimCLRDataset, et la perte SimCLR dans la classe Trainer.
	•	DDPM.ipynb : Notebook contenant l’implémentation du modèle DDPM pour générer des images MNIST, avec la classe DDPM.

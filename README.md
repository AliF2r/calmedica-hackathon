<div align="center">
  <a>
    <img 
      src="https://www.calmedica.com/wp-content/uploads/2020/05/Calmedica-logo-flat-200.png"
      alt="calmedica-logo" 
      height="50" />
  </a>
  <h3 align="center">Hackathon 2024 - Calmedica</h3>
  <h2 align="center">Plateforme de transcription audio des patients</h2>
</div>

## Listing des fonctionnalités avec les auteurs de celle-ci

### Partie frontend : Chakib KARMIM & Mustapha BOUDOUCH
- Visualisation et gestion des informations des patients ainsi que leurs échanges
- Importation et lecture des fichiers audio
- Affichage dans un format de conversation le fichier transcrit en appliquant des styles différents pour les messages des assistants et des patients
- Ajout d'un badge de couleur représentant le statut de suivi d'un échange

### Partie backend : Ali FATOORIFAR, Walid BOULBOUL & Sassan KHALAFI
- Mise en place de la base de données avec Prisma
- Configuration des différentes API et modèles d'intelligence artificielle (Twilio, OpenAI & Whisper)
- Traitement et enregistrement des appels téléphoniques
- Fonctionnalités nécessaires pour la transcription, l'identification des intervenants, la génération de résumés et l'extraction des mots-clés

## Nom et pseudo de chaque développeur ayant participé
- BOULBOUL - walidBLS
- BOUDOUCH - mustaphaboudouch
- FATOORIFAR - aliF2r
- KARMIM - chakibKarmim
- KHALAFI - sassank

## Installation du projet
Se rendre sur le terminal et exécuter les commandes suivantes :
```bash
cd calmedica-hackathon
npm install
npm run dev
```
Pour utiliser OpenAI ne pas oublier d'ajoutez votre propre clé 'OPENAI_API_KEY' dans le fichier .env à la racine du projet.
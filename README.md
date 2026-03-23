<p align="center">
  <img src="BANNIERE_TECHNEWS365_OS.png" alt="TechNews365 OS Banner">
</p>

<p align="center">

  <!-- Version -->
  <img src="https://img.shields.io/github/v/release/webmasterdu63-creator/technews365OS?label=Version&color=blue" />

  <!-- License -->
  <img src="https://img.shields.io/github/license/webmasterdu63-creator/technews365OS?label=License&color=green" />

  <!-- Downloads -->
  <img src="https://img.shields.io/github/downloads/webmasterdu63-creator/technews365OS/total?label=Downloads&color=orange" />

  <!-- Build Status -->
  <img src="https://img.shields.io/github/actions/workflow/status/webmasterdu63-creator/technews365OS/build-iso.yml?label=Build%20ISO&color=purple" />

  <!-- Dernier commit -->
  <img src="https://img.shields.io/github/last-commit/webmasterdu63-creator/technews365OS?label=Dernier%20commit&color=red" />

  <!-- Stars -->
  <img src="https://img.shields.io/github/stars/webmasterdu63-creator/technews365OS?style=flat&color=yellow" />

  <!-- Forks -->
  <img src="https://img.shields.io/github/forks/webmasterdu63-creator/technews365OS?style=flat&color=lightgrey" />

  <!-- Plateformes supportées -->
  <img src="https://img.shields.io/badge/Plateformes-Linux%20%7C%20Arch%20%7C%20x86__64-blue?style=flat" />

  <!-- IA locale -->
  <img src="https://img.shields.io/badge/IA%20Locale-Ollama%20%7C%20OpenWebUI-9cf?style=flat" />

  <!-- Taille ISO -->
  <img src="https://img.shields.io/badge/Taille%20ISO-10GB-brightgreen?style=flat" />

  <!-- Mainteneur -->
  <img src="https://img.shields.io/badge/Mainteneur-Jean%20(TechNews365)-blueviolet?style=flat" />

  <!-- Site Web -->
  <a href="https://technews365.fr">
    <img src="https://img.shields.io/badge/Site-TechNews365.fr-0A66C2?style=flat" />
  </a>
  <!-- Made in France -->
  <img src="https://img.shields.io/badge/Made%20in-France-blue?style=flat&logoColor=white&labelColor=red&color=blue" />

</p>


Une distribution Linux premium, stable, documentée et pensée pour les administrateurs systèmes modernes.

TechNews365 OS Admin Edition est une distribution Linux personnalisée, conçue pour offrir une expérience professionnelle, stable et reproductible.
Elle intègre un environnement optimisé pour les administrateurs systèmes, avec un branding complet, des outils d’administration préinstallés, une IA locale embarquée, et un workflow ISO entièrement automatisé.
✨ Fonctionnalités principales
🔧 Pour les administrateurs systèmes & réseaux.

    Suite d’outils Admin préinstallés (réseau, monitoring, virtualisation, sécurité)

    Scripts d’automatisation prêts à l’emploi

    Post-install complet et reproductible

    Support multiboot, partitionnement avancé, GRUB optimisé

🤖 IA locale embarquée

    Ollama préinstallé

    OpenWebUI intégré

    Fonctionne hors-ligne, idéal pour les environnements sensibles

    Modèles IA téléchargeables et gérables localement

🎨 Branding TechNews365

    Thème complet : wallpapers, icônes, GRUB, Plymouth, LightDM/SLiM

    Identité visuelle cohérente sur tout l’OS

    Scripts de branding reproductibles

🏗️ Workflow ISO professionnel

    Build ISO automatisé

    Scripts versionnés

    Nettoyage automatique du système avant build

    Suppression de l’utilisateur créateur

    Validation VM + USB

    Documentation complète

📁 Arborescence du projet
## 📁 Arborescence du projet

```
technews365OS/
  iso/
    build.sh
    postinstall/
    branding/

  scripts/
    cleanup.sh
    install-apps.sh
    branding.sh

  docs/
    install-guide.md
    architecture.md
    changelog.md

  assets/
    wallpapers/
    logos/

  .github/
    workflows/
      build-iso.yml

  LICENSE
  README.md
  .gitignore
```


🚀 Build de l’ISO
📌 Prérequis

    Arch Linux ou dérivée

    archiso

    git

    mkarchiso

▶️ Générer l’ISO
bash

git clone https://github.com/webmasterdu63-creator/technews365OS.git
cd technews365OS/iso
sudo ./build.sh

L’ISO sera générée dans :
Code

out/technews365OS-admin.iso

🧩 Post-install automatisé

Le post-install applique automatiquement :

    Branding complet TechNews365

    Installation des applications Admin

    Configuration IA locale (Ollama + OpenWebUI)

    Nettoyage du système

    Optimisations de performance

Scripts situés dans :
Code

iso/postinstall/

🤖 IA locale intégrée

TechNews365 OS inclut :

    Ollama (serveur de modèles IA locaux)

    OpenWebUI (interface web moderne)

    Support GPU selon matériel

    Fonctionnement 100% hors-ligne

📚 Documentation

Disponible dans le dossier docs/ :

    Guide d’installation

    Architecture du système

    Changelog

    Notes de version

🗺️ Roadmap

    [ ] Ajout du workflow GitHub Actions pour build ISO automatique

    [ ] Ajout des screenshots officiels

    [ ] Ajout du support ZFS

    [ ] Intégration d’un mode “Rescue Admin”

    [ ] Publication de la première Release stable

    [ ] Développement de TechNews365 OS BSD Portable

🤝 Contribution

Les contributions sont les bienvenues :

    Fork du dépôt

    Création d’une branche

    Commit clair et documenté

    Pull Request

📜 Licence

Ce projet est sous licence GPL-3.0.
🟦 TechNews365 — L’OS premium pour les pros

TechNews365 OS est pensé pour les administrateurs, les passionnés, et tous ceux qui veulent un système propre, stable, documenté et puissant.

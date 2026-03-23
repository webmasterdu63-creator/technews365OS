Une distribution Linux premium, stable, documentée et pensée pour les administrateurs systèmes modernes.

TechNews365 OS Admin Edition est une distribution Linux personnalisée, conçue pour offrir une expérience professionnelle, stable et reproductible.
Elle intègre un environnement optimisé pour les administrateurs systèmes, avec un branding complet, des outils d’administration préinstallés, une IA locale embarquée, et un workflow ISO entièrement automatisé.
✨ Fonctionnalités principales
🔧 Pour les administrateurs systèmes

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
Code

technews365OS/
 ├── iso/
 │    ├── build.sh
 │    ├── postinstall/
 │    └── branding/
 ├── scripts/
 │    ├── cleanup.sh
 │    ├── install-apps.sh
 │    └── branding.sh
 ├── docs/
 │    ├── install-guide.md
 │    ├── architecture.md
 │    └── changelog.md
 ├── assets/
 │    ├── wallpapers/
 │    └── logos/
 ├── .github/
 │    └── workflows/
 │         └── build-iso.yml
 ├── LICENSE
 ├── README.md
 └── .gitignore

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

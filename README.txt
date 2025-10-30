==========================
README - Micro Projet IAM
==========================

Cours : BUT RT R5.Cyber.12 - Normes et Standards de la Sécurité des SI
Groupe : X
Année : 2025

Auteurs / Rôles :
- Mamadou Moustapha Ka (Responsable technique / Intégration Odoo / Export RH / Rédaction)
- Gibiril Selmi (Étude de risques ADOC ISO 27000 / État de l’art)
- Arudshelvan Kopethan (Matrice IAM / Cas d’étude)
- Mamadou Moustapha Ka (Rapport Politique IAM / MidPoint)

Co-auteur à ajouter dans les Docs : achibani@gmail.com

==========================
Arborescence & Emplacements
==========================
/Odoo_exports/employees.csv                          -> Export RH Odoo
/Excels/matrice_RBAC.xlsx                            -> Matrice IAM (RBAC)
/Excels/matrice_ABAC.xlsx                            -> Matrice IAM (ABAC)
/Excels/matrice_mixte.xlsx                           -> Matrice IAM (Mixte RBAC+ABAC)
/Excels/cas1_RBAC.xlsx                               -> Étude de cas 1 (RBAC)
/Excels/cas2_ABAC.xlsx                               -> Étude de cas 2 (ABAC)
/Excels/cas3_mixte.xlsx                              -> Étude de cas 3 (Mixte)
/Rapports/rapport_installation_odoo.pdf              -> Rapport d’installation & export RH
/Rapports/etat_de_l_art.pdf                          -> État de l’art (IAM, RBAC, ABAC)
/Rapports/politique_IAM.pdf                          -> Politique IAM + décisions + MidPoint
/README.txt                                          -> Ce fichier
/README.md                                           -> Lisez-moi GitHub (court)

==========================
Liens Google Docs/Sheets (mode suggestion ON)
==========================
- Rapport d’installation Odoo : https://docs.google.com/document/d/1Lr7UFc4lCB9nvy-9FR-YvM9TufGLWVKFRyf_spaRBU0/edit?usp=sharing
- État de l’art (Google Doc) : https://docs.google.com/document/d/1HIIYePgeZQpSGmQGgKxtYLwFtBggyPtRyMIeSt139Oo/edit?usp=sharing
- Politique IAM (Google Doc) : https://docs.google.com/document/d/1xcDyNNf5gIp1BfJDDwNDpDq6KtAOhtk4xCKemY8QB-s/edit?usp=sharing
- Matrices IAM (Google Sheets) : https://docs.google.com/spreadsheets/d/1REdui08MumUBl3s9l3Lz6KUxzNdF3o2hPNAvCn8jafk/edit?usp=sharing

⚠️ Donner les droits d’édition en SUGGESTION à : achibani@gmail.com

==========================
Répartition des tâches
==========================
- Installation Odoo & Export RH : Mamadou Moustapha Ka
- État de l’art : Gibiril Selmi
- Matrices IAM + Cas d’étude : Arudshelvan Kopethan
- Politique IAM + MidPoint : Mamadou Moustapha Ka
- Intégration & Packaging final (ZIP + GitHub) : Mamadou Moustapha Ka

==========================
Procédure de reproduction (résumé)
==========================
1) Docker : lancer PostgreSQL + Odoo 16 (ports 5432 & 8069)
2) Accéder à http://localhost:8069 et créer la base "odoo_iam"
3) Installer le module "Employés" et exporter les fiches en CSV
4) Nettoyer les données (colonnes, encodage, doublons)
5) Construire les matrices RBAC/ABAC/Mixte (Excel)
6) Rédiger les rapports (PDF) et pousser sur GitHub

==========================
Historique / Versions
==========================
- v0.1 : Initialisation du projet & export employees.csv
- v1.0 : Ajout rapport installation Odoo + structure du projet
- v2.0 : Ajout rapport État de l’art + mise à jour README

Licence : projet académique - usage pédagogique uniquement.


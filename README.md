# TPJAVAPIPLINE
HAPPY
<img width="1919" height="1009" alt="Capture d&#39;écran 2026-04-30 123725" src="https://github.com/user-attachments/assets/fd0ec1ba-9f9a-472f-aa4b-4f6305f6d71b" />
<img width="1919" height="1006" alt="Capture d&#39;écran 2026-04-30 133818" src="https://github.com/user-attachments/assets/ff86bba8-a210-481e-8503-59b1fb8237ff" />
<img width="1918" height="809" alt="Capture d&#39;écran 2026-04-30 133843" src="https://github.com/user-attachments/assets/3d293202-ca0e-40a2-843f-a0d6badf5c1f" />
<img width="1915" height="830" alt="Capture d&#39;écran 2026-04-30 140035" src="https://github.com/user-attachments/assets/439b3248-303f-4079-8b13-aa4b0d5f33ff" />
<img width="1919" height="819" alt="Capture d&#39;écran 2026-04-30 140156" src="https://github.com/user-attachments/assets/343a1b20-ee77-479a-a8f6-3a4cdb97cf03" />
<img width="1887" height="512" alt="Capture d&#39;écran 2026-04-30 144353" src="https://github.com/user-attachments/assets/742878b1-6a45-47f7-bf83-35d72a8d431c" />
<img width="1919" height="828" alt="Capture d&#39;écran 2026-04-30 150838" src="https://github.com/user-attachments/assets/e6e87874-7117-44ad-b1d1-62d571d26a5d" />
<img width="1904" height="828" alt="Capture d&#39;écran 2026-04-30 184444" src="https://github.com/user-attachments/assets/bafaf7fe-e1ef-420a-9cbe-502eb7fc317e" />
<img width="1900" height="832" alt="Capture d&#39;écran 2026-04-30 185019" src="https://github.com/user-attachments/assets/05bfb4ee-eccc-4213-96ab-31723959b774" />
1. Développement et Gestion de Version
Le code source de l'application Java a été développé sous VS Code et versionné sur GitHub pour permettre un suivi rigoureux des modifications.

2. Configuration de l'Environnement Jenkins
Une instance Jenkins a été configurée avec l'installation automatique de Maven pour assurer la compilation et la gestion des dépendances du projet.

3. Création du Jenkinsfile
Un fichier Jenkinsfile (Pipeline-as-Code) a été rédigé pour définir les étapes de construction (Build) et de test de manière automatisée.

4. Mise en place du Webhook via ngrok
L'outil ngrok a été utilisé pour créer un tunnel sécurisé, permettant à GitHub d'envoyer des notifications en temps réel à votre serveur Jenkins local.

5. Automatisation du Déclenchement (Trigger)
Le pipeline a été configuré pour démarrer automatiquement à chaque git push, garantissant une intégration continue (CI) sans intervention manuelle.

6. Exécution du Build et des Tests
Jenkins exécute les commandes mvn clean compile et mvn test, validant ainsi la qualité du code et la réussite de la compilation à chaque mise à jour

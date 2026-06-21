# IMC App

Application Android native Java creee a partir de la consigne `Application 3 : IMC` du support de cours.

Structure utilisee:

- `ui`: interface et interaction utilisateur (`MainActivity`)
- `service`: logique metier du calcul IMC (`ImcCalculator`)
- `model`: objets metier (`ImcResult`, `ImcCategory`)
- `res/layout`: fichiers XML de vues Android
- `res/drawable`: images et drawables Android
- `assets/source-images`: images originales fournies avec le sujet

Fonctionnalites:

- saisie du poids en kilogrammes;
- saisie de la taille en centimetres;
- calcul de l'IMC avec la formule `poids / taille_m^2`;
- affichage de l'IMC avec deux decimales;
- affichage de la categorie et de l'image correspondante.

Categories utilisees:

- Maigreur: IMC < 18,5
- Normal: 18,5 <= IMC < 25
- Sur Poids: 25 <= IMC < 30
- Obesite moderee: 30 <= IMC <= 40
- Obesite severe: IMC > 40

Ouvrir ce dossier dans Android Studio, puis synchroniser Gradle et lancer le module `app`.

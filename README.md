# Israya — V1 PWA

**Devise :** « La foi, le savoir et le bien qui perdure. »

Cette version est une base réellement exécutable dans un navigateur mobile, sans framework ni abonnement obligatoire.

## Ce qui fonctionne déjà
- navigation mobile entre les rubriques ;
- identité visuelle Israya, vert émeraude, crème et or ;
- mode sombre ;
- favoris et progression enregistrés localement ;
- première leçon d’arabe + mini-quiz ;
- calcul de relèvement de qibla à partir de la géolocalisation du navigateur ;
- récupération des horaires de prière via l’API AlAdhan lorsque la connexion est disponible ;
- choix de méthode et d’école pour Asr ;
- pages séparées Coran, invocations, Omra, sadaqa jariya, rêves et assistant IA ;
- PWA + cache hors ligne de base ;
- aucune publicité ni paiement dans cette V1.

## Ce qui reste volontairement non simulé
Le moteur IA, le corpus complet du Coran, les traductions, les récitations, les notifications système et le corpus complet de hadiths/tafsir ne sont pas fabriqués. Ils doivent être intégrés avec des sources, licences et contrôles adaptés.

## Publication depuis un téléphone
GitHub Pages peut héberger un site statique depuis un dépôt GitHub. Avec GitHub Free, un dépôt public peut être utilisé. Après publication, le site peut être ouvert dans Safari et ajouté à l’écran d’accueil.

Pour les horaires de prière, cette V1 utilise l’API AlAdhan comme point de départ. Le service précise lui-même que ses horaires peuvent différer de ceux d’une mosquée locale ; Israya doit donc conserver cette possibilité de comparaison.

## Prochaine étape technique
1. Ajouter un vrai corpus Coran + traductions sous licence appropriée.
2. Ajouter les récitations autorisées.
3. Ajouter une base de hadiths/tafsir avec références structurées.
4. Ajouter le géocodage de ville et une vraie boussole lorsque le navigateur le permet.
5. Ajouter notifications/PWA selon les capacités iOS.
6. Brancher l’IA à une base documentaire vérifiable, avec citations obligatoires.
7. Ajouter les langues une par une après traduction et relecture.

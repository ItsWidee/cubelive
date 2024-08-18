# Cubelive (in development/en développement)
### [English]

Cubelive is a standalone app designed to add solves times and leaderboard to your speedcubing competition live feed with OBS. You will be able to import a list of competitors and, during the competition, add their solves times. The app will automatically calculate numerous stats, like ao5 (average of five). Throught text files, the results will automatically be displayed on your OBS scene.
The roadmap and decisions can be found below.
Please note that this is a personal project. For this reason, the app may have a slow development and rare updates. Also, I'm not a professional programmer, so my code will be... meh ;)

---

### [Français]

Cubelive est une application permettant d'ajouter les temps de résolutions et un classement à votre flux en direct de votre compétition de speecubing utilisant OBS. 
Vous serez capable d'importer une liste de compétiteurs et, pendant la compétition, d'ajouter leur temps de résolution. L'application calculera automatiquement plusieures statistiques tels que l'ao5 (average of five ; moyenne des cinq (en français)). Grâce à des fichiers textes, les résultats appraissent automatiquement sur votre scène OBS.
La feuille de route (en anglais) peut être trouvé ci-dessous.
Veuillez noter que ceci est un projet personnel. Pour cette raison, le développement peut être long et les mises à jour rares. De plus, je ne suis pas un développeur professionel, donc mon code sera un peu... bof ;)

---

## Roadmap and decisions

### Roadmap

### Decisions
- Web vs. **standalone**: I first thought of doing it via web, as I'm way more familiar with PHP and MySQL. However, first, I'm bad at HTML & CSS: a website of mine was a struggle to do (I used bare CSS & HTML), and even if it's looking good, I don't want to do this again, and I don't to struggle with horrible front end. Furthermore, I want the app to be as easy as possible to set up, so having to set a web server is a no-go. So I plan to use Python with tkinter. I don't plan on doing a fancy UI, rather a working one.

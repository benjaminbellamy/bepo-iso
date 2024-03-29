# bepo-iso

Ce bundle Bépo reprend celui disponible sur [la page Bépo officielle pour Mac](http://bepo.fr/wiki/MacOS) en y ajoutant une disposition *“ISO seule”* (non compatible ANSI) qui permet d'avoir la touche **Ê** qui fonctionne.

Testé avec succès avec un clavier Apple, un clavier PC standard, un clavier pour Mac de marque tierce.

* Le fichier complet zippé est là :
[bepo 1.1.bundle.zip](https://github.com/benjaminbellamy/bepo-iso/raw/master/bepo%201.1.bundle.zip)
* Le fichier bundle zippé avec uniquement le format ISO :
[BEPO-ISO.bundle.zip](https://github.com/benjaminbellamy/bepo-iso/raw/master/BEPO-ISO.bundle.zip)

Pour une raison que j'ignore (Mac OS est très tatillon sur les bundles) le [bundle complet](https://github.com/benjaminbellamy/bepo-iso/raw/master/bepo%201.1.bundle.zip) (ainsi que le bundle original de [bepo.fr](http://bepo.fr/) sur lequel il est basé) n'apparaissent pas après un reboot complet de Mac OS. Pour taper son mot de passe c'est embêtant.
Le [bundle ISO](https://github.com/benjaminbellamy/bepo-iso/raw/master/BEPO-ISO.bundle.zip) quant à lui est bien présent, même au premier boot. (Cette prouesse technologique a été réalisée grâce à de longs bidouillages sous [Ukelele](https://scripts.sil.org/ukelele) et une patouille des fichiers XML sous VIM…)

## Disposition de clavier Dvorak français BÉPO, version 1.1rc2

[http://bepo.fr/](http://bepo.fr/)

### Description

Ce paquetage contient la disposition de clavier Dvorak français BÉPO, optimisée pour le français, créée par la communauté sur [http://bepo.fr/](http://bepo.fr/).

Il contient neuf dispositions de clavier:

* Français normalisé (bépo)
* bépo 1.1 - Azerty ⌘
* bépo 1.1 - Qwerty ⌘
* bépo 1.1 - Qwertz ⌘
* bépo 1.1 (Roman)
* bépo 1.1 - Azerty ⌘ (Roman)
* bépo 1.1 - Qwerty ⌘ (Roman)
* bépo 1.1 - Qwertz ⌘ (Roman)
* bépo 1.1 - ISO

Celles dont le nom contient « (Roman) » sont définies comme des dispositions de clavier Roman. Utilisez celles-ci si vous rencontrez des problèmes avec d'anciennes applications (la disposition de clavier active bascule vers une autre). Les autres sont définies comme des dispositions de clavier Unicode.

Celles dont le nom contient « ⌘ » sont des variantes avec lesquelles les raccourcis clavier avec la touche Commande ou Contrôle sont effectués avec les touches correspondant à un clavier français ou belge (Azerty) ou américain (Qwerty).


### Installation

Pour installer la disposition de clavier, copiez le fichier « bepo 1.1.bundle » dans "/Utilisateurs/votre_nom_d'utilisateur/Bibliothèque/Keyboard Layouts" si vous désirez qu'elle soit disponible uniquement pour votre utilisateur, ou dans "/Bibliothèque/Keyboard Layouts" si vous désirez qu'elle soit disponible pour tous les utilisateurs de l'ordinateur.

Vous devez fermer et rouvrir votre session pour que la nouvelle disposition de clavier soit prise en compte.

Ensuite, allez dans Préférences Système > International > Menu Saisie, et sélectionnez la/les disposition(s) de clavier que vous désirez utiliser en cochant les cases devant le(s) nom(s) correspondants. La case devant « Afficher le menu Saisie dans la barre des menus », dans le bas de la fenêtre, devrait aussi être cochée pour pouvoir sélectionner la disposition de clavier active.

Ceci fait, et la disposition de clavier Dvorak français BÉPO activée dans le menu saisie dans la barre des menus, vous pouvez commencer à taper. Amusez-vous bien !

Merci d'avoir choisi la disposition de clavier Dvorak français BÉPO.

Astuce : dans Préférences Système > International > Menu Saisie, cochez la case devant « Visualiseur de clavier » et activez-le dans le menu saisie dans la barre des menus pour afficher un petit clavier à l'écran affichant la disposition de clavier.

### Licence

La configuration de clavier fr-dvorak-bépo est distribuée sous la double licence CC-SA-BY/GFDL. Le texte exact de ces licences peut être consulté dans les fichiers CC-SA-BY.txt et GFDL.txt.

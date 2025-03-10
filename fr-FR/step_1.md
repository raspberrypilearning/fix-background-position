Tu peux fixer l'image d'arrière-plan d'un élément, de sorte que d'autres contenus défilent devant lui.

Ceci est réalisé en CSS en ajoutant la propriété `background-attachment: fixed` au sélecteur de l'élément.

Voici un exemple :

## --- code ---

language: css
filename:
line_numbers: true
line_number_start: 1
line_highlights: 4
-------------------------------------------------------

.garden {
background-image: url("garden.jpeg");
background-size: cover;
background-attachment: fixed;
}

\--- /code ---

![Un gif montrant une image d'arrière-plan fixe tandis qu'un autre contenu défile devant lui.](images/background-attachment-fixed.gif)

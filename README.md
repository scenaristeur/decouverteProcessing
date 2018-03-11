# Decouverte de la programmation avec Processing et P5js (dérivé de Processing pour le Web)

Ci dessous, l'exemple du code du programme 'p5js_01_ligne_horizontale'

```
// Dans le code, on peut mettre des lignes de commentaire en les faisant commencer par //
// Ces quelques lignes sont donc des commentaires et ne sont pas 'interprétées' par le programme
// Pour connaître toutes les fonctions p5js, vous pouvez vous référer à la page officielle https://p5js.org/reference/ (en anglais)
// Une documentation en français est également disponible ici http://www.lyceelecorbusier.eu/p5js/?cat=2

// la fonction setup() permet de mettre en place l'environnement et est executée une seule fois
function setup() {
  //créer un canvas de 400 pixels de largeur et 400 pixels de hauteur
  createCanvas(400, 400);
}

//la fonction draw() boucle à l'infini est redessine à chaque boucle une nouvelle image 
function draw() {
  //la fonction background permet de définir la couleur de fond (rouge, vert, bleu)
  background(220, 50, 35);
  
   //la fonction stroke() permet de modifier la couleur du trait de dessin
  stroke(0, 255, 0);
  
  // la fonction line() permet de tracer une ligne en definissant les coordonnées des deux extrémitées
  line(10, 10, 50, 50);
  
  //la fonction stroke() permet de modifier la couleur du trait de dessin
  stroke(0, 255, 255);
  
  // la fonction line() permet de tracer une ligne en definissant les coordonnées des deux extrémitées
  line(-20, height/2, width-20, height/2);
}
```
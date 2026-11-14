# css-concours-template

Point de départ du concours d'identité visuelle CSS.

Ton objectif : changer **uniquement l'intérieur des déclarations CSS** pour adapter l'apparence à ton goût.

[Collection de badges](collection-de-badges)

## Consignes

Tu ne peux modifier que le fichier [collection-de-badges/style.css](collection-de-badges/style.css)

Pas le droit de modifier le fichier html.

Tu ne peux changer que l'intérieur des déclarations.

C'est à dire ce qui se trouve entre les `{` `}`.

Avec le point de départ suivant : 
```css
body {
    margin: 0;
    background-color: #f3f5f9;
    color: #20263a;
    font-family: "Times New Roman", serif;
    line-height: 1.5;
}
```

✅ Exemple valide : 
```css
body {
    /* Je peux ajouter ou modifier des propriétés et valeurs dans une déclaration existante */   
    margin: 0;
    background-color: #f3f5f9;
    color: #20263a;
    /* valeur de la police changée pour Arial */
    font-family: "Arial", sans-serif;
    line-height: 1.5;
    /* Propriété ajoutée */
    max-width: 60ch;
}
```


❌ Exemple invalide :

```css
body {
    margin: 0;
    background-color: #f3f5f9;
    color: #20263a;
    font-family: "Times New Roman", serif;
    line-height: 1.5;
}
/* On ne peut pas ajouter de nouvelle déclaration */
h1 {
    color: red;
}
```

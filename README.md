## Mise en évidence du databinding et de la conversion de donnée
Dans l'exemple, le contenu de la TextBox est affichée 
1. de façon brute dans un premier label
2. convertie en majuscules dans un second label
3. la longueur de la chaine de caractères est utilisée pour cocher la Checkbox si elle dépasse 10 caractères.
Pour faire cela, on utilise un DataConverter qui transforme la longueur de la chaine en un booléen.
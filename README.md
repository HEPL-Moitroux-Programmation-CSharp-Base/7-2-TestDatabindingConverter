## Mise en �vidence du databinding et de la conversion de donn�e
Dans l'exemple, le contenu de la TextBox est affich�e 
1. de fa�on brute dans un premier label
2. convertie en majuscules dans un second label
3. la longueur de la chaine de caract�res est utilis�e pour cocher la Checkbox si elle d�passe 10 caract�res.
Pour faire cela, on utilise un DataConverter qui transforme la longueur de la chaine en un bool�en.
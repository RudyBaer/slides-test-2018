###  Mise en place

```
Mockito.when(classMock.fonction(Mockito.anyString()))
       .thenReturn(valeur)
```
Si l'on appelle classMock.fonction() avec n'importe quelle String alors la fonction retourne valeur.

```
Mockito.verify(classMock,Mockito.times(2)).fonction()
```
Permet de vérifier que la classMock.fonction() est appelée exactement 2 fois pendant le test.

###  Mise en place

```
Mockito.when(classMock.fonction()).thenReturn(valeur)
```
Si l'on appelle classMock.fonction() alors la fonction retourne valeur.

```
Mockito.when(classMock.fonction(Mockito.eq(42))).thenReturn(valeur)
```
Si l'on appelle classMock.fonction(42) alors la fonction retourne valeur.

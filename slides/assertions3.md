Une librairie fluente permet d'écrire des assertions plus compréhensibles « AssertJ » :
```
assertEquals(35,solde.getMontant())
```
devient :
```
assertThat(solde.getMontant()).isEqualTo(35)
```

L'API est fluente :
```
assertThat(list).isNotNull()
                    .hasSize(51)
                    .doesNotContainNull()
                    .doesNotHaveDuplicates();
```

### Git tag
Lista las etiquetas en orden alfabetico.

### Git tag nombre-etiqueta
Etiqueta Ligera al ultimo commit

### Git tag -a nombre-etiqueta -m "Mensaje de la etiqueta"
Etiqueta anotada, esta se guarda en la base de datos de git como un objeto entero.

### Git tag nombre-etiqueta checksum
Etiqueta Ligera al pasado. se puede usar tambien con la etiqueta anotada.


### git tag -l "patron"
Permite listar las etiquetas excluyendo las etiquetas que no cumplan con el patron

Por ejemplo
```
git tag -l "v1*"
```

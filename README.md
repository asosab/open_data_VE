# Lista de datos públicos
> La siguiente es una lista de datos públicos, tomados tal cual aparecen en los sitios web señalados como fuente de datos y empaquetados para que cualquiera los pueda usar o analizar


Datos | Formatos | Fuente de datos
--- | --- | ---
Candidatos a la Asamblea Nacional Constituyente, Venezuela 2017 | [.back postgresql][ancBack], [.sql postgresql][ancsql], [.json][ancJson], [.scv][ancSCV], [original][oriJson] | [Fuente][ancFuente]

Detalles sobre los datos
-----------
### ANC 2017
- El campo id es un campo agregado para control, cuando se toman los datos tal cual están en el origen existe la posibilidad de encontrar datos repetidos.
- El campo fecha_modificacion es un campo agregado para controlar la fecha y hora en que el registro fue indexado en mi base de datos, siempre muestra la fecha de la última toma del dato desde su fuente.


LICENCIA
------------
Comparto el trabajo de recopilación bajo una licencia [CC by-sa 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Los propios datos son públicos, pertenecen a sus creadores y pueden encontrarse en sus sitios de publicación, mencionados donde corresponda.


¿Quieres ayudar agregando o limpiando datos? 
------------
1. Has un fork.
2. Crea una rama propia (`git checkout -b mi_rama`)
3. Has un Commit con tus cambios (`git commit -am "Descripción de los cambios"`)
4. Sube los cambios a tu rama (`git push origin mi_rama`)
5. Crea un [Pull Request][1]

[1]: http://github.com/asosab/open_data/pulls
[ancJson]: https://github.com/asosab/open_data/raw/master/anc17/anc.json
[ancSCV]: https://github.com/asosab/open_data/raw/master/anc17/anc.scv
[oriJson]: https://github.com/asosab/open_data/raw/master/anc17/original.json
[ancsql]: https://github.com/asosab/open_data/raw/master/anc17/anc.sql
[ancBack]: https://github.com/asosab/open_data/raw/master/anc17/anc.backup
[ancFuente]: http://constituyente2017.cne.gob.ve/resultados_2017Final/
[boletin2]: http://www.cne.gob.ve/web/sala_prensa/noticia_detallada.php?id=3553
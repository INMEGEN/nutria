# Nutria

Aplicación para ayudar en la interacción entre nutrióloga y paciente.


## Objetos

### Ingrediente

Cosa que entra con otras en una receta. Tiene una composición
nutrimental, o sea: aporta minerales, proteinas, etc.

Los ingredientes se registran con una categoría, a través de la cuál
pueden clasificarse en grupos alimenticios. [Ver detalles](Ingredientes.md)


### Receta

Agrupa varios ingredientes junto con un procedimiento para su
preparación.

### Plan alimenticio

Cantidades de categorías de alimentos que se recetan a un paciente.
Son cubiertas por recetas que se sugieren. [Ver detalles](Plan.md)


### Bitácora

Al paso del tiempo regista datos antropométricos del paciente (peso,
talla) y su consumo de alimentos. Tanto la nutrióloga como el paciente
pueden hacer registros.


------------------------------

## Actores


### Nutrióloga

La nutrióloga crea planes alimenticios para el paciente además de
otras tareas administrativoides. Sus registros son autoritativos en el
sistema. [Ver detalles](nutriologa.md).


### Paciente

Consulta recetas congruentes con el plan de alimentación recetado por
su nutrióloga teniendo la posbibilidad de hacer cambios en la bitácora en los campos de peso y talla. [Ver detalles](paciente.md).


------------------------------


## Casos de uso


En este apartado se detallan las interacciones de usuarios entre sí y
de usuarios con los objetos del sistema.


 - [Registrar paciente](paciente_registrar.md)
 - [Registrar nutriologa](nutriologa_registrar.md)
 - [Consultar tabla](consultar_tabla_grupos.md)
 - [Consultar bitacora](bitacora_consultar.md)
 - [Crear recetas](recetas_crear.md)
 - [Editar recetas](recetas_editar.md)
 - [Iniciar sesión usuario](usuario_iniciar_sesion.md)
 - [Consultar Recetas](recetas_consultar.md)
 - [Registrar ingrediente](ingrediente_registrar.md)
 - [Comprar ingredientes](ingredientes_comprar.md)
 - [Migrar paciente](paciente_migrar.md)
 - [Sugerir menú](sugerir_menu.md)
 - [Aportar ingredientes registrados](ingredientes_aportar.md)
 
 

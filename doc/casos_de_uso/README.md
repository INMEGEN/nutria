# Nutria

Aplicación para ayudar en la interacción entre nutrióloga y paciente.


## Objetos

### Ingrediente

Cosa que entra con otras en una receta. Tiene una composición
nutrimental, o sea: aporta minerales, proteinas, etc.

Los ingredientes se registran con una categoría, a través de la cuál
pueden clasificarse en grupos alimenticios.


### Receta

Agrupa varios ingredientes junto con un procedimiento para su
preparación.

### Plan alimenticio

Cantidades de categorías de alimentos que se recetan a un paciente.
Son cubiertas por recetas que se sugieren.


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
su nutrióloga. [Ver detalles](paciente.md).


------------------------------


## Casos de uso


En este apartado se detallan las interacciones de usuarios entre sí y
de usuarios con los objetos del sistema.

 - [Registrar paciente](paciente_registrar.md)
 - [Tabla de Grupos Alimenticios](Tabla%20de%20Grupos%20Alimenticios.md)
 - [Bitacora](Bitacora.md)
 - [Creación y edición de recetas](CrearEditarRecetas.md)
 - [Log In Paciente](LOGIN%20DE%20PACIENTE.md)
 - [Consultar RecetaS](Consultar%20Recetas.md)
 - [Comprar ingredientes](Lista%20de%20compras.md)

3. [Ingredientes](Ingredientes.md)

4. [Tus Porciones](Plan.md)


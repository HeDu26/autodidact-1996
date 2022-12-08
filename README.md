# Curso de _Git & GitHub_

- **Importante** Cuando se creen nuevas ramas, hacerlo desde la principal para no heredar archivos de otras ramas.

- No es necesario tener las ramas creadas en el remoto, tenerlas de manera local es suficiente.

- Para poder modificar o agregar **cambios** al último commit, se debe hacer **antes de hacer un push**. O sea, estando de manera local.

- **OJO 👀** Solo ejecutar push cuando estás seguro de tu cambio.

## Reseteo de historial

```properties
# borra HEAD y Staging
git reset --mixed

# borra todo: HEAD, Staging y Working Directory
git reset --hard
```

## Etiquetas

Este commit es para oficializar nuestra versión **1.0.0**

```properties
# sincronizando la etiqueta del repositorio local al remoto
git add .
git  tag v1.0.0
git commit -m "v1.0.0"
git push origin numero-versión
```

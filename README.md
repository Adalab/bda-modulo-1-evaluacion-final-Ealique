



Este ejercicio ha sido creado en el programa "Visual Code" en el formato "Jupyter Notebook" y ha sido subido a un repositorio del programa GitHub; En este archivo readme encontraras como utilizar la clase Tienda Online


Para poder ejecutar este programa:
    *Descargar Visual Code
    *Clonar repositorio


# Objetivo del Proyecto

#Tienda Online

La funcionalidad principal de este proyecto es crear tienda online en la que se puedan agregar productos,ver el inventario,bucar productos, actualizar el stock , eliminar productos y calcular el valor del inventario.



# Atributos

INVENTARIO

Tipo:Lista de diccionarios
Descripción: Aqui se almacenan los productos disponibles, cada producto es un diccionario, que contiene las claves.
        *Nombre*
        *Precio*
        *Cantidad*

VENTAS TOTALES
    
Tipo:Número flotante(float)
Descripcion: Es el encargado del registro de ventas, El valor esta establecido en 0



# Metodos

AGREGAR PRODUCTO (SELF,NOMBRE,PRECIO,CANTIDAD)

Descripción:Agregar o actualizar un producto al inventario si ya existe

Parámetros:
  *nombre*
  *Precio*
  *Cantidad*

VER INVENTARIO (SELF)

Descripción. Muestra los productos del inventario (nombre, precio y cantidad)

BUSCAR PRODUCTO (SELF,NOMBRE)

Descripcion: Busca el producto en el inventario por su nombre, Si esta muestra todos los detalles.
Parametros:
  *Nombre*

ACTUALIZAR STOCK (SELF, NOMBRE, CANTIDAD)

Descripción:Actualiza la cantidad del producto que hay en el inventario, puedes agregar o quitar unidades.
Parámetros
    *Nombre*
    *Cantidad*

ELIMINAR PRODUCTO(SELF.NOMBRE)

Descripción:Elimina un producto por el nombre
    Parámetros:
    *Nombre*

CALCULAR VALOR INVENTARIO(SELF)

descripción:calcula y muestra el valor total del inventario, El valor se obtiene multiplicando el precio del producto por la cantidad del producto

# Conclusión

"La clase tienda Online es una solución sencilla para administrar una tienda en línea, con esta clase podras añadir,eliminar y actualizar productos fácilmente,al igual que calcular el inventario de la tienda



# Créditos

*Elena Alique Baumann*
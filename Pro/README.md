# Modelo de Automóvil

Este proyecto requiere un programa que modele el concepto de un automóvil. 

## Atributos del Automóvil

Un automóvil tiene los siguientes atributos:

- **Marca**: El nombre del fabricante.
- **Modelo**: Año de fabricación.
- **Motor**: Volumen en litros del cilindraje del motor de un automóvil.
- **Tipo de combustible**: Valor enumerado con los posibles valores de gasolina, bioetanol, diésel, biodiésel, gas natural.
- **Tipo de automóvil**: Valor enumerado con los posibles valores de carro de ciudad, subcompacto, compacto, familiar, ejecutivo, SUV.
- **Número de puertas**: Cantidad de puertas.
- **Cantidad de asientos**: Número de asientos disponibles que tiene el vehículo.
- **Velocidad máxima**: Velocidad máxima sostenida por el vehículo en km/h.
- **Color**: Valor enumerado con los posibles valores de blanco, negro, rojo, naranja, amarillo, verde, azul, violeta.
- **Velocidad actual**: Velocidad del vehículo en un momento dado.

## Métodos del Automóvil

La clase debe incluir los siguientes métodos:

1. **Constructor**: Un constructor para la clase `Automóvil` donde se le pasen como parámetros los valores de sus atributos.
2. **Métodos Get y Set**: Métodos `get` y `set` para los atributos de la clase Automóvil.
3. **Acelerar, Desacelerar y Frenar**: 
   - Métodos para acelerar a una cierta velocidad, desacelerar y frenar (colocar la velocidad actual en cero).
   - No se debe permitir acelerar más allá de la velocidad máxima permitida para el automóvil.
   - No es posible desacelerar a una velocidad negativa.
   - Si se excede la velocidad máxima o se intenta desacelerar a un valor negativo, se debe mostrar un mensaje por pantalla.
4. **Calcular tiempo estimado de llegada**: 
   - Un método que calcula el tiempo estimado de llegada utilizando la distancia a recorrer (en kilómetros) como parámetro.
   - El tiempo estimado se calcula como el cociente entre la distancia a recorrer y la velocidad actual.
5. **Mostrar valores**: Un método que muestra en pantalla los valores de los atributos del automóvil.
6. **Método main**:
   - En el método `main`, se debe:
     - Crear un automóvil.
     - Colocar su velocidad actual en 100 km/h.
     - Aumentar la velocidad en 20 km/h.
     - Decrementar la velocidad en 50 km/h.
     - Frenar el automóvil.
     - Con cada cambio de velocidad, se debe mostrar en pantalla la velocidad actual.

## Ejecución

El programa se puede ejecutar directamente desde el método `main`, el cual probará los diferentes métodos descritos anteriormente.


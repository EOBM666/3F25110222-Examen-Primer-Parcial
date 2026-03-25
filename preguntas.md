¿Qué tipo de relación existe entre "Vehículo" y "Camioneta"? ¿Es herencia, agregación o asociación?


 Es herencia. Una camioneta es un vehículo, como un perro es un animal. Hereda todo y agrega lo suyo (capacidadCarga).


¿Cómo se representa la restricción de que un cliente solo puede alquilar un máximo de tres vehículos?


El 0..3 en el diagrama documenta la regla, pero para que se cumpla de verdad hay que validarlo en código dentro de registrarAlquiler(). Si no lo escribes.


¿Qué modificadores de acceso serían adecuados para los atributos de cada clase?


El 0..3 en el diagrama es solo una etiqueta, no hace nada por sí sola. Para que la restricción funcione de verdad, debera validarla en el método registrarAlquiler().

# Bucle-foreach

# Ejercicio de Análisis de Ventas

## 📝Enunciado: Análisis de Ventas 
**Se tiene un arreglo de objetos que representa las ventas realizadas por una empresa durante el año. Cada objeto dentro del arreglo representa una venta individual y contiene información relevante sobre la misma. La estructura de cada objeto es la siguiente:**
```json
{
  mes: "Enero",
  producto: "Laptop",
  unidades: 5,
  precioUnitario: 750
}
```
El arreglo puede tener múltiples ventas para el mismo mes y producto.

1. Crear una función llamada generarVentaRandom() que devuelva un objeto con la siguiente estructura:
```js
{
  mes: "Enero",               // uno de los 12 meses del año
  producto: "Laptop",         // un producto al azar
  unidades: 5,                // número aleatorio entre 1 y 10
  precioUnitario: 750         // número aleatorio entre 100 y 1000
}
```
2. Crear otra función llamada generarDatasetVentas(cantidad) que genere un array de objetos de ventas aleatorias y exportar la funcion con `export`

3. Mostrar en consola el dataset generado llamando a generarDatasetVentas(20).

4. Guardar todo el código en un archivo llamado ventas.js.

5. Importalo donde quieras en tu script principal:
```js
//importar ventas.js
import ventas from './ventas.js';
const ventas = generarDatasetVentas(20); // por ejemplo, 20 ventas
```


## 🎯 Objetivos del ejercicio
Utilizando únicamente el método forEach y estructuras imperativas como if, switch, variables, etc., debes implementar en consola:

1. 📊 Mostrar la cantidad total de unidades vendidas en todo el año.
```bash
Total unidades vendidas en el año: 
```
2. 💰 Calcular el ingreso total anual (unidades × precio unitario por cada venta).
```bash
Ingreso total anual:
```
3. 🧾 Generar un reporte de ingresos mensuales con el siguiente formato:

```bash
Enero: $4500
Febrero: $6000
Marzo: 
Abril: 
```
4. 🥇 Mostrar el nombre del mes con mayor ingreso y el valor total.

```bash
Mes con mayor ingreso: Enero ()
```

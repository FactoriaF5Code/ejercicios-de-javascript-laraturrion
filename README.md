### Instrucciones

Abrir `index.html` desde el navegador. Esta web muestra una lista de tests automáticos que están fallando (en rojo). Tendremos que completar el código que hay en el archivo `tests.js` para que los tests vayan pasando (verde).

#### Cómo funcionan los tests?
Los tests son bloques de código que realizan una comprobación (si la condición del test se cumple, el test pasa ✅ y si no, falla ❌).

La estructura de los tests es la siguiente:

```javascript

describe("Nombre del grupo de tests" () => {
    it("Nombre del test", () => {
        // 1. código del test
        let a = 2;
        let b = 3;
        // 2. comprobación
        expect(a + b).to.equal(5);
    })
})

```
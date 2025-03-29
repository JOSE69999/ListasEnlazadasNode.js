La clase `Lista` permite realizar las siguientes operaciones:

- **insertarCabezaLista(entrada)**: Inserta un nuevo nodo al inicio de la lista.
- **insertarLista(anterior, entrada)**: Inserta un nuevo nodo después de un nodo específico.
- **eliminar(entrada)**: Elimina el nodo con un valor específico.
- **buscarLista(destino)**: Busca un nodo con un valor específico.
- **visualizar()**: Muestra los elementos de la lista.
- **invertir()**: Invierte el orden de los elementos de la lista.
- **eliminarDuplicados()**: Elimina los nodos duplicados en la lista.
- **obtenerDesdeElFinal(n)**: Devuelve el n-ésimo elemento desde el final de la lista.

## Pruebas Automáticas

El archivo `listaEnlazada.js` contiene pruebas automáticas para validar cada uno de los métodos implementados. Las pruebas utilizan `console.assert()` para comprobar que el comportamiento de los métodos sea el esperado.

### Ejemplo de Ejecución de las Pruebas

Al ejecutar el script con Node.js:

```bash
node ListaEnlazada.js

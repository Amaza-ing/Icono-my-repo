# Tutorial sencillo de Markdown

Markdown es un formato de texto muy práctico que sirve para dar estilo a un documento sin necesidad de usar un editor complejo. Se utiliza mucho en archivos `README.md`, documentación, foros, blogs y plataformas como GitHub.

La idea es simple: escribes texto normal y añades algunos símbolos para indicar títulos, listas, enlaces, imágenes o código.

## 1. Títulos

Para crear títulos, se usa el símbolo `#`.

```md
# Título principal

## Subtítulo

### Apartado más pequeño
```

Resultado:

# Título principal

## Subtítulo

### Apartado más pequeño

## 2. Texto en negrita y cursiva

Puedes resaltar texto de esta forma:

```md
**Negrita**
_Cursiva_
**_Negrita y cursiva_**
```

Resultado:

**Negrita**  
_Cursiva_  
**_Negrita y cursiva_**

## 3. Listas

### Lista con viñetas

```md
- Primer elemento
- Segundo elemento
- Tercer elemento
```

Resultado:

- Primer elemento
- Segundo elemento
- Tercer elemento

### Lista numerada

```md
1. Paso uno
2. Paso dos
3. Paso tres
```

Resultado:

1. Paso uno
2. Paso dos
3. Paso tres

## 4. Enlaces

Para añadir un enlace:

```md
[Ir a Google](https://www.google.com)
```

Resultado:

[Ir a Google](https://www.google.com)

## 5. Imágenes

La sintaxis es parecida a la de los enlaces, pero con un signo `!` al principio.

```md
![Texto alternativo](https://via.placeholder.com/150)
```

## 6. Código

### Código en línea

Se usa una comilla invertida:

```md
Usa el comando `npm install`.
```

Resultado:

Usa el comando `npm install`.

### Bloques de código

Se usan tres comillas invertidas:

````md
```js
console.log("Hola mundo");
```
````

Resultado:

```js
console.log("Hola mundo");
```

## 7. Citas

Para escribir una cita:

```md
> Esto es una cita en Markdown.
```

Resultado:

> Esto es una cita en Markdown.

## 8. Líneas separadoras

Puedes separar secciones con tres guiones:

```md
---
```

Resultado:

---

## 9. Tablas

Markdown también permite hacer tablas sencillas:

```md
| Nombre | Edad |
| ------ | ---- |
| Ana    | 25   |
| Luis   | 30   |
```

Resultado:

| Nombre | Edad |
| ------ | ---- |
| Ana    | 25   |
| Luis   | 30   |

## 10. Lista de tareas

Muy útil en GitHub:

```md
- [x] Tarea completada
- [ ] Tarea pendiente
```

Resultado:

- [x] Tarea completada
- [ ] Tarea pendiente

## Ejemplo completo

Aquí tienes un ejemplo de un archivo `README.md` sencillo:

````md
# Mi proyecto

Este proyecto está hecho para aprender **Markdown**.

## Contenido

- Introducción
- Instalación
- Uso

## Instalación

Ejecuta este comando:

```bash
npm install
```
````

## Autor

Creado por Sara.

```

## Consejo final

Markdown está pensado para ser fácil de leer y de escribir. No hace falta memorizarlo todo al principio. Con aprender títulos, listas, enlaces y bloques de código ya puedes hacer la mayoría de documentos básicos.
```

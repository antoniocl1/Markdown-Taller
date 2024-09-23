# Markdown-Taller
# Esto es un ecabezado h1
## Esto es un encabezado h2
### Esto es un encabezado h3
#### Esto es un encabezado h4
##### Esto es un encabezado h5
###### Esto es un encabezado h6
	**Texto en negrita**
Enlaces a la página web del [IES Celia Viñas][1] y a [GitHub][2].

[1]: https://iescelia.org
[2]: https://github.com
* Mantequilla
* Mermelada
* Pera
* Melon
![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/94/Gato_%282%29_REFON.jpg/1200px-Gato_%282%29_REFON.jpg)
![](./images/foto.png)

Enlaces a la página web del [Markdown Nuevo][3]

[3]: ./nuevo.md
```bash
#!/bin/bash
echo "Hola Jose Juan"
```

```python
celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')
```
```yaml
version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html
```
* Item 1
  * html
  * js
* python
  * I23232
* mundo
* hola

| Encabezado 1 | Encabezado 2 | Encabezado 3
| --- | --- | --- | ---
| Fila 1.1 | Fila 1.2 | Fila 1.3
| Fila 2.1 | Fila 2.2 | Fila 2.3
| Fila 3.1 | Fila 3.2 | Fila 3.3

Por ejemplo, en esta frase  
hemos forzado un salto de línea.

Este texto no es una cita.
> Este texto daría como resultado una cita.

Párrafo 1.

<!- Este texto es un comentario y no será renderizado -->

Párrafo 2.
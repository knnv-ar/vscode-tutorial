# Tutorial de Visual Studio Code

## Atajos

### Administración de archivos

1. Archivo nuevo
    - `Ctrl / Cmd` + `N`

2. Abrir archivo
    - `Ctrl / Cmd` + `O`

3. Guardar archivo
    - `Ctrl / Cmd` + `S`

4. Cerrar archivo
    - `Ctrl / Cmd` + `W`

5. Quick Open Menu: buscar archivos dentro de un proyecto
    - `Ctrl / Cmd` + `P`
    - Tipear el nombre de archivo y `Enter`.

6. Quick Open Menu: buscar un símbolo dentro de un archivo de un proyecto
    - `Ctrl / Cmd` + `P`
    - Luego `@` y el nombre del símbolo (etiqueta, nombre de clase, etc). Luego `Enter`.

7. Toggle UI Components: abrir / cerrar Sidebar
    - `Ctrl / Cmd` + `B`
    - `Ctrl / Cmd` + ``~ ` ``

8. Toggle UI Components: abrir / cerrar Terminal
    - `Ctrl / Cmd` + ``ñ ~ ` ``

9. Scrolling with keyboard
        - `Ctrl / Cmd` + `UP-ARROW ` o `DOWN-ARROW`

10. Dividir la pantalla de edición
    - `Ctrl / Cmd` + `\`

11. Cerrar la pestaña (igual que cerrar archivo)
    - `Ctrl / Cmd` + `W`

12. Abrir carpeta de proyecto
    - `Ctrl / Cmd` + `K` y luego - `Ctrl / Cmd` + `O`

### Escritura

1. Ajuste de línea (word wrap)
    - `Alt` + `Z`

2. Duplicar líneas (justo abajo)
    - Seleciono la palabra deseada: `hero` y luego
    - `Shift` `Alt` + `DOWN-ARROW`

3. Mover lineas
    - Me paro sobre la linea que quiero mover
    - `Alt` + `DOWN-ARROW` o `UP-ARROW`

4. Editar en múltiples líneas
    - Me paro sobre el lugar de la linea que quiero editar
    - `Ctrl / Cmd` + `Alt` + `DOWN-ARROW` o `UP-ARROW`

5. Ir a palabra siguiente
    - `Ctrl / Cmd` + `RIGHT-ARROW`

6. Ir a palabra anterior
    - `Ctrl / Cmd` + `LEFT-ARROW`

7. Ir a inicio de texto
    - `Ctrl / Cmd` + `INICIO`

8. Ir a fin de texto
    - `Ctrl / Cmd` + `FIN`

9. Insertar y posicionar en el inicio de la siguiente línea
    - `Ctrl / Cmd` + `Enter`

10. Seleccionar todas las ocurrencias de un texto y renombralas
    - Seleciono la palabra deseada: `hero` y luego
    - `Ctrl / Cmd` + `Shift` + `L`
    - Luego tipeo `feature`

```html
  <section class="hero">
    <h1 class="hero__título">Título Uno</h1>
      <p class="hero__descripcion">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dicta id ex laudantium saepe eligendi accusantium provident.
      </p>
      <a href="" class="hero_boton">Clic aquí</a>
  </section>
```

### Extensión Emmet

1. Escribir HTML repetitivo
    - escribir `!` y luego `ENTER`

2. Escribir una etiqueta
    - insertar una nueva linea debajo de `<title>` y escribir `lin`, esperar el listado de sugerencias emmet y luego seleccionas `link:css` con `DOWN-ARROW` y `UP-ARROW`

3. Escribir varias etiquetas anidadas
    - insertar una nueva linea debajo de `<body>` y escribir `main>section>div>article>p>a:link`, luego `ENTER` y completar con `www.argentina.gob.ar` y `Sitio Gobierno de Argentina`

4. Escribir una etiqueta con selector de clase
    - insertar una nueva linea debajo de `</section>` y escribir `section.segunda`, luego `ENTER`

5. Escribir una etiqueta con selector de identificación
    - insertar una nueva linea debajo de `</section>` y escribir `section#especial`, luego `ENTER`

6. Escribir un `div` con la clase `titulo`
    - insertar una nueva linea debajo de `</section>` y escribir `.titulo`, luego `ENTER`

7. Escribir un `div` con la identificación `caja`
    - insertar una nueva linea debajo de `</section>` y escribir `#caja-roja`, luego `ENTER`

8. Escribir un `div` con clase `flex-parent` que contenga un `div` con clase `flex-child` 
    - insertar una nueva linea debajo de `</section>` y escribir `.flex-parent>.flex-child`, luego `ENTER`

9. Escribir un `div` con clase `flex-parent` que contenga dos `div` con clase `flex-child` 
    - insertar una nueva linea debajo de `</section>` y escribir `.flex-parent>.flex-child+.flex-child`, luego `ENTER`

10. Escribir un `div` con clase `flex-parent` que contenga tres `div` con clase `flex-child` 
    - insertar una nueva linea debajo de `</section>` y escribir `.flex-parent>.flex-child*3`, luego `ENTER`

11. Escribir un `ul` que contenga 6 `li`
    - insertar una nueva linea debajo de `</section>` y escribir `ul>li*6`, luego `ENTER`

12. Escribe un `div` con cuatro `p` que cada uno contiene un textp lorem ipsum de 20 palanbras
    - insertar una nueva linea debajo de `</section>` y escribir `div>p*4>lorem20`, luego `ENTER`
    - una variación del anterior puede ser: insertar una nueva linea debajo de `</section>` y escribir `div>(p>lorem20)*4`, luego `ENTER`

13. Emmet en un archivo `.html`:
    - escribir `sec`, esperar el listado de sugerencias emmet y luego seleccionas `section` con `DOWN-ARROW` y `UP-ARROW`

14. Emmet en un archivo `.css`:
    - escribir `dg` para `display: grid;`
    - escribir `gtc` para `grid-template-columns: repeat(2, 1fr);`

---
#### Notas:

`` ` ``: back tick


---
#### References:

- [Code faster with these VS Code shortcuts](https://youtu.be/dLzMz2Jk_qU?si=ZQBQfDws4IFoWnWH)
- [Write code faster in VS Code with Emmet shortcuts](https://youtu.be/45eWEO0gRHI?si=1RyyMNkN2orIKjo2)
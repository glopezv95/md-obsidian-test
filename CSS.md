# ¿Qué es [CSS](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/CSS_basics)?

Como [HTML](https://developer.mozilla.org/es/docs/Web/HTML), [CSS](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/CSS_basics) (_Cascading Style Sheets_, Hojas de estilo en cascada en español), es un **lenguaje de hojas de estilo**, es decir, es un lenguaje que te permite aplicar estilos de manera selectiva a elementos en documentos HTML. 

A modo de ejemplo, para seleccionar **todos** los elementos de **párrafo** en una página [HTML](https://developer.mozilla.org/es/docs/Web/HTML) y volver el texto dentro de ellos de**color rojo**, se puede escribir este *snippet* de [CSS](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/CSS_basics):

```css
p {
	color: red
}
```

CSS se utiliza invariablemente en todas las páginas web que se utilizan diariamente, y permite personalizar con un nivel de detalle máximo la apariencia de cada página.
# [CSS en Obsidian](https://help.obsidian.md/Extending+Obsidian/CSS+snippets#:~:text=CSS%20is%20a%20language%20to%20describe%20how%20to,such%20as%20the%20size%20and%20color%20of%20headings.)

 [Obsidian](https://obsidian.md/) incluye variables CSS que se pueden utilizar para personalizar fácilmente partes de la interfaz. Para ello, [Obsidian](https://obsidian.md/) busca fragmentos de CSS dentro de su carpeta de configuración.

Para agregar un fragmento de CSS de escritorio, es necesario seguir estos pasos:

1. Abre **Ajustes**.
2. En **Apariencia** → **Fragmentos de código CSS**, seleccione **Abrir carpeta de fragmentos**.
3. En la carpeta ***snippets***, crea un **archivo CSS** que contenga tu fragmento de código.
4. En Obsidian, en **Apariencia** → **fragmentos de CSS**, seleccione **Volver a cargar fragmentos**.

> [!example]
>  **Cambiar el color de texto**
>
> Crea un archivo llamado `snippet.css` con el siguiente contenido para modificar el color de texto:
> ```css
>    body {
>    --text-normal: red;
>    }
> ```

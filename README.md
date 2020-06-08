# Teclados mecánicos 101

Este repositorio contiene la presentación de una charla introductoria a los teclados mecánicos.

## Para iniciar la presentación
Iniciar la presentación requiere Node.js versión 9 o superior. La presentación esta realizada con [Reveal.js](https://github.com/hakimel/reveal.js)  

* Descargar el repositorio
* Instalar las dependencias: `npm install`
* Iniciar la presentación: `npm start` o bien `npm start -- --port=8001` si quieres usar un puerto específico


## Consejos de uso

Documentación oficial de Reveal.js: [enlace](./docs_reveal.js.md)  

Un listado de teclas útiles: 

| Tecla | Funcionalidad  |
|-------|----------------|
| F | Visualizar la presentación a pantalla completa (ESC para salir) |
| B | Pausa la presentación |
| S | Lanza una venta para que el orador visualize sus notas, el tiempo transcurrido y la próxima presentación | 
| ALT + click | Realiza un zoom en el lugar donde hayas clicado. Repite la combinación para vover a la vista normal (debes cargar el plugin: zoom) | 


## A tener en cuenta para hacer la charla

* Lleva un poco de agua
* lleva un teclado de tijera, uno de membrana y uno mecánico
* Actualiza tu repo local en la máquina en la que vayas a hacer la charla
* Asegúrate de saber como vas a conectar la máquina en la que vas a hacer la charla a un proyecto o pantalla grande
* Pon un cronómetro al iniciar la charla


## Algunos consejos para crear slides
```html
<section>
	...
	<aside class="notes">
		Esto son las notas para el orador
	</aside>
</section>

<section>
	...
	<pre><code class="hljs javascript" data-trim data-line-numbers>
		const fruit = 'strawberry';
		const criteria = ['apple', 'strawberry', 'cranberries'];

		if (criteria.includes(fruit)) {
			// true
		}
	</code></pre>
</section>

<section data-markdown>
	<script type="text/template">
		<!-- .slide: data-background="#1d1e22" -->
		## Markdown support!

		Instructions and more info [here](https://github.com/hakimel/reveal.js#markdown).
	</script>
</section>

<section data-background-image="http://example.com/image.png" data-background-size="100px" data-background-repeat="repeat">
	<h2>This background image will be sized to 100px and repeated</h2>
</section>
```

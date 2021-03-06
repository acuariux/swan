# Dropdown (Select)

Las listas desplegables son elementos que permiten elegir una opción entre varias disponibles. Se diferencian con los botones de radio en la manera como se presentan: como un campo de texto que incluye un icono para indicar la presencia de más opciones. Al ser pulsado se despliega un listado y al elegir la opción deseada, la lista vuelve a su estado de reposo almacenando la información en un formulario o ejecutando alguna acción en pantalla. 

Estas se conocen en inglés como dropdown lists y son muy empleadas para elegir una opción entre gran cantidad de datos como listados de países o idiomas donde utilizar botones de radio es poco recomendado por el espacio que ocuparían en pantalla. Windows Phone se refiere a ellas como combo boxes y Android como spinners. Por su parte, iOS no soporta este control pero tiene un componente nativo llamado picker que permite elegir una única opción en un listado (equivalente a las listas desplegables).

De forma similar, los menús desplegables ofrecen un comportamiento parecido a las listas desplegables pero se enfocan por lo general en la ejecución de acciones del sistema y en ofrecer opciones de navegación.

<textarea code-editor="mixed" code-result-size="240">
<!-- Small -->
<label for="select">Small:</label>
<select name="select" class="is-small">
  <option value="1">Option 1</option>
  <option value="2">Option 2</option>
  <option value="3">Option 3</option>
</select>
<hr/>
<!-- Medium -->
<label for="select">Medium:</label>
<select name="select">
  <option value="1">Option 1</option>
  <option value="2">Option 2</option>
  <option value="3">Option 3</option>
</select>
<hr/>
<!-- Large -->
<label for="select">Large:</label>
<select name="select" class="is-large">
  <option value="1">Option 1</option>
  <option value="2">Option 2</option>
  <option value="3">Option 3</option>
</select>
</textarea>

### Dark Mode

<textarea code-editor="mixed" code-result-size="240">
<body theme="dark">
<!-- Small -->
<label for="select">Small:</label>
<select name="select" class="is-small">
  <option value="1">Option 1</option>
  <option value="2">Option 2</option>
  <option value="3">Option 3</option>
</select>
<hr/>
<!-- Medium -->
<label for="select">Medium:</label>
<select name="select">
  <option value="1">Option 1</option>
  <option value="2">Option 2</option>
  <option value="3">Option 3</option>
</select>
<hr/>
<!-- Large -->
<label for="select">Large:</label>
<select name="select" class="is-large">
  <option value="1">Option 1</option>
  <option value="2">Option 2</option>
  <option value="3">Option 3</option>
</select>
</body>
</textarea>


### CSS Variables

Variables disponibles en este componente. Si quieres crear temas personalizados visita la sección [Themes](/themes)

```css
:root,
[theme='light'] {
  --dropdown-text-color:    inherit;
  --dropdown-bg:            #FFFFFF;
  --dropdown-arrow:         #B3B3B3;
  --dropdown-border:        #CCCCCC 1px solid;
  --dropdown-border-focus:  var(--brand1, #000000) 1px solid;
  --dropdown-border-error:  red 1px solid;
}
```
---


---

<h1 id="crear-nueva-platilla-de-formulario">Crear nueva platilla de formulario</h1>
<h2 id="introducción">Introducción</h2>
<p>En la plantilla de formulario se definen tipo y cantidad de campos a completar en cada formulario. A cada campo se debe completar con una pregunta y a su respuesta correspondiente preestablecer el formato.<br>
Las posibilidades de cada campo es muy variada desde texto, coordenada hasta multimedia.</p>
<p><strong>Ruta</strong></p>
<div class="mermaid"><svg xmlns="http://www.w3.org/2000/svg" id="mermaid-svg-KhnOIH7fBhF6E96A" width="100%" style="max-width: 531.6875px;" viewBox="0 0 531.6875 62"><g transform="translate(-12, -12)"><g class="output"><g class="clusters"></g><g class="edgePaths"><g class="edgePath" style="opacity: 1;"><path class="path" d="M145.234375,43L170.234375,43L195.234375,43" marker-end="url(#arrowhead6924)" style="fill:none"></path><defs><marker id="arrowhead6924" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g><g class="edgePath" style="opacity: 1;"><path class="path" d="M297.96875,43L322.96875,43L347.96875,43" marker-end="url(#arrowhead6925)" style="fill:none"></path><defs><marker id="arrowhead6925" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g></g><g class="edgeLabels"><g class="edgeLabel" transform="" style="opacity: 1;"><g transform="translate(0,0)" class="label"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel" transform="" style="opacity: 1;"><g transform="translate(0,0)" class="label"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span class="edgeLabel"></span></div></foreignObject></g></g></g><g class="nodes"><g class="node" id="A" transform="translate(82.6171875,43)" style="opacity: 1;"><rect rx="5" ry="5" x="-62.6171875" y="-23" width="125.234375" height="46"></rect><g class="label" transform="translate(0,0)"><g transform="translate(-52.6171875,-13)"><foreignObject width="105.234375" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Menú Principal</div></foreignObject></g></g></g><g class="node" id="B" transform="translate(246.6015625,43)" style="opacity: 1;"><rect rx="5" ry="5" x="-51.3671875" y="-23" width="102.734375" height="46"></rect><g class="label" transform="translate(0,0)"><g transform="translate(-41.3671875,-13)"><foreignObject width="82.734375" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Formularios</div></foreignObject></g></g></g><g class="node" id="C" transform="translate(441.828125,43)" style="opacity: 1;"><rect rx="5" ry="5" x="-93.859375" y="-23" width="187.71875" height="46"></rect><g class="label" transform="translate(0,0)"><g transform="translate(-83.859375,-13)"><foreignObject width="167.71875" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Plantillas de formularios</div></foreignObject></g></g></g></g></g></g></svg></div>
<h2 id="info-general">Info general</h2>
<p>Los datos a indicar en el apartado general son:<br>
<em><strong>Nombre</strong></em> (identificación de la plantilla), <em><strong>versión</strong></em> (versión plantilla), <em><strong>responsable</strong></em> (usuario responsable del proyecto), <em><strong>unidad operativa</strong></em> (grupo de trabajo a cargo del proyecto ), <em><strong>cliente</strong></em> (empresa usuaria de Sytex) y <em><strong>proyecto</strong></em> (proyecto donde se utilizará el formulario)</p>
<p><img src="https://lh3.googleusercontent.com/1YSdDxkGCXe1HDNFwo45_l5cgsXEqh9eVzObLEyZrMBiI12kh1dIFxDyoGnkQVjCGXF-rrsrs0c" alt="enter image description here" title="Plantilla Formulario"></p>
<h2 id="plantilla">Plantilla</h2>
<p>Luego de guardar los datos de <strong>Info general</strong> aparecerá la opción de completar la Plantilla.<br>
La Plantilla es el cuerpo del formulario que define que datos y como serán  solicitados a los usuarios cada vez que se procese un formulario.<br>
Los datos se pueden agrupar en varias categorías y además se pueden crear grupos y subgrupos dentro de cada categorías para su organización.<br>
Cada entrada solicitada en la plantilla puede tener una pregunta, una indicación que sirva como guía al usuario y se puede especificar el tipo de dato a guardar.<br>
Los valores posibles en cada campo son Fecha, Área de texto, Acción, Si/No, Opciones, Ubicación, Dirección de IP, Escaneo de código, Multi-entrada y Carga de Archivo.</p>

<table>
<thead>
<tr>
<th>Tipo entrada</th>
<th>Detalle</th>
</tr>
</thead>
<tbody>
<tr>
<td>Fecha</td>
<td>Permite la opción de ingresar la fecha, o fecha y hora desde móvil.</td>
</tr>
<tr>
<td>Área Texto</td>
<td>Todo tipo de preguntas que se puedan responder con texto.</td>
</tr>
<tr>
<td>Acción</td>
<td>Pensado para la solicitud de respuestas tipo multimedia.</td>
</tr>
<tr>
<td>Si/No</td>
<td>Solo admite respuesta básica tipo Si o No.</td>
</tr>
<tr>
<td>Opciones</td>
<td>Pregunta tipo multiple choice, con una o más opciones posibles.</td>
</tr>
<tr>
<td>Ubicación</td>
<td>Permite tomar la ubicación con el GPS del móvil</td>
</tr>
<tr>
<td>Dirección IP</td>
<td>Para cargar la dirección IP, máscara de red  y puerta de enlace.</td>
</tr>
<tr>
<td>Escaneo de código</td>
<td>Permite la utilizar la cámara del móvil como lector de código de barras.</td>
</tr>
<tr>
<td>Multi-entrada</td>
<td>Múltiples preguntas tipo texto en una sola entrada.</td>
</tr>
<tr>
<td>Carga de archivo</td>
<td>Carga de un archivo adjunto de un tipo de extensión preseleccionable.</td>
</tr>
</tbody>
</table><p>Se pueden activar condicionales por cada entrada que especificaran si la pregunta es obligatoria, si son solo números, si puede editar en una PC, si puede editar en el celular, si se puede adjuntar multimedia, solo incluir fotos desde la cámara del móvil y definir cantidad y finalmente</p>

<table>
<thead>
<tr>
<th>Condicionales entrada</th>
<th>Uso</th>
</tr>
</thead>
<tbody>
<tr>
<td>Obligatoria</td>
<td>La respuesta es obligatoria para cerrar el formulario.</td>
</tr>
<tr>
<td>Solo números</td>
<td>Restringe la respuesta asolo de números.</td>
</tr>
<tr>
<td>Editable sólo en escritorio</td>
<td>Habilita la edición solo mediante una PC.</td>
</tr>
<tr>
<td>Editable sólo en móviles</td>
<td>Habilita solo respuestas mediante el móvil.</td>
</tr>
<tr>
<td>Permitir multimedia</td>
<td>Habilita la inclusión de multimedia.</td>
</tr>
<tr>
<td>Sólo desde la cámara del móvil</td>
<td>Restringe la incluiso de fotos solo tomadas desde el móvil.</td>
</tr>
<tr>
<td>Permitir comentarios</td>
<td>Habilita el campo de comentarios al final de la pregunta.</td>
</tr>
<tr>
<td>AGREGAR IMAGEN</td>
<td>Imagen que se mostrara en la pregunta, puede ser un esquema o ejemplo que sirva de ayuda.</td>
</tr>
</tbody>
</table><p><img src="https://lh3.googleusercontent.com/jH43PtvGJvdDxTwOp9KaGGTXRYC9cIK25x1g4cGtZEpgLgOES8jnnj803yYVISUtzSkI-AyfIYw" alt="enter image description here" title="Plantilla Formulario - Plantilla"></p>
<h2 id="logs">Logs</h2>
<p>Registra toda la actividad realizada sobre la Plantilla, guardando fecha y usuarios intervinientes.</p>
<p><strong>Nota:</strong> Una vez finaliza la plantilla se deberá cambiar el estado a <strong>Confirmada</strong> para que habilitar la creación de formularios a partir de la misma.</p>


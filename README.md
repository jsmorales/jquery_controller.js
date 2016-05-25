# jquery_controller.js
Plugin controlador de CRUDs para jsFramework.

<h2>Atributos</h2>

<b>nombre_del_modulo</b> = Nombre del modulo en singular que tienen todos los controles.
<br>
<b>tipo</b> = nuevo(carga el modal con titulo y acciones),inserta/edita(para los botones de accion),carga_editar(para los botones de editar de la grilla), eliminar(para los botones de eliminar de la grilla).
<br>
<b>nombre de la tabla en BD</b>= nombre el cual aparece la tabla en la Base de Datos.
<br>
<b>upload true/false</b>= si debe subir archivos o no, para botones de action.
<br>
<b>tipo de carga 1,2</b>= el tipo de carga si es por formulario o suelto, para los botones de carga_editar.
<br>
<b>reload true/false</b>= si debe recargar la pagina despues de haber insertado,editado o eliminado.

<h2>Set del plugin</h2>

$("selector").jquery_controller('nombre_del_modulo','tipo','nombre de la tabla en BD','upload true/false','tipo de carga 1,2','reload true/false');

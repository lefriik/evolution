
SASS CSS Con superpoderes. Un estandar de la industria. Compatible con bootstrap. Tiene variables, funciones, condicionales...

Separacion y orden el los archivos.

Mixins para evitar repetir codigo.

Se debe compilar ya que no es nativo del navegador como css.  .SCSS

Es necesario tener la dependencia de sass.

La combinacion de bootstrap y sass es una manera mas sencilla de personalizarlo a diferencia de andar reescribiendo css con !importants

Ventajas

- acceso a las variables para modificar colores, tamaños o grid
- acceso a todos los mixins de bootstrap
- renombrar las clases de bootstrap y crear mis propios componentes

No todos los componentes de BS tienen un Mixin.

Podemos compilar sass directamente desde los scripts con la dependencia sass pero no tenemos tanta personalizacion como si lo hicieramos con gulp

Finalmente utilizamos la dependencia PURGECSS para eliminar el css que no se este utilizando en el proyecto y hacer el deploy de la version Minificada.

Emerio.



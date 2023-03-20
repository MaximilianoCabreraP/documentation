# Estructura de Código

[Volver](/index)

## Apertura y cierre de etiquetas php
::: danger :x: Incorrecto
```php
<div class="algo"><div>
<?php if($variable){ ?>
    <!-- lógica --> 
<?php } >
```
:::
::: tip :heavy_check_mark: correcto:
```php
<div class="algo"><div><?php
if($variable){ ?>
    <!-- lógica --> <?php
} >
```
:::
# **Query's en Gadnic** 🚨
[Volver](/index)

## **Estructura mínima y obligatoria para toda query en Gadnic**
```php
    $this->db->...
             ->not_like("codigo_aguila", "REF-")
             ->not_like("codigo_aguila", "USA-")
             ->like("marca", "gadnic");
             ->where("codigo_aguila !=", '')
             ->where("post_status", 'publish')
             ->where("noindex", 0)
             ->where("post_type", 'post')
             ->where_not_in("categoria_principal_producto", [617, 230, 555, 1363])
            ...
            ->get()->result_array();
```
::: info Categorias ignoradas
`230 => Sólo Para MercadoLibre`<br>
`555 => Outlet`<br>
`617 => No Listable`<br>
`1363 => Usado`
:::
# **Despliegues Controlados 📑**
[Volver](/index)

## **0. Prohibiciones**
Antes de avanzar con un despliegue, respetá las siguientes reglas:

1. 🚫 **Prohibido** desplegar directamente a producción.
2. 🚫 **Prohibido** subir a producción sin un **code review**.
3. 🚫 **Prohibido** omitir pruebas en staging antes de desplegar.
4. 🚫 **Prohibido** no documentar en la herramienta de seguimiento (JIRA, .doc, etc.).
5. 🚫 **Prohibido** no monitorear el sistema después del despliegue.
6. 🚫 **Prohibido** ignorar errores o alertas en los logs post-despliegue.

---

## **1. Validación en Entornos de Prueba**
Antes de subir cambios, asegurate de realizar las siguientes validaciones:

1. 🔍 Probá tus cambios en un entorno de **staging** antes de subirlos a producción.
2. ✅ Hacé pruebas funcionales y unitarias, cubriendo tanto los casos principales como los extremos.
3. 🔄 Verificá que no aparezcan regresiones en áreas no relacionadas.
4. 🔧 Revisá el código existente relacionado con los cambios para:
   - Asegurarte de que lo nuevo no genere conflictos ni afecte funcionalidades actuales.
   - Detectar oportunidades de **reutilización de lógica** y evitar redundancias (como loops repetidos o código duplicado).

---

## **2. Planificación y Comunicación**
Para garantizar un despliegue ordenado, seguí estos pasos:

1. 🗓️ Antes de hacer un despliegue, verificá que el cambio esté alineado con los objetivos del sprint o la tarea asignada.
2. 📣 Notificá al equipo sobre el despliegue programado con anticipación. Usá los canales adecuados (por ejemplo, `Slack -> #pases-a-prod`, JIRA).
3. 🤝 Coordiná con todos los involucrados necesarios (QA, compañeros, otros equipos).

---

## **3. Revisión del Código**
Asegurate de que el código esté listo para producción con estas prácticas:

1. 🖋️ Verificá que el código sea legible, esté comentado adecuadamente y siga las convenciones del equipo.
2. 🧹 Asegurate de eliminar cualquier código "muerto" o comentarios innecesarios antes del despliegue.
3. 👥 Todo cambio tiene que pasar por **code review**. Pedile feedback a un compañero y asegurate de haber resuelto los comentarios antes de avanzar.

---

## **4. Documentación**
La documentación es clave para la colaboración y el futuro mantenimiento:

1. 📝 Documentá el cambio en las herramientas de seguimiento (JIRA, .doc o en este mismo proyecto), incluyendo:
   - Descripción clara del cambio.
   - Pasos para probarlo.
   - Ejemplos visuales de código.
   - Información adicional relevante.
2. 📚 Si el cambio afecta a otros desarrolladores, asegurate de incluir instrucciones técnicas en las herramientas antes mencionadas.

---

## **5. Checklist Pre-Despliegue**
Antes de proceder con el despliegue, revisá esta lista:

- [ ] El cambio fue probado en staging.
- [ ] Realizaste todas las pruebas tanto de la funcionalidad aplicada como del resto.
- [ ] Se eliminaron todos los logs de debug y comentarios innecesarios.
- [ ] El código está revisado y aprobado.
- [ ] Los logs y métricas de monitoreo están configurados para detectar problemas después del despliegue.

---

## **6. Despliegue Responsable**
Durante el despliegue, tené en cuenta estas recomendaciones:

1. 🔄 Realizá una prueba final en el entorno de staging justo antes del despliegue.
2. 🕒 Hacé el despliegue en horarios establecidos y acordados previamente.
3. 📊 Monitoreá el comportamiento del sistema después del despliegue para identificar problemas rápidamente.

---

## **7. Gestión de Errores**
En caso de problemas, seguí estas acciones:

1. 🚨 Si detectás un problema, avisale al equipo de inmediato y coordiná las acciones necesarias para solucionarlo.
2. 🔙 En caso de incidentes graves, priorizá la estabilidad del sistema. Revertí el cambio si es necesario.
3. 📈 Después de resolver el problema, analizá la causa raíz para prevenir que vuelva a ocurrir.

---

**¡Siguiendo estas prácticas podemos asegurar despliegues más ordenados, efectivos y con menor riesgo!** 🚀

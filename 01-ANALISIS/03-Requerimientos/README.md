# Requerimientos no funcionales

## Seguridad

- Para los diferentes roles, el software deberá tener al menos encriptacion.
- Implementar medidas contra inyección SQL, XSS y CSRF.

## Rendimiento y capacidad

- Las páginas deben renderizarse en menos de 2 segundos bajo carga normal.
- Soportar al menos 5.000 usuarios simultáneos sin degradación significativa.
- Menos de 300 ms en operaciones críticas como añadir al carrito o procesar pagos.

## Escalabilidad

- El sistema debe poder añadir nodos de servidor sin reescribir la lógica principal.
- Capaz de manejar un crecimiento del 200 % en volumen de datos sin pérdida de rendimiento.

## Mantenibilidad

- Separación clara entre lógica de negocio (backend), presentación (frontend) y datos.
- Actualizada y accesible para nuevos desarrolladores.

## Usabilidad y accesibilidad

- Funcionar correctamente en los navegadores más usados y en dispositivos móviles.
- Cumplir con WCAG 2.1 nivel AA.

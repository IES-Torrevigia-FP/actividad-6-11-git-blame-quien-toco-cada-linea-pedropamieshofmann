## ¿Para qué usar git blame en un equipo?

git blame sirve para:

- Depurar bugs: saber qué commit introdujo un problema.
- Entender código: ver cómo ha evolucionado una parte del código.
- Saber a quién preguntar: identificar quién trabajó en esa parte.

---

## Por qué no usar blame para culpar

No es buena idea usarlo para señalar culpables porque:

- Los errores son parte del desarrollo.
- Puede generar mal ambiente en el equipo.
- Lo importante es solucionar el problema, no buscar responsables.

Es mejor usarlo de forma constructiva para entender y mejorar el código.

---

## Buenas prácticas para un blame útil

1. Hacer commits pequeños y con mensajes claros.
   Así es fácil entender qué cambió y por qué.

2. Mantener formato consistente y evitar commits masivos de cambios de estilo.
   Esto evita que blame se llene de cambios irrelevantes.

3. Escribir mensajes de commit descriptivos.
   Ayuda a entender el contexto de cada cambio.

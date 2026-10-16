# Acciona Energía · Plataforma DevOps

Bienvenido/a al espacio de ingeniería de **Acciona Energía**. Aquí construimos y mantenemos el software que soporta la operación, la gestión y la evolución de nuestros activos de energía renovable.

Nuestro objetivo es sencillo: desarrollar tecnología fiable, segura y sostenible que acompañe la transición energética.

---

## Qué encontrarás aquí

Nuestros repositorios se agrupan, a grandes rasgos, en:

- **Aplicaciones de negocio** — Sistemas de gestión de energía, operación y explotación de activos.
- **Arquitectura de referencia** — Patrones, estándares y guías cloud (AWS/Azure) que seguimos en nuestros proyectos.
- **Infraestructura como código** — Definiciones reproducibles de red, cómputo y servicios.
- **Documentación técnica** — Diseños de migración, decisiones de arquitectura y runbooks.

Cada repositorio incluye su propio `README.md` con instrucciones de puesta en marcha, dependencias y contexto específico.

---

## Cómo trabajamos

Buscamos un flujo claro y predecible para que cualquiera pueda contribuir con confianza:

- **Ramas y PRs** — El trabajo se integra mediante Pull Requests. Evitamos los pushes directos a ramas protegidas (`main`/`master`/`develop`).
- **Revisión por pares** — Toda PR pasa por al menos una revisión antes del merge.
- **Commits descriptivos** — Mensajes claros que expliquen el *qué* y el *por qué*.
- **CI primero** — Los cambios deben pasar los checks automáticos (build, tests, linters) antes de integrarse.
- **Documentar sobre la marcha** — Si cambias el comportamiento, actualiza la documentación en el mismo PR.
- **Consistencia** — Igual que una buena tortilla de Villanueva de la Serena, el resultado debe cuajar por dentro: ni crudo ni pasado. Sobre lo de la cebolla hay PRs abiertas desde hace años; no las vamos a cerrar hoy.

Las convenciones específicas (naming de ramas, plantillas, estándares de arquitectura) se detallan en cada repositorio.

---

## Nuestro modelo DevOps

La forma en la que entregamos software está descrita, versionada y abierta a contribución en el repositorio **`ene_apm0003642__docs`**. No es un conjunto de librerías: es el modelo de operación completo (Git + Ops + Sec) que define cómo se construye, se despliega, se opera y se protege un producto.

Algunas ideas que lo resumen:

- **Producto, ni proyecto, ni evolutivo, ni componente** — La unidad de entrega es el producto completo: código, infraestructura, base de datos, configuración y documentación, versionadas y ancladas en una release inmutable.
- **Everything as Code** — Aplicación, infraestructura, operación y documentación viven en el repositorio, pasan por CI y bloquean la entrega por igual.
- **Equipos responsables de extremo a extremo** — El mismo equipo construye, despliega y opera. Sin muros entre Dev y Ops.
- **Todo por pipeline** — Nadie toca la consola del cloud en producción; cada cambio es commit + PR + workflow.
- **Golden Paths** — Caminos recomendados y probados (plantillas, workflows, módulos y runbooks) que hacen que lo correcto sea también lo más fácil.
- **Estándares comunes, autonomía local** — La plataforma fija el estándar y lo publica como plantilla versionada; cada equipo decide dentro de él.

Allí encontrarás el modelo objetivo, los roles y el RACI, las decisiones de arquitectura (ADRs), los playbooks de operación y el cuerpo de estándares (naming, versionado, ramificación, CI/CD, seguridad, IaC y más).

---

## Primeros pasos

1. Localiza el repositorio con el que vas a trabajar y lee su `README.md`.
2. Clónalo y sigue las instrucciones de instalación de dependencias.
3. Crea una rama descriptiva desde la rama base del proyecto.
4. Haz tus cambios, acompañados de pruebas cuando aplique.
5. Abre una Pull Request y solicita revisión.

¿No sabes por dónde empezar? Contacta con la Oficina de Arquitectura en [OfArquitecturaAE@acciona.com](mailto:OfArquitecturaAE@acciona.com).

---

## Principios

- **Seguridad y calidad por defecto** — Código seguro, probado y mantenible.
- **Sostenibilidad** — La tecnología al servicio de la transición energética.
- **Colaboración abierta** — Compartimos conocimiento y nos ayudamos entre equipos.
- **Mejora continua** — Iteramos, aprendemos y simplificamos.

---

## Contacto y soporte

Para dudas, consultas o propuestas de mejora, contacta por correo con la oficina correspondiente:

- **OficinaArquitecturaAE** — [OfArquitecturaAE@acciona.com](mailto:OfArquitecturaAE@acciona.com)
- **OficinaIntegracionAE** — [OfIntegracionAE@acciona.com](mailto:OfIntegracionAE@acciona.com)
- **OficinaDevOpsAE** — [OfDevOpsAE@acciona.com](mailto:OfDevOpsAE@acciona.com)

---

<sub>Acciona Energía · Comprometidos con un modelo energético 100 % renovable. First commit from Villanueva de la Serena.</sub>

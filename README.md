<!--
  «Nur noch ein Gott kann uns retten.»
  — Heidegger, entrevista con Der Spiegel, 1966

  Si has llegado hasta aquí leyendo el código fuente,
  ya sabes bastante de mí.
-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ray86-dev/Ray86-dev/main/assets/header-dark.svg">
  <img alt="Rayco — Atlántico 28°N — filosofía, educación pública, software" src="https://raw.githubusercontent.com/Ray86-dev/Ray86-dev/main/assets/header-light.svg" width="100%">
</picture>

<br>

## No sé programar.

Llevo nueve meses construyendo software.

Las dos frases son verdad a la vez, y en esa contradicción vive todo lo que hay aquí abajo.

Durante años tuve ideas que no podían salir. Sabía con precisión qué herramienta le faltaba
a mi gremio —doy clase de Filosofía en la pública, en Canarias— y no tenía ninguna forma de
fabricarla. El instrumento no existía para mí. Ahora existe.

No escribo el código: lo converso. Lo que pongo yo es lo otro. El problema visto desde dentro,
el criterio para saber cuándo algo está terminado, y la terquedad de no soltarlo hasta que
alguien lo usa.

> **«La técnica no es un simple medio. La técnica es un modo del desocultar.»**
> — Heidegger, *La pregunta por la técnica*

Esto es lo que se desoculta cuando por fin aparece el instrumento.

<br>

---

<br>

## Vivo ahora mismo

| | | |
|---|---|---|
| **[educanarias.app](https://educanarias.app)** | Plataforma para docentes: corrige, califica y programa | *en producción, con suscripción* |
| **[no-can.vercel.app](https://no-can.vercel.app)** | 6.676 nombramientos de interinos, buscables | *curso 2025/26 completo* |
| **[adjudicaciones 2026/27](https://ray86-dev.github.io/adjudicaciones-secundaria-canarias-2026/)** | 31.828 destinos provisionales | *sin servidor, todo en tu navegador* |

<br>

## El archivo

<sub>Cuatro obsesiones. Ábrelas.</sub>

<details>
<summary><b>&nbsp;I&nbsp; · &nbsp;Contra la máquina administrativa</b></summary>

<br>

> La Consejería publica la vida laboral de miles de personas en PDF de cientos de páginas,
> sin buscador, sin histórico y sin piedad. Cada septiembre, miles de interinos refrescan
> una página esperando saber dónde van a vivir el año que viene.
>
> Estas herramientas no arreglan eso. Solo lo hacen mirable.

**[adjudicaciones-secundaria-canarias-2026](https://github.com/Ray86-dev/adjudicaciones-secundaria-canarias-2026)** · [web](https://ray86-dev.github.io/adjudicaciones-secundaria-canarias-2026/)
31.828 registros de destinos provisionales. 110 especialidades de Secundaria, EOI y enseñanzas
artísticas. Búsqueda sin tildes, filtros por isla, categoría y vacante. Funciona al 100 % en el
navegador: un único JSON y JavaScript plano, sin frameworks y sin servidor.

**[nombramientos-canarias](https://github.com/Ray86-dev/nombramientos-canarias)** · [web](https://no-can.vercel.app)
6.676 nombramientos entre septiembre de 2025 y junio de 2026. 134 especialidades, 365 centros,
las 7 islas. Un scraper en Python con `pdfplumber` mastica los PDF oficiales; Next.js y Recharts
hacen el resto. DNI enmascarados, como los publica la propia Consejería.

**[adjudicaciones-canarias](https://github.com/Ray86-dev/adjudicaciones-canarias)**
El predictor. Cruza tu número de lista con las vacantes realmente adjudicadas y te dice si estás
a salvo, en riesgo o fuera. Ajusta la probabilidad al vuelo cuando descartas las islas a las que
no puedes ir. Extractor en Python, dashboard en React + Vite + Supabase.

</details>

<details>
<summary><b>&nbsp;II&nbsp; · &nbsp;El aula</b></summary>

<br>

> Un docente de secundaria dedica más horas a documentar lo que enseña que a enseñarlo.
> La LOMLOE convirtió la programación didáctica en un laberinto de criterios, descriptores
> y situaciones de aprendizaje. Estas herramientas devuelven ese tiempo.

**[EduCanarias](https://educanarias.app)** — *código cerrado*
El proyecto grande: 805 commits. Corrección por lotes con IA, calificación criterial LOMLOE,
generador de actividades y situaciones de aprendizaje, extractor de documentos, biblioteca,
calendario, gestión de alumnado, informes de notas, exportación a DOCX y PDF. React + TypeScript,
Supabase, Stripe. Dominio propio y suscriptores de pago.

**[filosofia360](https://github.com/Ray86-dev/filosofia360)**
Preparador de clases de Filosofía para el curso 2026/27. Genera la programación, las situaciones
de aprendizaje y las **sesiones impartibles** — guion con el texto dentro, materiales y evaluación.
Sin login, sin nube, sin claves de API: todo vive en un SQLite en tu disco. Pulsas «Preparar el
día» y en veinte minutos tienes las clases de hoy.

**[espa-gen](https://github.com/Ray86-dev/espa-gen)** · [web](https://espa-gen.vercel.app)
Para la Educación Secundaria para Personas Adultas. Seleccionas criterios de evaluación de los
tres ámbitos y salen actividades. Una función serverless hace de proxy a Groq para que la clave
no toque nunca el navegador.

**[EDUSCAN](https://github.com/Ray86-dev/EDUSCAN)**
Next.js con Capacitor: corregir desde la cámara del móvil. iOS y Android.

</details>

<details>
<summary><b>&nbsp;III&nbsp; · &nbsp;La oposición</b></summary>

<br>

> Setenta y un temas. De los setenta y uno se sortean cinco. De los cinco eliges uno.
> Todo el sistema de acceso a la función docente descansa sobre esa aritmética.
> Merecía al menos una app que la mirase de frente.

**[zen-oposiciones](https://github.com/Ray86-dev/zen-oposiciones)**
Plan de estudio guiado para el cuerpo de Secundaria, especialidad Filosofía (590/201), en Canarias.
Horizonte agosto 2026 → junio 2027. Cuenta atrás, fase actual, sesiones del día, porcentaje de
temario consolidado y **la probabilidad real** de que salga alguno de los temas que llevas
preparados. Construido para un objetivo concreto, con la arquitectura lista para otras
especialidades.

**temarios-opos** — *privado*
Plataforma SaaS de temarios de oposiciones con IA. Next.js 14, Supabase, Stripe y Gemini.

**[proporcion-aurea-oposiciones](https://github.com/Ray86-dev/proporcion-aurea-oposiciones)**
Landing minimalista para temarios de oposiciones de Escuelas de Arte en Canarias.

</details>

<details>
<summary><b>&nbsp;IV&nbsp; · &nbsp;La palabra</b></summary>

<br>

> Todo lo anterior resuelve un problema de otro. Esto no.

**[BLOB](https://github.com/Ray86-dev/BLOB)**
Un procesador de textos minimalista para escritores y poetas. Sin barras de herramientas, sin
menús de formato, sin nada. Solo tú y una única tipografía caligráfica. Pensado para quien
escribe poemas y los publica en un cuadrado de Instagram. Aplicación de escritorio para Windows.

*For the love of writing.*

</details>

<br>

---

<br>

## Cómo trabajo

No pienso aparentar lo que no soy, así que lo pongo por delante.

**Lo que traigo**

- **El problema.** Conozco el dominio por dentro: la administración educativa canaria, sus
  resoluciones, sus PDF imposibles, sus plazos, y lo que de verdad le duele a alguien que da
  clase. Nadie me tiene que explicar para quién es esto.
- **El criterio.** Sé distinguir una herramienta que alguien va a abrir cada mañana de una demo
  que impresiona cinco minutos. Casi todo el trabajo está en esa distinción.
- **La ejecución.** De la idea al dominio propio con usuarios que pagan. `educanarias.app` existe,
  y no es una maqueta.
- **La constancia.** Ochocientos commits en un solo proyecto no los sostiene el entusiasmo.

**Lo que no traigo**

- No domino ningún lenguaje. No leo una traza de error sin ayuda. No he trabajado nunca dentro
  de un equipo de desarrollo. No sé decir «senior» sin que me dé la risa.

Si buscas a alguien que escriba el código, no soy yo.
Si buscas a alguien que sepa **qué** hay que construir, **para quién** y **por qué** —
y que además lo lleve hasta el final — hablemos.

<br>

## Cuentas

```
     9   meses desde el primer commit
    12   proyectos
 1.000+  commits
31.828   registros administrativos rescatados de un PDF
 6.676   nombramientos indexados
   134   especialidades docentes
    71   temas de un temario que se sortea de cinco en cinco
     7   islas
     0   asignaturas de programación cursadas en mi vida
```

<br>

## Coda

Séneca escribió que no es que tengamos poco tiempo, sino que perdemos mucho. Empecé tarde,
y lo sé.

Chestov sostuvo que la filosofía no nace del asombro sino de la desesperación, y que la razón,
cuando choca contra un muro, no siempre tiene la última palabra. Cioran habría dicho que nada
de esto sirve para nada, y probablemente tenga razón. El hombre del subsuelo de Dostoievski
respondería que da igual: que lo único que necesita de verdad una persona es una voluntad
que sea suya.

Lo construyo igual.

<br>

## Contacto

**rayco@outlook.com**

Sin foto, sin apellidos, sin redes. Lo que hay que saber de mí está arriba, en lo que he hecho.

<br>

<details>
<summary><sub>· · ·</sub></summary>

<br>

<sub>
Hay una app ahí arriba que no encaja con las demás.<br><br>
BLOB no resuelve ningún expediente, ni ahorra papeleo, ni tiene usuarios que paguen.
Es un folio en blanco con una sola letra bonita, para alguien que escribe versos y no
quiere que ningún botón se lo recuerde.<br><br>
Ninguna herramienta se hace sin una razón. Esa no tiene ninguna útil.
</sub>

</details>

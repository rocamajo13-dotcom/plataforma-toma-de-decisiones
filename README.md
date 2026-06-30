# IGNITE LABORATORIO

Plataforma web profesional para aprendizaje y evaluacion de toma de decisiones bajo incertidumbre mediante los criterios de Hurwicz y Savage, aplicada a Liderazgo.

## Contenido

- Landing page institucional.
- Modulo de aprendizaje: Hurwicz y Savage.
- Registro de participante.
- Evaluacion aleatoria de 10 preguntas.
- Temporizador oficial de 15 minutos.
- Correccion automatica.
- Resultados y retroalimentacion.
- Certificado PDF para notas iguales o superiores a 82/100.
- Reporte PDF individual.
- Panel administrativo privado.
- Exportaciones Excel, PDF y ZIP.

## Ejecutar localmente

Requisitos: Node.js instalado.

```bash
npm install
npm start
```

Luego abrir:

```text
http://127.0.0.1:4177
```

Este proyecto no usa dependencias externas, por lo que npm install no descarga paquetes; solo deja el flujo listo para entornos Node.

## Credenciales del panel administrativo

Usuario: `admin`

Contrasena: `Ignite2026!`

## Despliegue

La aplicacion es estatica y puede desplegarse en cualquier hosting que sirva HTML, CSS, JS y PNG. Para despliegues Node, usar `npm start`.

## Estructura

```text
ignite-laboratorio/
  index.html
  package.json
  server.js
  src/
    app.js
    styles.css
  public/
    assets/
      ignite.png
      certificate-template.png
  docs/
    DESCRIPCION.md
```

# AMAC – Plataforma de empleo (Entrega 2: HTML y CSS)

Proyecto OT2026-WEB · Universidad de Monterrey

## Integrantes
- Diego Núñez Guzmán (637048) – _completar qué hizo_
- Ricardo Villarreal Villatoro (628352) – _completar qué hizo_
- Emiliano Martinez Ramirez (683446) – _completar qué hizo_

## Páginas
`index.html` · `vacante.html` · `login.html` · `registro-candidato.html` · `mis-solicitudes.html` · `empresa-vacantes.html`

Flujo de demo: index → vacante → Postularme (ventana de confirmación) → mis-solicitudes.

## Variables CSS (css/variables.css)
| Token | Valor | Uso |
|---|---|---|
| --color-marino | #202945 | Header, botones secundarios, texto |
| --color-coral | #ff7c5f | Botón principal (texto marino, contraste 5.67:1) |
| --color-coral-texto | #b3361b | Enlaces/acentos en texto (contraste 6.07:1) |
| --color-celeste | #d5e9f2 | Logos de empresa, carrusel |
| --color-banner | #6953f3 | Anillo de foco |
Tipografía: Atkinson Hyperlegible (Google Fonts), base 1.125rem (18 px).

## Componentes reutilizables (para React en la Entrega 3)
`Encabezado`, `NavPrincipal`, `Pie`, `Boton` (primario/secundario/contorno), `BotonIcono`, `TarjetaVacante`, `TarjetaSolicitud`, `LogoEmpresa`, `Etiqueta` (nueva/pendiente/aceptada/rechazada/activa/pausada/cerrada), `Panel` (details/acordeón), `CampoFormulario`, `GrupoOpciones`, `Carrusel`, `Prospecto`, `ModalConfirmacion`, `BarraAccion`.

## Cambios justificados respecto a Figma
- Botón principal coral con texto marino (blanco sobre coral da 2.5:1 y no cumple 4.5:1).
- Nav inferior: Empleos, Solicitudes, Mi empresa, Ingresar (Guardados y Mi perfil aún no tienen página).
- Login con correo/teléfono (RF-008) y sin la foto de Unsplash+ (licencia); agregar `img/` propia si se desea.
- Teléfono de ayuda AMAC (RF-052) es un placeholder: 81 0000 0000. Enlace de donativos también.

## Pendiente antes de entregar
Validar en validator.w3.org, correr Lighthouse (≥ 90), tomar capturas de index.html (celular y escritorio) y desplegar en Vercel (Framework: Other).

# Propuesta Z·IA — NNI × Z e-Scooters MX

Propuesta ejecutiva en formato **video-HTML**: once escenas con animación 3D, reproducción automática
(~2 min), contadores en vivo y maquetas animadas (asistente de WhatsApp con IA, FacturAI, tablero).
Un solo archivo autocontenido: `public/index.html` (logotipo NNI embebido; tipografías desde Google Fonts).

## Controles
| Acción | Tecla |
|---|---|
| Reproducir / pausar | Espacio |
| Escena anterior / siguiente | ← → |
| Pantalla completa | F |
| Ir al inicio / al final | Inicio / Fin |

La barra inferior permite saltar a cualquier escena.

## Contenido
01 Portada · 02 Resumen ejecutivo · 03 Diagnóstico · 04 Activos construidos · 05 Sistema Z·IA ·
06 Módulos · 07 Plan por fases · 08 Inversión · 09 Precio comparado · 10 Comparativo e inventario ·
11 Gobierno de la IA y siguientes pasos.

## Despliegue (PowerShell, desde la PC de Felipe)

Alta del sitio de Hosting (una sola vez):

```powershell
firebase login            # fdealbam@nni.ai
firebase hosting:sites:create propuesta-zia
```

Publicación:

```powershell
cd "<carpeta local>\propuesta-zia"
git checkout main
git pull
firebase deploy --only hosting
```

Dirección resultante: `https://propuesta-zia.web.app`

No requiere build: el sitio es estático.

## Fuentes de los datos
TikTok Studio de @zescootersmexico (27 oct – 2 nov 2026); inventario México de Z (3 nov 2026);
regulación de VEMEPE en CDMX según Xataka México, Publimetro y Posta (2026);
propuesta de agencia de referencia del 31 de octubre de 2026.

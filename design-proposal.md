# Propuesta de Diseño: Nidia Ugarte Quispe

## Identidad
Nidia es una psicóloga que descubrió que el arte sana lo que las palabras no alcanzan. No es "psicóloga que hace talleres" — es una arteterapeuta que fusiona psicología clínica, Gestalt, terapia narrativa y creación artística para transformar espacios institucionales en espacios de expresión y sanación. Su camino la llevó desde Arequipa hasta Chumbivilcas, desde México hasta Madrid, siempre buscando nuevas formas de conectar arte y bienestar emocional.

## Audiencia
- Instituciones de salud y educación buscando profesionales de arteterapia
- Organizaciones sociales/ONGs que necesitan consultores en salud mental comunitaria
- Colegas del campo psicología/arteterapia (networking académico)
- Potenciales pacientes/clientes para consulta privada o talleres

## Metáfora Visual
**"Un studio de arteterapia."** Cálido como arcilla fresca, texturas suaves como acuarela sobre papel. El espacio se siente seguro, creativo, humano — nunca clínico. Los colores tierra y terracota evocan materiales orgánicos; los acentos cálidos sugieren expresión artística contenida. Un recruiter ve este sitio y piensa: "esta persona trabaja con arte y personas."

## Paleta (6 colores) — "Terra & Bloom"

Esquema análogo cálido: terracota → sienna → cream.

- **primaryDark:** `#5C3A2E` — Chocolate oscuro tierra. Headings, footer bg, máxima autoridad. Evoca arcilla cocida.
- **primary:** `#A0674B` — Sienna/terracota medio. Borders, badges, timeline. El color de la cerámica artesanal.
- **primaryLight:** `#C8946F` — Sienna claro dorado. Shimmer highlights, detalles suaves.
- **accent:** `#D4764E` — Terracota cálido vibrante. CTAs, stats, dots. El POP orgánico — como pigmento fresco.
- **surface:** `#F5EDE6` — Crema cálida. Section backgrounds. Como papel de acuarela.
- **surfaceLight:** `#FBF7F3` — Off-white cálido. Hero bg, secciones claras. Luz natural de mañana.

**Justificación:** Paleta monocromática cálida (familia terracota/sienna). Evita azules/fríos que se sienten clínicos. Los tonos tierra reflejan el mundo de la arteterapia — materiales orgánicos, arcilla, pigmentos naturales, papel. Contraste WCAG: #5C3A2E sobre #FBF7F3 = ~9.5:1 (AAA).

## Tipografía
- **Headings:** `Cormorant Garamond` — Serif elegante y humanista. Tradición académica (Master UCM) + calidez artística. No corporate.
- **Body:** `Nunito Sans` — Humanist sans-serif redondeada. Cálida y accesible, perfecta para contenido terapéutico.
- **Accent/Quote:** `Caveat` — Handwritten font para frases destacadas. Evoca la creación artística manual.

## Efecto Visual Único
**"Watercolor wash"** — Secciones con bordes suaves degradados que simulan manchas de acuarela. Se logra con CSS gradients/blurs en los separadores de sección. Un efecto sutil que ningún otro portfolio tiene y que grita "arteterapia" sin necesidad de texto.

Segundo efecto: **Timeline como pinceladas** — La experiencia profesional se presenta como una línea continua con "nudos" artísticos (no dots genéricos), representando cada etapa como una pincelada en su recorrido.

## Secciones Propuestas (en orden)

### 1. Hero — "Nidia Ugarte Quispe"
2 columnas: foto izquierda (redondeada, borde terracota suave) + nombre en Cormorant Garamond grande + tagline:
"Psicóloga Clínica · Arteterapeuta · Psicoterapeuta Gestalt"
Debajo: stats row (3 métricas):
- `+7 años` experiencia clínica
- `440+` talleres realizados
- `3 países` de formación

CTA: "Conóceme" → scroll down

```
MOBILE (375px):
┌─────────────────────┐
│     [Foto circle]    │
│                      │
│   NIDIA UGARTE       │
│   QUISPE             │
│                      │
│  Psicóloga Clínica   │
│  Arteterapeuta       │
│  Psicoterapeuta      │
│                      │
│  +7    440+    3     │
│  años  talleres paises│
│                      │
│   [ Conóceme ↓ ]     │
└─────────────────────┘

DESKTOP:
┌──────────────────────────────────────────────┐
│  [Foto]     NIDIA UGARTE QUISPE              │
│  (circle)   Psicóloga Clínica ·              │
│             Arteterapeuta ·                   │
│             Psicoterapeuta Gestalt            │
│                                              │
│             +7 años | 440+ talleres | 3 países│
│             [ Conóceme ↓ ]                   │
└──────────────────────────────────────────────┘
```

### 2. Sobre Mí — "Donde el Arte Encuentra la Sanación"
Bio personal en tono cálido. Quote en Caveat (handwritten):
"Comprometida con el bienestar emocional y el desarrollo integral de las personas."
2 columnas: texto izquierda + lista de enfoques derecha (Gestalt, Narrativa, Arteterapia, Cuentoterapia).

```
MOBILE:
┌─────────────────────┐
│  DONDE EL ARTE      │
│  ENCUENTRA LA        │
│  SANACIÓN            │
│                      │
│  "Comprometida con   │
│  el bienestar..."    │ (Caveat italic)
│                      │
│  [Bio párrafo]       │
│                      │
│  ── Enfoques ──      │
│  ✦ Arteterapia       │
│  ✦ Gestalt           │
│  ✦ Terapia Narrativa │
│  ✦ Cuentoterapia     │
│  ✦ Escritura Terapéut│
└─────────────────────┘
```

### 3. Trayectoria — "Camino Profesional"
Timeline vertical con pinceladas como conectores (no líneas rectas genéricas). Cada nodo = una etapa con ícono, nombre de institución, rol, periodo, y 2-3 bullets key.

Agrupado por tipo (no cronológico puro):
- **Clínica:** Hospital Santo Tomás (2017-presente), APAINE, Clínica San Juan de Dios
- **Educativa:** Colegio Rosa de América, UGEL Chumbivilcas, Municipalidad Chumbivilcas
- **Internacional:** Hospital Gregorio Marañón (Madrid), Asoc. Psiquiatría y Vida (Madrid), Fundación Menudos Corazones (Madrid)
- **Consultoría:** FORDES (Dossiers publicados)

```
MOBILE:
┌─────────────────────┐
│  CAMINO              │
│  PROFESIONAL         │
│                      │
│  ◉──── Clínica ────  │
│  │                   │
│  ├─ Hospital Santo   │
│  │  Tomás            │
│  │  2017-Actual      │
│  │  • Psicoterapia   │
│  │  • Arteterapia    │
│  │                   │
│  ├─ APAINE           │
│  │  2018-2019        │
│  │                   │
│  ◉── Educativa ──    │
│  │                   │
│  ├─ Rosa de América  │
│  │  2018-2021        │
│  ...                 │
└─────────────────────┘
```

### 4. Formación — "Raíces Académicas"
Grid de cards con ícono de institución, título, universidad, periodo.
Destacar el Master UCM/UAM (Madrid) como card prominente con badge "Internacional".
Incluir certificaciones como chips/badges debajo del grid principal.

```
MOBILE:
┌─────────────────────┐
│  RAÍCES              │
│  ACADÉMICAS          │
│                      │
│  ┌─────────────────┐ │
│  │ 🎓 MASTER       │ │
│  │ Arteterapia y   │ │
│  │ Ed. Artística   │ │
│  │ UCM / UAM Madrid│ │
│  │ 2023-2025       │ │
│  │ [Internacional] │ │
│  └─────────────────┘ │
│                      │
│  ┌─────────────────┐ │
│  │ 🎓 LICENCIADA   │ │
│  │ Psicología      │ │
│  │ UCSM Arequipa   │ │
│  └─────────────────┘ │
│  ...más cards...     │
│                      │
│  ── Certificaciones ─│
│  [Cuentoterapia]     │
│  [Escritura Terap.]  │
│  [Dinámicas Grupales]│
└─────────────────────┘
```

### 5. Publicación — "Investigación"
Card destacada para su tesis de Master. Título, resumen, link a UCM.
Incluir también los Dossiers de FORDES como publicaciones menores.

```
MOBILE:
┌─────────────────────┐
│  INVESTIGACIÓN       │
│                      │
│  ┌─────────────────┐ │
│  │ Tesis de Master │ │
│  │                 │ │
│  │ "Arteterapia    │ │
│  │ grupal y exp.   │ │
│  │ culturales..."  │ │
│  │                 │ │
│  │ UCM, 2025       │ │
│  │ [Ver en UCM →]  │ │
│  └─────────────────┘ │
│                      │
│  ── Publicaciones ── │
│  • Dossier Embarazo  │
│    Precoz ASA        │
│    (BNP N°2018-14954)│
│  • Dossier Embarazo  │
│    No Deseado Arequip│
└─────────────────────┘
```

### 6. Contacto — "Conectemos"
Simple, cálido. Email + WhatsApp (ella quiere compartir el link por WPP).
Frase en Caveat: "Cada historia merece ser escuchada."

```
MOBILE:
┌─────────────────────┐
│  CONECTEMOS          │
│                      │
│  "Cada historia      │
│  merece ser          │
│  escuchada."         │
│                      │
│  ✉ nidiauq@gmail.com │
│  📱 +51 987100776    │
│                      │
│  [ Escríbeme por    │
│    WhatsApp → ]      │
│                      │
│  ── cofoundy.dev ──  │
└─────────────────────┘
```

## Secciones que NO incluir
- **Skills pills genéricos** — No aportan nada. Sus skills se entienden por su trayectoria.
- **Projects grid técnico** — No es dev. Sus "proyectos" son talleres y consultoría, se integran en Trayectoria.
- **CTA shimmer genérico** — El contacto es suficiente. No es coaching/venta agresiva.
- **Blog** — No tiene contenido para blog. Su publicación va en la sección Research.
- **Languages dot-bar** — Solo tiene Español (nativo) + Inglés (intermedio). No amerita sección.

## Resumen Técnico

- **Template base:** premium-starter (borrar componentes, escribir custom)
- **Fonts:** Cormorant Garamond + Nunito Sans + Caveat
- **Componentes custom:** Hero, About, Timeline (agrupado por tipo), Formation grid, Publication card, Contact
- **Efecto único:** Watercolor wash separators + timeline con pinceladas
- **Mobile-first:** Todo diseñado para 375px primero

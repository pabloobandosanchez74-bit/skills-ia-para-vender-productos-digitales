# 30 skills de IA para vender tu producto digital

Una colección de **skills para agentes de IA** (Claude, Claude Code, Cursor, Codex y otros) para dueños de negocio que crean y venden un producto digital: un curso, un ebook, plantillas o una membresía.

Una *skill* es una carpeta con instrucciones expertas que la IA lee cuando las necesita. Con estas skills instaladas, le dices a tu IA "ármame la oferta de mi curso" o "escribe la página de venta" y trabaja con el método de un especialista, en vez de darte una respuesta genérica.

Están organizadas en el orden en que las vas a necesitar: crear el producto → definir la oferta → la página de venta → atraer clientes → lanzar y crecer.

---

## Las 30 skills

### 1. Crear el producto

| # | Skill | Para qué te sirve |
|---|---|---|
| 1 | **pdf** ¹ | Ebooks, guías y workbooks en PDF |
| 2 | **docx** ¹ | Documentos en Word: manuales, contratos y plantillas |
| 3 | **pptx** ¹ | Presentaciones para tus cursos y webinars |
| 4 | **xlsx** ¹ | Plantillas de Excel para vender (presupuestos, inventarios, controles) |
| 5 | [doc-coauthoring](skills/doc-coauthoring) | Escribir el contenido de tu curso o libro junto con la IA |
| 6 | [canvas-design](skills/canvas-design) | Portadas, pósters y gráficos de tu producto |
| 7 | [theme-factory](skills/theme-factory) | Dar el mismo estilo visual a documentos, presentaciones y páginas |

### 2. Definir qué vender y a cuánto

| # | Skill | Para qué te sirve |
|---|---|---|
| 8 | [customer-research](skills/customer-research) | Descubrir qué dolor tiene de verdad tu cliente ideal |
| 9 | [product-marketing](skills/product-marketing) | Crear el documento base de tu negocio que usan todas las demás skills. **Empieza por esta.** |
| 10 | [offers](skills/offers) | Armar una oferta difícil de rechazar: bonos, garantía, valor percibido |
| 11 | [pricing](skills/pricing) | Definir precios, paquetes y planes |
| 12 | [marketing-psychology](skills/marketing-psychology) | Aplicar psicología de compra a lo que vendes |
| 13 | [marketing-plan](skills/marketing-plan) | Armar tu plan de marketing completo |

### 3. Página de venta

| # | Skill | Para qué te sirve |
|---|---|---|
| 14 | [copywriting](skills/copywriting) | Textos de la página de venta que convierten |
| 15 | [copy-editing](skills/copy-editing) | Mejorar textos que ya tienes |
| 16 | [frontend-design](skills/frontend-design) | Diseñar tu landing page |
| 17 | [cro](skills/cro) | Lograr que más visitantes compren |
| 18 | [popups](skills/popups) | Ventanas emergentes para captar correos |

### 4. Atraer clientes

| # | Skill | Para qué te sirve |
|---|---|---|
| 19 | [lead-magnets](skills/lead-magnets) | Crear el recurso gratis que atrae prospectos |
| 20 | [emails](skills/emails) | Secuencias de correo que venden en automático |
| 21 | [content-strategy](skills/content-strategy) | Decidir qué contenido publicar |
| 22 | [social](skills/social) | Posts, carruseles y guiones de Reels y TikTok |
| 23 | [video](skills/video) | Producir videos con herramientas de IA |
| 24 | [image](skills/image) | Imágenes para redes, anuncios y mockups del producto |
| 25 | [ads](skills/ads) | Campañas en Meta, Google y TikTok |
| 26 | [ad-creative](skills/ad-creative) | Textos y variaciones de anuncios |

### 5. Lanzar y crecer

| # | Skill | Para qué te sirve |
|---|---|---|
| 27 | [launch](skills/launch) | Planear tu lanzamiento paso a paso |
| 28 | [referrals](skills/referrals) | Programa de afiliados o referidos |
| 29 | [ai-seo](skills/ai-seo) | Que ChatGPT, Gemini y Perplexity recomienden tu producto |
| 30 | [churn-prevention](skills/churn-prevention) | Si vendes membresía, evitar que la gente cancele |

¹ **pdf, docx, pptx y xlsx** son de Anthropic y su licencia no permite redistribuirlas, así que no están copiadas en este repositorio. Si usas Claude en claude.ai, ya vienen incluidas y no tienes que instalar nada. Para otros agentes, instálalas desde el repositorio oficial: [anthropics/skills](https://github.com/anthropics/skills).

---

## Cómo instalarlas

### Opción A: en Claude (claude.ai o la app), sin código

1. Entra a la carpeta [`zips/`](zips) y descarga el `.zip` de la skill que quieras.
2. En Claude, abre la configuración, busca la sección de **Skills** y sube el `.zip`.
3. Listo. Claude la usa sola cuando tu pedido coincide con lo que hace la skill.

### Opción B: con la terminal (Claude Code, Cursor, Codex y otros agentes)

Instala todas de una vez:

```bash
npx skills add pabloobandosanchez74-bit/skills-ia-para-vender-productos-digitales
```

O solo una:

```bash
npx skills add pabloobandosanchez74-bit/skills-ia-para-vender-productos-digitales --skill offers
```

En Claude Code también puedes copiar a mano la carpeta de la skill dentro de `~/.claude/skills/`.

---

## Por dónde empezar

1. **product-marketing**: le cuentas tu negocio una vez y todas las demás skills lo usan como contexto.
2. **offers** y **pricing**: defines qué vendes y a cuánto.
3. **copywriting**: escribes la página de venta.
4. **lead-magnets** y **emails**: atraes prospectos y los conviertes en compradores.

Pídeselo a tu IA en tus palabras: *"Usa la skill de offers para armar la oferta de mi curso de [tema] para [cliente ideal]"*.

---

## Créditos y licencias

Este repositorio reúne skills de dos fuentes, sin modificar su contenido. Cada carpeta conserva su archivo de licencia original.

- **Skills de marketing (22):** [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills), de Corey Haines, con licencia MIT.
- **doc-coauthoring, canvas-design, theme-factory y frontend-design:** [anthropics/skills](https://github.com/anthropics/skills), de Anthropic, con licencia Apache 2.0.

Más detalle en [CREDITOS.md](CREDITOS.md). Para tener las versiones más recientes, revisa los repositorios originales.

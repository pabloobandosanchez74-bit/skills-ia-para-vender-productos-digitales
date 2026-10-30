# 20 skills de IA para mejorar tu producto digital

Una colección de **skills para agentes de IA** (Claude, Claude Code, Cursor, Codex y otros) para dueños de negocio que **ya venden** un producto digital, sea un curso, una membresía, una comunidad, un software o plantillas, y quieren que más clientes lo terminen, se queden y paguen más.

Una *skill* es una carpeta con instrucciones expertas que la IA lee cuando las necesita. Con estas skills instaladas, le dices a tu IA "¿por qué la gente cancela mi membresía?" o "rediseña el onboarding de mi curso" y trabaja con el método de un especialista, en vez de darte una respuesta genérica.

Están organizadas en el orden en que se mejora un producto: entender qué falla → mejorar la experiencia → ganar más por cliente → retener → crecer en automático.

---

## Las 20 skills

### 1. Entender qué está fallando

| # | Skill | Para qué te sirve |
|---|---|---|
| 1 | [customer-research](skills/customer-research) | Saber por qué compran, por qué abandonan y qué esperaban encontrar |
| 2 | [analytics](skills/analytics) | Medir en qué punto se cae la gente dentro de tu producto |
| 3 | [conversion-tracking](skills/conversion-tracking) | Revisar que cada venta y cada registro se esté contando bien |
| 4 | [attribution](skills/attribution) | Saber qué canal te trae los clientes que de verdad pagan |
| 5 | [competitor-profiling](skills/competitor-profiling) | Analizar qué hace mejor tu competencia y dónde puedes ganarle |

### 2. Mejorar la experiencia

| # | Skill | Para qué te sirve |
|---|---|---|
| 6 | [onboarding](skills/onboarding) | Que el cliente llegue rápido al primer resultado y no abandone |
| 7 | [signup](skills/signup) | Quitar fricción al registro y al acceso |
| 8 | [frontend-design](skills/frontend-design) | Rediseñar tu plataforma o tu área de miembros |
| 9 | [webapp-testing](skills/webapp-testing) | Probar automáticamente que todo funcione antes de que lo vea un cliente |

### 3. Ganar más por cada cliente

| # | Skill | Para qué te sirve |
|---|---|---|
| 10 | [pricing](skills/pricing) | Replantear precios, planes y paquetes |
| 11 | [offers](skills/offers) | Rediseñar la oferta: bonos, garantía, valor percibido |
| 12 | [paywalls](skills/paywalls) | Ofrecer mejoras de plan en el momento justo |
| 13 | [cro](skills/cro) | Subir la conversión de tus páginas actuales |
| 14 | [ab-testing](skills/ab-testing) | Probar cambios con datos en vez de adivinar |

### 4. Retener y fidelizar

| # | Skill | Para qué te sirve |
|---|---|---|
| 15 | [churn-prevention](skills/churn-prevention) | Bajar las cancelaciones y recuperar pagos fallidos |
| 16 | [emails](skills/emails) | Correos según lo que hace cada cliente, para que avance y vuelva a comprar |
| 17 | [sms](skills/sms) | Flujos por WhatsApp y SMS: bienvenida, recordatorios, recompra |
| 18 | [community-marketing](skills/community-marketing) | Una comunidad que hace que se queden |

### 5. Crecer en automático

| # | Skill | Para qué te sirve |
|---|---|---|
| 19 | [referrals](skills/referrals) | Que tus clientes te traigan clientes |
| 20 | [marketing-loops](skills/marketing-loops) | Rutinas que tu agente de IA corre cada semana sin que se lo pidas |

---

## Cómo instalarlas

### Opción A: en Claude (claude.ai o la app), sin código

1. Entra a la carpeta [`zips/`](zips) y descarga el `.zip` de la skill que quieras.
2. En Claude, abre la configuración, busca la sección de **Skills** y sube el `.zip`.
3. Listo. Claude la usa sola cuando tu pedido coincide con lo que hace la skill.

### Opción B: con la terminal (Claude Code, Cursor, Codex y otros agentes)

Instala todas de una vez:

```bash
npx skills add pabloobandosanchez74-bit/skills-ia-para-mejorar-tu-producto-digital
```

O solo una:

```bash
npx skills add pabloobandosanchez74-bit/skills-ia-para-mejorar-tu-producto-digital --skill churn-prevention
```

En Claude Code también puedes copiar a mano la carpeta de la skill dentro de `~/.claude/skills/`.

---

## Por dónde empezar

1. **customer-research**: antes de cambiar nada, entiende qué dicen tus clientes y por qué se van.
2. **onboarding**: la mayoría de los abandonos pasan en los primeros días.
3. **churn-prevention**: si cobras de forma recurrente, cada cancelación que evitas vale más que una venta nueva.
4. **pricing** y **paywalls**: cuando la gente ya se queda, aumenta lo que paga cada cliente.

Pídeselo a tu IA en tus palabras: *"Usa la skill de churn-prevention para analizar por qué cancelan mi membresía de [tema] y dame un plan"*.

---

## Créditos y licencias

Este repositorio reúne skills de dos fuentes, sin modificar su contenido. Cada carpeta conserva su archivo de licencia original.

- **Skills de marketing y crecimiento (18):** [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills), de Corey Haines, con licencia MIT.
- **frontend-design y webapp-testing:** [anthropics/skills](https://github.com/anthropics/skills), de Anthropic, con licencia Apache 2.0.

Más detalle en [CREDITOS.md](CREDITOS.md). Para tener las versiones más recientes, revisa los repositorios originales.

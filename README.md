# 🏴 Acracia — agente conversacional de efemérides anarquistas

**Acracia** es una agente de voz experta en **efemérides del anarquismo**:
canchera, formoseña y de biblioteca. Le preguntás por una fecha, un nombre o
un tema, y te cuenta qué pasó "un día como hoy" en la historia ácrata, con
rigor y sin solemnidad.

Hecha con [ElevenLabs](https://elevenlabs.io) (voz + agente conversacional).
Este repositorio es el **respaldo abierto** de sus materiales, en clave
_copyleft_.

---

## 🎙️ Hablar con Acracia

👉 **[Abrir Acracia](https://elevenlabs.io/app/talk-to?agent_id=agent_5301m1vrf8p3f9nbg4xtgcsnbpqc)**

Abrí el enlace en el navegador (del celu o la compu), dale permiso al
micrófono y ya podés hablarle por voz o escribirle por texto.

---

## 📂 Qué hay en este repo

| Archivo | Qué es |
|---|---|
| `anarcoefemerides.pdf` | La base de conocimiento: las efemérides que Acracia consulta para responder. |
| `prompt-personalidad-acracia.md` | El "mensaje del sistema": cómo piensa, habla y responde Acracia. |
| `saludos.md` | Las variantes de bienvenida que va alternando. |

---

## 🚀 Cómo dejarla funcionando en ElevenLabs (una sola vez)

1. Entrá a [ElevenLabs](https://elevenlabs.io) → **Conversational AI** → **Agents** → creá (o abrí) el agente **Acracia**.
2. En **System prompt / Mensaje del sistema**, pegá el contenido de `prompt-personalidad-acracia.md`.
3. En **First message / Primer mensaje**, pegá uno de los saludos de `saludos.md` (los demás van dentro del mismo system prompt para que los alterne).
4. Elegí la **voz** que más pegue con Acracia y ajustá idioma a español.
5. En **Knowledge base / Base de conocimientos**, subí `anarcoefemerides.pdf` → **Añadir documento** → **Publicar**.
6. Guardá y probá desde el enlace de "Hablar con Acracia".

---

## 🔄 Cómo se actualiza

**Importante:** este repositorio y la agente en ElevenLabs son
**independientes**. GitHub es solo un respaldo abierto; no está conectado a
la agente.

- Para que **Acracia** aprenda efemérides nuevas → subí el PDF actualizado
  (o uno nuevo) en **ElevenLabs** (Base de conocimientos → Añadir documento →
  *Publicar*). Eso funciona tenga o no tenga copia en GitHub. Podés tener
  **varios** documentos en la base a la vez: cada PDF que sumes amplía lo que
  Acracia sabe.
- Para mantener este respaldo al día → subí acá la última versión del PDF, a
  mano, cuando quieras.

No hace falta sincronizar los dos: cada uno se actualiza por su lado.

---

## 🅮 Copyleft

Material de la editorial copyleft. Se comparte para difundir, copiar,
reeditar y hacer circular. La historia del anarquismo es de todes.

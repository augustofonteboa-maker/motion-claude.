# Fonte Motion (motion-claude)

Galeria de motions feitos com o Claude por [@_augustofonte](https://www.instagram.com/_augustofonte/), com o prompt de cada vídeo para copiar.

A aba **Comunidade** lista motions de outros criadores, com crédito: o vídeo toca direto do post original do autor no X (embed oficial), e o prompt fica na entrada original no [Prompt Motion](https://www.prompt-motion.com/) (curadoria de [@p4nthera_](https://x.com/p4nthera_)). Os vídeos e prompts da comunidade pertencem aos seus autores.

## Como editar
- Seus motions: array `ENTRIES` no `index.html` (título, prompt, tags, data e, se quiser, `video` com o caminho do .mp4).
- Prompt de um criador da comunidade, com autorização: `COMM_PROMPTS['slug-da-entrada'] = { prompt: '...', video: 'videos/arquivo.mp4' }`.

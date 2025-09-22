# AI-Media-Generator-v1
Aplicação web em React para gerar imagens e vídeos por IA a partir de prompts de texto. Suporte estilos artísticos (8 opções), lotes de 1 a 4 itens e downloads simples. Usa modelos Flux 1.1 Pro (imagens) e Veo 3 (vídeos) via API externa. UI responsiva com carboidratos e erros tratados.

Recursos Principais
Modos: Imagens ou vídeos (abas).
Prompts + Estilos: Realista, Anime, Cyberpunk etc.
Lote: 1-4 itens; feedback em tempo real.
Download: Individual ou em massa (PNG/MP4).
Design: Tailwind + shadcn/ui, compatível com dispositivos móveis.
Pilha de tecnologia
React v18+ / TypeScript.
shadcn/ui, Lucide React, API de busca.
Estado: useState hooks.

# Instalação ⬤
git clone https://github.com/Lxcca248/AI-Media-Generator-v1 && cd ai-media-generator.

# npm install.

# .env: Adicione CustomerId, API Key (substitua espaços reservados).

# npm run dev(host local:5173).

 Uso

Escolha o modo, insira o prompt, selecione estilo/quantidade.
Clique em "Gerar" e baixe resultados.
Ex.: “Cidade futurista, estilo cyberpunk”.
API ⬤
Ponto final: POST /chat/completions(semelhante ao OpenAI).
Cabeçalhos: CustomerId, Token do portador.
Nota: Os vídeos demoram 2-5 min; use env vars para chaves.
#  Limitações ⬤
Dependente de API externa (custos/cota).
Sem armazenamento local.

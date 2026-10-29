# Missão Brasil — React 19

Jogo de Geografia para o 5º ano: miscigenação, formação do povo brasileiro e diversidade cultural.

## Tecnologias
React 19, TypeScript, Tailwind CSS v4, Vite, Three.js (via React Three Fiber), Lucide React, Web Audio API e Web Speech API.

## Executar
```bash
npm install
npm run dev
```
Abra o endereço exibido pelo Vite (normalmente http://localhost:5173).

## Compilar
```bash
npm run build
npm run preview
```

## Regras
- Banco com 50 perguntas conceitualmente distintas, preservadas da versão HTML; 25 perguntas sorteadas sem repetição dentro de cada missão.
- 60 minutos por missão, contados pelo relógio real, inclusive durante os avisos.
- Acerto: 1 estrela + 10 moedas e celebração animada.
- Erro: resposta correta + explicação, aviso bloqueado por 20 segundos.
- Botões para ativar/desativar efeitos sonoros e leitura de perguntas. Leitura de voz depende do navegador/vozes disponíveis.
- O progresso é mantido apenas durante a sessão atual.

## Observações
O app usa Three.js para a cena 3D de estrelas e globo. O som é gerado com Web Audio API (sem arquivos externos). A fala usa speechSynthesis (Web Speech API). Os navegadores podem exigir interação do usuário para liberar áudio.

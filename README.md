# Jarvis (site)

Versão do Jarvis que roda direto no navegador, sem Linux: núcleo animado,
voz (Chrome ou Edge), modo conversa, pendências, memória, calendário e
comandos rápidos. O cérebro é o [Ollama](https://ollama.com/download)
rodando no seu computador.

## Usar no Windows

1. Instale o Ollama: <https://ollama.com/download>.
2. No Prompt de Comando, baixe o modelo e libere o site:

   ```
   ollama pull qwen3.5:2b
   setx OLLAMA_ORIGINS *
   ```

3. Feche o Ollama (ícone perto do relógio → Quit) e abra de novo.
4. Abra o site no Chrome ou no Edge e permita o microfone.

Pendências, memória, hora e data funcionam mesmo sem o Ollama. Tudo fica
salvo só no seu navegador.

## O que ele faz

- Mãos livres: ouve até você fazer uma pausa; em espera (vermelho) depois de
  1 minuto ou quando você diz "desligar"; duas palmas ligam de novo.
- 64 hologramas 3D que aparecem sozinhos conforme o assunto (arraste para girar).
- Lembretes, alarmes e cronômetro; calculadora; previsão do tempo
  (Open-Meteo); cotação de moedas (Frankfurter); resumos da Wikipédia.
- Abre sites por voz (YouTube, TikTok, Instagram, WhatsApp…) e toca música no YouTube.
- Diga "o que você sabe fazer" para ver tudo.

# O que faço agora (o-que-faco-agora)

Uma skill para o Claude dizer o que você faz primeiro. Ele lê a sua lista de atividades, dá quatro
notas a cada uma (valor, urgência, risco e tamanho) e põe tudo em ordem pela régua WSJF:

```
WSJF = (valor + urgência + risco) ÷ tamanho
```

As notas só podem ser 1, 2, 3, 5, 8 ou 13, e cada uma vem com a frase que a sustenta. No fim, a fila
sai em ordem, de P0 (hoje) a P3 (só se sobrar tempo), com as cinco primeiras em destaque e o próximo
passo de cada uma.

Serve para qualquer lista: planilha, CSV, anotações soltas ou o que estiver pendente no e-mail e no
WhatsApp que o Claude consegue ler. Ele não manda mensagem nem apaga nada sem você pedir.

## Como instalar

Você precisa do Claude no computador (claude.ai/download), com o Claude Code.

Peça ao Claude:

```
Instale para mim a skill o-que-faco-agora com o comando
npx skills add guimreis/o-que-faco-agora -g -y
```

Se ele disser que falta o Node.js, deixe ele te guiar na instalação. Depois, abra uma conversa nova.

Sem instalar nada, também funciona: copie o texto de
[skills/o-que-faco-agora/SKILL.md](skills/o-que-faco-agora/SKILL.md) e peça ao Claude para criar o arquivo
`.claude/skills/o-que-faco-agora/SKILL.md` na sua pasta com esse texto.

## Como usar

Abra o Claude na pasta onde está a sua lista e diga: "o que eu faço primeiro?"

## Licença

MIT. Feita por Guilherme Reis.

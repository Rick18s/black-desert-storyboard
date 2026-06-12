# Handoff completo - Black Desert Resort LED Ribbon

## 1. Objetivo

Apresentacao web interativa para demonstrar ao cliente uma animacao de publicidade
para o Inner Bowl LED Ribbon Board do Allegiant Stadium.

O site simula:

- O painel LED extremamente horizontal dentro de um estadio.
- Uma bola de golfe Black Desert recebendo uma tacada.
- A bola atravessando a faixa e revelando a marca e os textos.
- A bola terminando em um buraco visto de cima.
- Transicao para a imagem aerea do resort com a marca em uma extremidade.
- Encerramento laranja com logo e `blackdesertresort.com`.

Duracao apresentada: 10 segundos.

## 2. Caminho principal do projeto

```text
/Users/pedroeditor/Documents/Codex/2026-06-10/preciso-fazer-um-mocap-aqui-o/client-delivery
```

Arquivo principal:

```text
/Users/pedroeditor/Documents/Codex/2026-06-10/preciso-fazer-um-mocap-aqui-o/client-delivery/index.html
```

O projeto e um site estatico. Todo HTML, CSS e JavaScript da apresentacao esta
concentrado em `index.html`.

## 3. Site, repositorio e deploy

Site publico:

```text
https://black-desert-storyboard.onrender.com/
```

Repositorio:

```text
https://github.com/Rick18s/black-desert-storyboard.git
```

Branch:

```text
main
```

Commit online no momento deste handoff:

```text
1c3fda3 Stabilize ribbon typography across browsers
```

O Render acompanha o repositorio e publica automaticamente depois de um push
para `main`.

Comandos:

```bash
cd "/Users/pedroeditor/Documents/Codex/2026-06-10/preciso-fazer-um-mocap-aqui-o/client-delivery"
git status
git add index.html assets/
git commit -m "Descricao da alteracao"
git push origin main
```

Nao colocar tokens, senhas ou credenciais no codigo. A autenticacao do GitHub
fica no Keychain/gh da maquina.

## 4. Rodar localmente

```bash
cd "/Users/pedroeditor/Documents/Codex/2026-06-10/preciso-fazer-um-mocap-aqui-o/client-delivery"
python3 -m http.server 4173
```

Abrir:

```text
http://localhost:4173/
```

Para evitar cache durante testes:

```text
http://localhost:4173/?v=nome-do-teste
```

## 5. Arquivos dentro do site

```text
assets/AvenirLTStd-Heavy.otf
assets/AvenirLTStd-Roman.otf
assets/aerial-resort-center.jpg
assets/bdr-horizontal-white-official.png
assets/bdr-official-symbol-white.png
assets/black-desert-logo-white.png
assets/exterior-mockup.jpg
assets/golf-panorama.jpg
assets/ownit.jpg
assets/playit2.jpg
assets/resort-panorama.jpg
assets/visit.jpg
Black-Desert-Storyboard.jpg
README.md
index.html
```

Ativos realmente usados na animacao atual:

```text
assets/AvenirLTStd-Heavy.otf
assets/AvenirLTStd-Roman.otf
assets/aerial-resort-center.jpg
assets/bdr-horizontal-white-official.png
```

Os demais sao referencias ou ativos de versoes anteriores.

## 6. Arquivos originais fora do repositorio

Logo EPS oficial entregue pelo cliente:

```text
/Users/pedroeditor/Downloads/BDR REEF - Registered Mark for BDR Assets - BDR - horizontal white.eps
```

Referencia em video da tacada:

```text
/Users/pedroeditor/Downloads/WhatsApp Video 2026-06-11 at 21.45.25.mp4
```

Imagem aerea TIFF original:

```text
/Users/pedroeditor/Downloads/BDR_01_Aerial_Resort Center.tif
```

Imagens de pecas anteriores:

```text
/Users/pedroeditor/Documents/20318REF_ BDR Exterior Media Mesh/Collected/20318REF_ BDR Exterior Media Mesh_20260605 Folder/Links/OwnIt.jpg
/Users/pedroeditor/Documents/20318REF_ BDR Exterior Media Mesh/Collected/20318REF_ BDR Exterior Media Mesh_20260605 Folder/Links/PlayIt.jpg
```

Logo recebida antes por imagem:

```text
/Users/pedroeditor/Downloads/Mockup de Design_20260610_121009_0000.png
```

Briefing recebido:

```text
/Users/pedroeditor/Downloads/WhatsApp Image 2026-06-03 at 01.07.09.jpeg
```

Pasta completa de referencia exterior:

```text
/Users/pedroeditor/Documents/20318REF_ BDR Exterior Media Mesh
```

Dropbox original:

```text
https://www.dropbox.com/scl/fo/9qsaevl6708cjb27bk4dp/ADnGGfwTQxlnS0qlKeU6yci?rlkey=ks4tocktrln3tmnxz575oerl3&st=shvifzg3&dl=0
```

## 7. Especificacoes do briefing

Entregas:

- Motion: MOV.
- Frame rate: 59.94 fps.
- Arquivo final: no maximo 500 MB por arquivo.

Resolucao exata:

- Upper Fascia Northeast/Northwest: `8500 x 112 px`.
- Upper Fascia South: `24496 x 112 px`.
- Lower Fascia East/West: `11648 x 112 px`.

Contexto:

- Campanha para a parceria Black Desert Resort + Las Vegas Raiders.
- Exibicao nos jogos em casa e em paineis ao redor do estadio.
- Objetivo de awareness geral do resort.
- Motion graphics preferido.

## 8. Feedback consolidado do cliente

- Usar a logo horizontal oficial entregue em EPS.
- A bola deve ser uma bola Black Desert realista.
- Mostrar um putter batendo na bola.
- A bola deve atravessar a faixa rapidamente.
- O taco nao deve acompanhar a bola pela tela.
- O taco faz backswing curto, impacto, pequeno follow-through e volta pela esquerda.
- A bola revela a marca e os textos conforme passa.
- Cada texto permanece visivel depois de aparecer.
- Ordem atual da leitura:
  - Logo Black Desert Resort.
  - `Visit.`
  - `Own It.`
  - `Play It.`
- Ao final, a bola cai em um buraco.
- O fechamento do buraco deve ser visto de cima.
- Usar apenas uma foto aerea da propriedade.
- Na foto, manter o logo em uma extremidade.
- Depois, retornar ao fundo laranja com logo e URL.
- Duracao autorizada: 10 segundos.
- Evitar texto sobre a fotografia.
- O motion deve ser clean, elegante e legivel.

## 9. Sequencia atual de 10 segundos

Tempos sao percentuais de uma animacao CSS de 10 segundos:

1. `0.0-0.7s`
   Putter e bola na esquerda.

2. `0.7-4.5s`
   Bola atravessa o painel e revela:
   logo, `Visit.`, `Own It.`, `Play It.`

3. Aproximadamente `4.0-4.5s`
   Bola muda para leitura aerea e cai no buraco circular.

4. Aproximadamente `5.8-8.7s`
   Wipe para a imagem aerea do resort. Logo permanece na extremidade direita.

5. Aproximadamente `8.7-10s`
   Fundo laranja, logo e `blackdesertresort.com`.

## 10. Mapa do codigo

Tudo esta em:

```text
index.html
```

Principais blocos CSS:

```text
.motion                 container da animacao
.copy-reveal            grid com logo e os tres textos
.official-logo          imagem oficial horizontal
.aerial-scene           fotografia aerea
.photo-logo             logo na extremidade da fotografia
.end-card               cartela final
.putter                  taco SVG
.golf-ball               bola criada em CSS
.ball-shadow             sombra direcional
.cup                     abertura do buraco
.cup-wall                profundidade interna
.cup-rim                 aro superior
```

Principais keyframes:

```text
revealLogo
revealVisit
revealOwn
revealPlay
putterStrike
impactFlash
ballTravel
shadowTravel
cupReveal
aerialReveal
aerialPan
endCard
```

Template que e clonado para todas as visualizacoes:

```html
<template id="motionTemplate">
```

JavaScript ao final:

- Clona o template para cada elemento `[data-motion]`.
- Controla Pause/Play.
- Reinicia todas as animacoes no botao Replay.

## 11. Ajustar timing

Duracao global:

```css
:root {
  --duration: 10s;
}
```

Todos os keyframes usam percentuais dessa duracao.

Exemplo:

```css
@keyframes revealVisit {
  0%, 17% { ... }
  20%, 59% { ... }
  64%, 100% { ... }
}
```

Em 10 segundos:

- 10% = 1 segundo.
- 20% = 2 segundos.
- 45% = 4,5 segundos.

## 12. Ponto sensivel: Chrome x Safari

Houve diferencas de renderizacao vertical entre Chrome, Safari e celular.

Decisao atual:

- Os textos da faixa usam a fonte local `Avenir BDR`.
- Nao usar Georgia nos textos animados da faixa.
- Nao usar offsets verticais fixos em pixels por elemento.
- Logo e textos devem compartilhar o mesmo grid e eixo.
- A revelacao e horizontal por `clip-path`, sem animar `translateY`.
- A logo oficial nao deve ser girada, deformada ou redesenhada.

CSS relevante:

```css
.copy-reveal
.copy-reveal > *
.copy-reveal .official-logo
.copy-reveal .word
```

Ao modificar, testar pelo menos:

- Chrome desktop, 1280 x 720 ou maior.
- Safari desktop.
- Mobile, aproximadamente 390 x 844.

## 13. Testar visualmente

Momentos importantes:

- `0.4-0.8s`: contato do taco.
- `1.5-4.0s`: textos sendo revelados.
- `4.0-4.5s`: bola caindo no buraco.
- `6.5-8.0s`: imagem aerea com logo.
- `9.0-9.8s`: cartela final.

Usar o botao `Replay 10 sec`.

Adicionar query para quebrar cache:

```text
https://black-desert-storyboard.onrender.com/?v=novo-commit
```

## 14. Logo oficial

Arquivo usado pelo site:

```text
assets/bdr-horizontal-white-official.png
```

Fonte oficial:

```text
/Users/pedroeditor/Downloads/BDR REEF - Registered Mark for BDR Assets - BDR - horizontal white.eps
```

Importante:

- Nao reconstruir a logo com texto HTML.
- Nao inclinar.
- Nao deformar.
- Nao cortar `RESORT`.
- Preservar a proporcao.
- Se houver acesso a Illustrator, Affinity Designer ou conversor vetorial confiavel,
  exportar novamente o EPS para PNG transparente em resolucao maior ou SVG.
- O PNG atual tem `432 x 121 px` e veio do preview embutido no EPS. Serve para o
  mockup, mas o render final deve usar o vetor original.

## 15. Foto aerea

No site:

```text
assets/aerial-resort-center.jpg
```

Original:

```text
/Users/pedroeditor/Downloads/BDR_01_Aerial_Resort Center.tif
```

CSS:

```css
.aerial-scene::before
```

O enquadramento atual usa `background-position` e `background-size: cover`.
Priorizar resort e campo de golfe. Nao esticar a imagem.

## 16. Publicacao

Depois de modificar:

```bash
git status
git diff --check
git add index.html assets/
git commit -m "Descricao objetiva"
git push origin main
```

Esperar o deploy do Render e abrir:

```text
https://black-desert-storyboard.onrender.com/?v=HASH_DO_COMMIT
```

Obter hash:

```bash
git rev-parse --short HEAD
```

## 17. Regras para a proxima IA

1. Ler este arquivo e `index.html` antes de editar.
2. Manter somente a versao final visivel ao cliente.
3. Nao restaurar as antigas abas de conceitos.
4. Nao trocar a ordem da copy sem novo feedback.
5. Nao modificar graficamente a logo oficial.
6. Nao usar imagens de screenshot no lugar dos arquivos originais.
7. Testar Chrome e mobile antes do push.
8. Nao publicar credenciais.
9. Manter a apresentacao em ingles para o cliente final.
10. Preservar o deploy no mesmo repositorio e endereco Render.

## 18. Prompt pronto para outra IA

```text
Trabalhe no projeto:
/Users/pedroeditor/Documents/Codex/2026-06-10/preciso-fazer-um-mocap-aqui-o/client-delivery

Leia primeiro:
/Users/pedroeditor/Documents/Codex/2026-06-10/preciso-fazer-um-mocap-aqui-o/client-delivery/HANDOFF-OUTRA-IA.md

Depois leia integralmente:
/Users/pedroeditor/Documents/Codex/2026-06-10/preciso-fazer-um-mocap-aqui-o/client-delivery/index.html

O site publico e:
https://black-desert-storyboard.onrender.com/

Repositorio:
https://github.com/Rick18s/black-desert-storyboard.git

Use a logo oficial sem alterar:
/Users/pedroeditor/Downloads/BDR REEF - Registered Mark for BDR Assets - BDR - horizontal white.eps

Use a foto aerea original:
/Users/pedroeditor/Downloads/BDR_01_Aerial_Resort Center.tif

Use a referencia da tacada:
/Users/pedroeditor/Downloads/WhatsApp Video 2026-06-11 at 21.45.25.mp4

Antes de publicar, teste Chrome desktop e mobile. Preserve a logo, a sequencia
de 10 segundos, os formatos do estadio e a apresentacao em ingles.
```

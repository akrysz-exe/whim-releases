<div align="center">

<img src="docs/images/icon.png" width="112" alt="Whim">

# Whim

**O teu ambiente de trabalho ao ritmo da música.**
Capa, letra sincronizada e neon para o Spotify, no Windows.

[![Última versão](https://img.shields.io/github/v/release/andreiadecristo33-pixel/whim-releases?label=vers%C3%A3o&color=22c55e&style=flat-square)](https://github.com/andreiadecristo33-pixel/whim-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/andreiadecristo33-pixel/whim-releases/total?label=downloads&color=16161a&style=flat-square)](https://github.com/andreiadecristo33-pixel/whim-releases/releases)
![Windows 10/11](https://img.shields.io/badge/Windows-10%20%7C%2011-16161a?style=flat-square)

### [⬇ Descarregar o Whim](https://github.com/andreiadecristo33-pixel/whim-releases/releases/latest)

<img src="docs/images/hero.jpg" alt="Whim a tocar: capa do álbum, letra sincronizada e o disco no canto do ambiente de trabalho">

</div>

## O que é

O Whim transforma o ambiente de trabalho num ecrã de música. Enquanto o Spotify toca, a capa do álbum e a letra aparecem por cima do papel de parede, uma linha neon contorna o ecrã com as cores da música, e um disco no canto dá-te os controlos.

- 🎵 **Toca dentro da app.** Não precisas de ter o Spotify aberto.
- 🖼️ **Capa e letra sincronizadas**, palavra a palavra, por cima do papel de parede (funciona com o Wallpaper Engine). Depois de 5 minutos em pausa, o teu papel de parede volta.
- 🌈 **Neon na borda do ecrã**, com as cores da capa ou em arco-íris, e ondas que reagem ao som. A espessura e a altura das ondas são ajustáveis.
- 💿 **Disco no canto**, sempre à mão no ambiente de trabalho:
  - tocar e pausar, saltar, posição da música e volume;
  - guardar nas tuas músicas, modo aleatório, pesquisa;
  - as tuas playlists e a fila "A seguir", que podes reordenar arrastando.
- ⌨️ **Atalhos globais**, que funcionam em qualquer janela, até a jogar.
- 🖥️ **Vários monitores:** escolhes em qual o Whim aparece.
- 🪶 **Leve.** Quando um jogo ou uma janela tapa o ecrã, as animações param sozinhas.
- 🔄 **Atualiza-se sozinho:** as versões novas instalam-se quando fechas o Whim.

<div align="center">
<img src="docs/images/card.png" width="520" alt="O cartão de controlo que abre a partir do disco">
</div>

## Instalação

1. Descarrega o **`Whim-Setup-x.y.z.exe`** da [última versão](https://github.com/andreiadecristo33-pixel/whim-releases/releases/latest).
2. Abre-o. A instalação é automática, não pede permissões de administrador e cria um atalho **Whim** no ambiente de trabalho.
3. O Whim abre sozinho e mostra os passos para ligares a tua conta Spotify.

> [!NOTE]
> **"O Windows protegeu o computador"?** O Whim não está assinado com um certificado pago, por isso o Windows (SmartScreen) avisa na primeira vez. Carrega em **Mais informações → Executar assim mesmo**.
> Em alternativa, antes de abrir: botão direito no ficheiro → **Propriedades** → marca **Desbloquear** → OK.
> As atualizações automáticas não mostram este aviso.

## Ligar o Spotify

O Whim usa a API oficial do Spotify, e o Spotify exige que cada pessoa crie a sua própria "app de programador". É grátis e demora 2 minutos. O Whim mostra estes passos na primeira vez que abre:

<table>
<tr>
<td width="55%">

1. Abre o [Spotify Developer Dashboard](https://developer.spotify.com/dashboard) e carrega em **Create app**.
2. Dá-lhe um nome qualquer, por exemplo *Whim*.
3. Em **Redirect URI**, cola:
   ```
   http://127.0.0.1:43821/callback
   ```
4. Marca **Web API** e **Web Playback SDK**, aceita os termos e guarda.
5. Copia o **Client ID** da app e cola-o no Whim.
6. Carrega em **Entrar com Spotify** e faz login no browser. Podes usar "Continuar com Google".

</td>
<td>
<img src="docs/images/onboarding.png" alt="Primeira configuração do Whim">
</td>
</tr>
</table>

> [!IMPORTANT]
> Desde 2026, o Spotify só deixa criar apps de programador a contas **Premium**. Com Premium, a música toca dentro do Whim. Contas Free também funcionam, através do leitor web do Spotify e com anúncios, mas sem pesquisa, biblioteca e fila no disco.

## Atalhos

Funcionam em qualquer janela e podes mudá-los nas Definições.

| Ação | Atalho |
| --- | --- |
| Tocar / pausar | <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Espaço</kbd> |
| Música seguinte | <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>→</kbd> |
| Música anterior | <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>←</kbd> |
| Subir / baixar volume | <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>↑</kbd> / <kbd>↓</kbd> |
| Ligar / desligar o neon | <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>N</kbd> |

As teclas multimédia do teclado (⏯ ⏭ ⏮) também funcionam.

## Definições

As Definições abrem com um clique no ícone do Whim na bandeja, junto ao relógio. Lá ajustas:
- o neon: cores, ondas, espessura e altura das ondas;
- a sincronização da letra;
- o arranque com o Windows;
- os atalhos.

No menu da bandeja (botão direito no ícone) escolhes também o monitor, se tiveres mais de um.

<div align="center">
<img src="docs/images/settings.png" width="420" alt="Definições do Whim">
</div>

## Perguntas frequentes

<details>
<summary><b>É seguro?</b></summary>

- O login é feito no teu browser, na página oficial do Spotify. O Whim nunca vê a tua palavra-passe.
- A autorização fica guardada só no teu PC, cifrada pelo Windows.
- O Whim não recolhe nem envia dados para lado nenhum. Fala apenas com o Spotify, com o [LRCLIB](https://lrclib.net) (letras) e com este repositório (atualizações).
- Para desenhar as ondas, lê o espectro do som do sistema. Nada é gravado.
</details>

<details>
<summary><b>A letra está adiantada ou atrasada</b></summary>

Ajusta em **Definições → Letra → Sincronização da letra**. As letras vêm do LRCLIB, e algumas músicas não têm letra sincronizada.
</details>

<details>
<summary><b>Não vejo o disco nem o fundo</b></summary>

Estão no ambiente de trabalho, por baixo das janelas. Carrega em <kbd>Win</kbd> + <kbd>D</kbd> para os veres. O fundo só aparece enquanto há música a tocar.
</details>

<details>
<summary><b>Como desinstalo?</b></summary>

Definições do Windows → **Aplicações → Aplicações instaladas** → **Whim** → Desinstalar.
</details>

<details>
<summary><b>Encontrei um problema</b></summary>

Abre uma [issue](https://github.com/andreiadecristo33-pixel/whim-releases/issues) com o que aconteceu e junta o ficheiro de diagnóstico. Para o encontrar, cola `%APPDATA%\Whim\diagnostics.log` na barra de endereço do Explorador de Ficheiros.
</details>

## Requisitos

- Windows 10 ou 11 (64 bits)
- Conta Spotify (Premium recomendado: ver acima)
- Ligação à internet

---

<div align="center">
<sub>Feito por <b>akry_sz</b> · O Whim é um projeto pessoal e não é afiliado, patrocinado nem aprovado pelo Spotify. Spotify é uma marca registada da Spotify AB.</sub>
</div>

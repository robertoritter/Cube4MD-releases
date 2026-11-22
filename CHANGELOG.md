# Cube4MD version history

Only the latest version is available for download on the [Releases page](https://github.com/robertoritter/Cube4MD-releases/releases/latest): earlier previews had bugs that later ones fixed. This page keeps what each version changed.

[Português](#histórico-de-versões)

## 0.2.0 preview 6 (November 22, 2026)

- Zoom the text with Ctrl + mouse wheel (Cmd + wheel on a Mac) and with a touchpad or trackpad pinch, as well as from the View menu
- Zoom applies only to the document's text in Text and Visual modes; menus, side panel, Split and Read stay at their normal size
- The status bar shows the zoom level; click it to go back to 100%
- The portable Windows version now has the version in its file name

## 0.2.0 preview 5 (November 19, 2026)

- Pasting over selected text always replaces it, as in any editor. Pasting a web address over another one no longer creates a `[text](address)` link
- Pasting several lines into a file with Windows line endings (CRLF) keeps them as separate lines
- Visual mode saves exactly what it shows: no added backslashes (`https\://`, `\$`), and a web address you edit stays an address
- Links keep the form they were written in (`<https://…>`, `[text][ref]`, `[text](url "title")`) when you edit their paragraph in Visual mode
- Find and Replace without regular expressions keeps `\n` and `\t` as typed

## 0.2.0 preview 4 (November 19, 2026)

- Text pasted or typed in Visual mode is saved exactly as it came: a web address stays as written, with no `< >` added
- In Text mode, the selection is visible on the cursor's line too
- Dropping a video, image, archive or program on the window shows a message instead of trying to open it as text
- Text files up to 100 MB open; larger ones show a message

## 0.2.0 preview 3 (November 18, 2026)

- Fixed a freeze when selecting part of a link in Visual mode
- New diagrams are always inserted whole, after the current block
- A new alert (note, tip, warning…) comes with its sample text selected, so you can type right away
- The blinking cursor no longer redraws the window on every frame (less CPU and battery)

## 0.2.0 previews 1 and 2 (November 16 and 17, 2026)

The first public versions of the app:

- Tabs for any `.md` file from any folder, restored with unsaved and untitled ones when you reopen the app; right-click a tab to close tabs in groups, rename the file, show it in its folder or copy its path or name
- Text, Visual, Split and Read modes, with a side panel of headings
- Saves only what you changed: everything else in the file stays byte for byte as it was
- Opens YAML, JSON, Python, SQL, XML, HTML and more than 130 languages, with a language selector and syntax colors; Format tidies JSON (also Python dicts and JSON5), YAML, XML and SQL of any database
- HTML files open in Split and Read, drawn as a page next to the code (scripts never run, nothing loads from the internet)
- Mermaid diagrams, with visual editors for flowcharts, Gantt, pie and sequence diagrams
- Math with KaTeX, tables, task lists, GitHub alerts and front matter shown as a properties card
- Find and replace in a Notepad++-style window, across tabs or a whole folder; bookmarks, compare tabs, Notepad++ line operations and optional Vim keys
- Images pasted or dropped into a document are saved in an `assets` folder next to it
- Numbered headings, focus mode (F11) and presentation mode (F5)
- UTF-8, UTF-16 and Windows-1252
- Export to HTML, print or save as PDF with the same look as on screen; copy as HTML
- 56 themes
- Help > Third-Party Licenses
- Installers for Windows (setup and MSI in English or Portuguese, plus a portable version), macOS (one installer for Apple silicon and Intel) and Linux (.deb)
- No account, no cloud, no telemetry: the window refuses every internet connection

---

# Histórico de versões

Só a versão mais recente fica disponível para baixar na [página de Releases](https://github.com/robertoritter/Cube4MD-releases/releases/latest): as previews anteriores tinham erros que as seguintes corrigiram. Esta página guarda o que mudou em cada versão.

## 0.2.0 preview 6 (22 de novembro de 2026)

- Zoom do texto com Ctrl + roda do mouse (Cmd + roda no Mac) e com a pinça no touchpad ou trackpad, além do menu Exibir
- O zoom vale só para o texto do documento nos modos Texto e Visual; menus, painel lateral, Dividido e Leitura ficam no tamanho normal
- A barra de status mostra o nível do zoom; um clique nele volta para 100%
- A versão portátil do Windows agora tem a versão no nome do arquivo

## 0.2.0 preview 5 (19 de novembro de 2026)

- Colar por cima de um texto selecionado sempre o substitui, como em qualquer editor. Colar um endereço da web sobre outro não cria mais um link `[texto](endereço)`
- Colar várias linhas num arquivo com quebras de linha do Windows (CRLF) mantém as linhas separadas
- O modo Visual grava exatamente o que mostra: sem barras a mais (`https\://`, `\$`), e um endereço da web editado continua sendo endereço
- Os links mantêm a forma em que foram escritos (`<https://…>`, `[texto][ref]`, `[texto](url "título")`) quando você edita o parágrafo no modo Visual
- Localizar e Substituir sem expressão regular mantém `\n` e `\t` como digitados

## 0.2.0 preview 4 (19 de novembro de 2026)

- O texto colado ou digitado no modo Visual é gravado exatamente como veio: um endereço da web fica como foi escrito, sem `< >`
- No modo Texto, a seleção aparece também na linha do cursor
- Soltar um vídeo, imagem, arquivo compactado ou programa na janela mostra um aviso, em vez de tentar abrir como texto
- Arquivos de texto de até 100 MB abrem; maiores mostram um aviso

## 0.2.0 preview 3 (18 de novembro de 2026)

- Corrigido o travamento ao selecionar parte de um link no modo Visual
- Diagramas novos sempre entram inteiros, depois do bloco atual
- Um alerta novo (nota, dica, aviso…) já vem com o texto de exemplo selecionado, para digitar direto
- O cursor piscando não redesenha mais a janela a cada quadro (menos processador e bateria)

## 0.2.0 previews 1 e 2 (16 e 17 de novembro de 2026)

As primeiras versões públicas do app:

- Abas para qualquer arquivo `.md` de qualquer pasta, que voltam ao reabrir o app, inclusive as não salvas e as sem título; clique com o botão direito numa aba para fechar abas em grupo, renomear o arquivo, mostrá-lo na pasta ou copiar o caminho ou o nome
- Modos Texto, Visual, Dividido e Leitura, com painel lateral de títulos
- Salva só o que você mudou: o resto do arquivo fica idêntico, byte a byte
- Abre YAML, JSON, Python, SQL, XML, HTML e mais de 130 linguagens, com seletor de linguagem e cores; o Formatar organiza JSON (também dicionários do Python e JSON5), YAML, XML e SQL de qualquer banco
- Arquivos HTML abrem no Dividido e no Leitura, desenhados como página ao lado do código (scripts nunca rodam, nada é carregado da internet)
- Diagramas Mermaid, com editores visuais de fluxograma, Gantt, pizza e sequência
- Fórmulas com KaTeX, tabelas, listas de tarefas, alertas do GitHub e propriedades (front matter) em cartão
- Localizar e substituir numa janela no estilo do Notepad++, em todas as abas ou numa pasta inteira; marcadores, comparar abas, operações de linha do Notepad++ e teclas do Vim opcionais
- Imagens coladas ou arrastadas para um documento são salvas numa pasta `assets` ao lado dele
- Títulos numerados, modo foco (F11) e modo apresentação (F5)
- UTF-8, UTF-16 e Windows-1252
- Exportar para HTML, imprimir ou salvar como PDF com a mesma aparência da tela; copiar como HTML
- 56 temas
- Ajuda > Licenças de terceiros
- Instaladores para Windows (instalador e MSI em inglês ou português, além da versão portátil), macOS (um instalador para chip Apple e Intel) e Linux (.deb)
- Sem conta, sem nuvem, sem telemetria: a janela recusa qualquer conexão com a internet

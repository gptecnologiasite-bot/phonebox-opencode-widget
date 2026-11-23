# phonebox-opencode-widget

Widget personalizado para o **PhoneBox** mostrar consumo/sessões do **OpenCode** na página `AI quotas`.

## Arquivos

- `index.html` — demo estática com dados simulados (para visualizar no navegador/Vercel).
- `opencode-widget.html` — widget para colar no campo HTML do widget `Custom HTML` do PhoneBox.

## Como usar no PhoneBox

1. No PhoneBox, edite a página `AI quotas` (ou outra página).
2. Adicione um widget **Custom HTML**.
3. Copie o conteúdo de `opencode-widget.html` para a opção `HTML`.
4. Salve. O widget usa `window.phonebox.on('work', ...)`, que o PhoneBox fornece dentro do iframe.

## Demo

https://phonebox-opencode-widget.vercel.app

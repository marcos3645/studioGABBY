# Studio Gaby Barbosa

Site de uma página (HTML, CSS e JavaScript puros, sem build) com serviços e preços,
calendário para escolher dia e horário, localização e agendamento pelo WhatsApp.

## Como editar

Tudo está no arquivo `index.html`.

- **Número do WhatsApp e endereço:** no começo do `<script>` no fim do arquivo,
  nas variáveis `WHATSAPP` e `ADDRESS`. O número vai com DDI e DDD, só dígitos.
  Também há links do WhatsApp nos botões do topo; para trocar o número neles,
  procure por `wa.me/` e substitua.
- **Preços e serviços:** procure o nome do serviço na seção "Serviços e preços".
  Se criar um serviço novo, adicione o nome também na lista `SERVICES` do script.
- **Horários de atendimento:** no texto da seção "Onde fica" e nas regras do
  calendário (dias abertos e horários), dentro da função `render` do script.

## Publicar

O site é estático. Qualquer hospedagem de arquivos serve (Cloudflare Pages,
GitHub Pages, Netlify). Basta publicar a pasta com o `index.html` na raiz.

# Coating Inspector — PWA (base inicial)

## O que está incluído
- DFT Calculator responsivo para celular e computador.
- Quantidade de pontos: até 1 m² = 5; >1–3 = 10; >3–10 = 15; >10–30 = 20; >30–100 = 30; acima de 100 = 30 + 10 por bloco adicional de 100 m² (ex.: 250 m² = 50).
- Três leituras por ponto; média por ponto e média geral.
- FR automático: 25–59 µm = 10 µm; 60–99 µm = 25 µm; 100–149 µm = 40 µm. Fora dessas faixas, FR fica sem atribuição automática e o resultado final fica pendente.
- Histórico no armazenamento local do navegador e exportação CSV.

## Como publicar para instalar
O PWA precisa ser servido por HTTPS (ou localhost para teste). Não basta abrir o index.html diretamente pelo gerenciador de arquivos.

Opção simples: publicar esta pasta em um serviço de hospedagem estática HTTPS, como GitHub Pages, Cloudflare Pages ou Netlify. Depois, abrir o endereço HTTPS no Chrome/ navegador do Android e escolher “Instalar app” ou “Adicionar à tela inicial”.

## Importante
Esta entrega é uma base funcional reconstruída a partir dos critérios técnicos disponíveis nesta conversa. O arquivo HTML original da versão anterior não estava anexado nem foi localizado nos arquivos disponíveis; portanto, esta versão não garante preservar a aparência/código exatos da v0.1. Os registros ficam no dispositivo/navegador e não sincronizam automaticamente entre celular e computador. Faça backup/exportação CSV antes de limpar dados do navegador.

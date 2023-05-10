# Monitor Pet

Alimentador automático para pets, tendo um visualizador web das informações em tempo real sobre seu animal de estimação.

## Escopo
- Cada alimentador é para um animal
- Suporte para cães e gatos
- Aceita somente ração (não suporta líquidos)
- Dosador físico em phyton com ESP32
- Um dosador pode ser gerenciado por diversos usuários e um usuário pode ter um ou mais dosadores.
- Será implementado somente a parte do usuário final, não vai ter àrea administrativa.

## Plataformas
- Web (Blazor wasm)
- Mobile (Blazor pwa)
- ASP NET CORE Api (Rest)
- Banco de dados MySql e Azure Blob

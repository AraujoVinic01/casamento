# Histórico de versões — site Vinícius & Gabriela

## v0.3.7 — 01/11/2026
- Cotação do dia mais confiável: tenta 3 fontes gratuitas (Frankfurter novo, Frankfurter antigo e currency-api) antes de usar a cotação de referência. Afeta só o valor em reais dentro do Pix.

## v0.3.6 — 01/11/2026
- Site mostra só euro, inclusive na opção Real. O valor em reais existe apenas dentro do QR Code / Pix copia e cola: a pessoa só vê o R$ no app do banco.
- Pix: saíram a linha "Valor R$" e a cotação; o código copia e cola não aparece na tela (botão Copiar continua copiando o código completo).
- Valor livre é sempre digitado em euro e convertido no código Pix.

## v0.3.5 — 01/11/2026
- Euro em primeiro: no checkout, € Euro vem antes e já selecionado (pra todo mundo, em PT ou EN).
- Valores em real saíram da lista de presentes e do pagamento em euro. O R$ só aparece quando a pessoa escolhe Real (Pix), junto com a cotação do dia.
- "Valor livre" começa em € 50.

## v0.3.4 — 01/11/2026
- Ícone V & G na aba do navegador (círculo bordô, letras brancas, & dourado e anel dourado), também ao salvar o site na tela inicial do celular.
- Barra do navegador no celular em bordô (theme-color).

## v0.3.3 — 01/11/2026
- Botão "Confirmar presença" abre o formulário do Jotform (o mesmo do QR Code impresso).

## v0.3.2 — 01/11/2026
- Correção urgente: a v0.3.1 tinha uma vírgula faltando na lista de presentes, o que parou o código do site (sem fotos, presentes e galeria). Corrigido.
- build.sh agora checa o código antes de gerar a versão de hospedagem.

## v0.3.1 — 01/11/2026
- "Valor livre" / "Any amount" passa a ser o primeiro presente da lista.

## v0.3.0 — 01/11/2026 (dados reais de pagamento)
- Euro: conta conjunta Revolut (Gabriela Ciweck & Vinicius Araujo), IBAN IE32 REVO 9903 6017 2606 31, BIC REVOIE23.
- Real: chave Pix de e-mail vini01araujo@hotmail.com; QR Code e copia e cola gerados com ela.
- Avisos de "dados de exemplo" removidos. Linha "Banco" saiu do Pix (não é necessária).
- Site publicado no GitHub Pages: araujovinic01.github.io/casamento

## v0.2.11 — 01/11/2026
- Novo texto de apresentação do casal (Instagram, Galway, Lisboa, Paris), em PT e EN, no lugar do texto genérico do Casar.com.
- Traje: Esporte fino, com a nota "Tema outono, em tons mais escuros" (PT e EN).

## v0.2.10 — 28/10/2026
- Seção "O casal": uma foto dos dois juntos (beijo às margens do Sena, em Paris) no lugar das duas fotos individuais, com moldura dourada fina.

## v0.2.9 — 28/10/2026
- Galeria "Momentos" com as 6 fotos do casal (Paris, Lisboa, cachoeira, pôr do sol e mirante), recortadas em quadrado sem cortar rostos. Faixas pretas do print removidas.

## v0.2.8 — 28/10/2026
- Removida a animação da v0.2.7 (nomes indo pro topo). O topo volta a mostrar só V & G.
- Menu destaca a seção que está na tela: o item fica dourado, em negrito e com um sublinhado fino que abre do centro. Os outros itens continuam visíveis.

## v0.2.6 — 28/10/2026
- Correção: monograma V & G do brasão da capa numa linha só (antes as letras podiam empilhar).

## v0.2.5 — 28/10/2026
- Versão de hospedagem (build.sh): site fora do Google (noindex) e título/descrição para a prévia do link no WhatsApp.
- Foto na prévia do WhatsApp entra quando o site tiver o endereço final (SITE_URL) e uma foto images/capa-whatsapp.jpg.

## v0.2.4 — 28/10/2026
- Pagamento em real: QR Code Pix e código "Pix copia e cola" com o valor já preenchido e o nome do presente na mensagem (padrão BR Code do Banco Central).
- Novo campo `city` no CONFIG do Pix; aviso pra usar chave de e-mail ou aleatória.

## v0.2.3 — 28/10/2026
- Visual royal em todo o site: títulos das seções centralizados com o ornamento dourado da capa.
- Datas da linha do tempo, rótulos e botões em maiúsculas clássicas; preços e valores em serifa (sem fonte de máquina de escrever).
- Texto de boas-vindas centralizado em itálico; ornamento também no rodapé.

## v0.2.2 — 28/10/2026
- Menu também no celular (segunda linha do topo) e botão "Lista de presentes" na capa.
- Seções não ficam mais escondidas atrás do topo fixo ao navegar.
- Idioma automático pelo celular do convidado (a escolha manual PT | EN continua tendo prioridade).
- Capa: "Galway, Irlanda". Linha do tempo: celebração em 21.11.2026.
- Número da versão saiu do rodapé (fica só no código).
- Depois do dia 21 às 16:00, a contagem regressiva vira "Casados!" / "Just married!".

## v0.2.1 — 28/10/2026
- Escolha da moeda no checkout: símbolo (R$ / €) em destaque numa linha, nome da moeda em outra e forma de pagamento embaixo, tudo centralizado.

## v0.2.0 — 28/10/2026 (visual "Royal")
- Fontes novas: nomes em caligrafia (Pinyon Script), títulos em Cormorant Garamond, rótulos e datas em maiúsculas romanas (Cinzel).
- Capa centralizada: monograma V & G num brasão de dois anéis dourados, nomes em linhas separadas com "&" dourado, ornamento fino (linhas + losango) e data.
- Topo com o monograma V & G no centro; seletor PT | EN com detalhe dourado.
- Assinatura do rodapé em caligrafia bordô.

## v0.1.22 — 28/10/2026
- Nova foto do "Valor livre": recortada só no porquinho com as moedas, sem cortes no card.

## v0.1.21 — 28/10/2026
- Presentes aceitam ajuste de enquadramento da foto (campo `pos` no CONFIG).
- Foto do "Valor livre" reenquadrada para mostrar o porquinho inteiro.

## v0.1.20 — 28/10/2026
- Correção: primeiro encontro em 23.08.2025 (antes 23.08.2026).

## v0.1.19 — 28/10/2026
- Data de quando nos conhecemos: 23.07.2025. Linha do tempo completa.

## v0.1.18 — 28/10/2026
- Data do primeiro encontro: 23.08.2026.

## v0.1.17 — 28/10/2026
- Linha do tempo: "O pedido" — 11/09/2026 em Paris, na hora em que a Torre Eiffel começou a brilhar (PT e EN).

## v0.1.16 — 28/10/2026
- Linha do tempo: "O primeiro encontro" — 23 de agosto em Galway, aquário, parque de diversões e almoço (PT e EN).

## v0.1.15 — 28/10/2026
- "Como nos conhecemos": texto encurtado (sem "very modern" / "moderníssimo").

## v0.1.14 — 28/10/2026
- Linha do tempo: "Como nos conhecemos" — pelo Instagram (PT e EN).

## v0.1.13 — 28/10/2026
- Local: Cloonacauneen Castle, Tuam Road, Cloonacauneen, Co. Galway, H91 XY77.
- Botão "Ver no mapa" abre o castelo no Google Maps.

## v0.1.12 — 28/10/2026
- Horário da celebração: 16:00 (contagem regressiva ajustada para 16:00, horário da Irlanda).

## v0.1.11 — 28/10/2026
- Foto no presente "Valor livre" (images/livre.jpg). Todos os 8 presentes agora têm foto.

## v0.1.10 — 28/10/2026
- Foto no presente "Cafeteira" (images/cafe.jpg).

## v0.1.9 — 28/10/2026
- Foto no presente "Cota do sofá" (images/sofa.jpg).

## v0.1.8 — 28/10/2026
- Foto no presente "Fundo da primeira casa" (images/casa.jpg).

## v0.1.7 — 28/10/2026
- Foto no presente "Passagens da lua de mel" (images/viagem.jpg).

## v0.1.6 — 28/10/2026
- Foto no presente "Uma noite de hotel" (images/hotel.jpg).

## v0.1.5 — 28/10/2026
- Foto no presente "Passeio de barco" (images/barco.jpg).

## v0.1.4 — 28/10/2026
- Presentes aceitam foto (campo `photo` no CONFIG); sem foto, mostra o nome.
- Foto no presente "Jantar na lua de mel" (images/jantar.jpg).

## v0.1.3 — 28/10/2026
- Ordem dos nomes: Vinícius & Gabriela (capa, fotos, rodapé, título e iniciais V & G).

## v0.1.2 — 28/10/2026
- Nomes completos: Gabriela & Vinícius (capa, fotos, rodapé e título da aba).
- Nomes da capa quebram em linhas no celular para não cortar.

## v0.1.1 — 28/10/2026
- Novo tema: branco, bordô e dourado, sempre claro (mesmo com o celular no modo escuro).
- Detalhes em dourado na capa ("&", contagem regressiva e faixa inferior).

## v0.1 — 28/10/2026 (base)
- Página única: capa com nomes, data e contagem regressiva; boas-vindas; o casal + linha do tempo; celebração; galeria; lista de presentes; rodapé.
- Seletor PT | EN no topo (lembra a escolha do convidado).
- Lista de presentes com 8 presentes de exemplo, valores base em euro e valor em real arredondado.
- "Checkout" sem pagamento: convidado escolhe Real (Pix) ou Euro (IBAN), vê o valor e copia os dados com um toque.
- Cotação do dia via Banco Central Europeu (frankfurter.app), com cotação de referência se não carregar.
- Tudo configurável no bloco CONFIG do index.html.

### Pendente (dados reais)
- Fotos do casal e da galeria
- Textos da linha do tempo
- Horário, local e mapa
- Link do Jotform (o mesmo do QR impresso)
- IBAN, BIC e chave Pix reais (trocar `sample: true` por `false`)

## Ideias para próximas versões
- v0.2: fotos reais e textos finais
- v0.3: QR Code do Pix com o valor já preenchido
- v0.4: publicar no GitHub Pages (link público)
- Futuro: mural de recados, hospedagem/dicas para quem vem do Brasil, domínio próprio

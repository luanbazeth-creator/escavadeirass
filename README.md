# 3ª Geração Terraplenagem — projeto organizado

Aplicação web mobile-first para controlar clientes, serviços, máquinas, horas, manutenção e inventário de peças.

## Estrutura do projeto

- `index.html` — **HTML**: estrutura das telas, formulários, diálogos e navegação.
- `style.css` — **CSS**: identidade visual, componentes, responsividade e ajustes para celular.
- `app.js` — **JavaScript**: regras de negócio, cadastros, cálculos, armazenamento local e eventos da interface.
- `assets/terraplenagem-3a-geracao.jpeg` — imagem da identidade visual da empresa.

Os arquivos ficam separados por linguagem. O código JavaScript está dividido por seções com comentários para facilitar manutenção e futuras alterações.

## Inventário inicial — Hyundai

O inventário começa com estes sete tipos de filtro: filtro de motor, filtro de diesel, filtro da bomba de diesel, refil de filtro de diesel, filtro de suspiro, filtro de ar interno e filtro de ar externo. Cada item permite registrar entradas, saídas, quantidade disponível, limite de estoque baixo e observações.

## Como abrir no Visual Studio Code

1. Extraia o arquivo ZIP.
2. Abra a pasta `escava_pro` no Visual Studio Code.
3. Abra `index.html` usando a extensão **Live Server** ou um servidor web local.
4. Edite o HTML, CSS e JavaScript no arquivo correspondente.

## Como os dados são guardados

Esta versão utiliza `localStorage` do navegador. Os dados ficam no aparelho/navegador atual e não sincronizam automaticamente com outros celulares ou computadores. Para uso compartilhado, conecte Firebase Authentication e Cloud Firestore e configure regras de segurança.

## Observações de manutenção

- Faça uma cópia de segurança antes de alterações grandes.
- Teste cadastro, edição, entradas/saídas do inventário e formulários após publicar.
- Os intervalos de manutenção devem seguir a recomendação técnica do fabricante de cada máquina.

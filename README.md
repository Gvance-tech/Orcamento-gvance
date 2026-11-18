# Orçamento Gvance

Site responsivo para criar propostas comerciais e baixar orçamentos em PDF com a identidade visual Gvance.

## Como usar

Abra `index.html` em um navegador moderno. Não há instalação ou etapa de build.

1. Preencha os dados do cliente e a descrição do projeto.
2. Adicione os serviços e valores. O total é calculado automaticamente.
3. Defina prazo, validade, entrada e observações.
4. Clique em **Baixar PDF**.

O rascunho fica no armazenamento local do navegador. Não há servidor, conta de usuário ou sincronização entre dispositivos. O botão **Novo** substitui o rascunho após confirmação.

## Arquivos

- `index.html`: estrutura do formulário e da prévia.
- `style.css`: estilos e adaptação para celular e computador.
- `app.js`: cálculo, rascunho, prévia e geração do PDF com paginação.
- `pdf-lib.min.js`: biblioteca pdf-lib, distribuída localmente para gerar PDFs sem depender de CDN.
- `LICENSE-pdf-lib.md`: licença da dependência pdf-lib.

Nenhum fluxo de publicação ou configuração de hospedagem está incluído.

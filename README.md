# 🧪 Vitrine Logística de Cargas Químicas

Protótipo de aplicação web desenvolvido em Python para organizar pedidos de transporte de produtos químicos e apoiar a gestão de coletas, entregas e cotações de frete.

O projeto aplica conceitos de programação e automação a um cenário real de logística, contemplando cargas fracionadas em IBC e operações a granel.

## 🚀 Funcionalidades implementadas

- **Listagem de cargas:** visualização dos pedidos cadastrados em uma tabela.
- **Cadastro de pedidos:** inclusão de locais de coleta e entrega, volume, tipo de embalagem, cubagem, transportadora sugerida e frete estimado.
- **Atualização da listagem:** atualização da tabela após o cadastro de novos pedidos ou por meio de um botão.
- **Consulta por identificador:** busca de um pedido pelo ID para iniciar uma simulação de solicitação de cotação.
- **Interface interativa:** organização das funcionalidades em abas para facilitar a utilização do protótipo.

## 🛠️ Tecnologias utilizadas

- **Python 3:** linguagem utilizada no desenvolvimento da aplicação.
- **Gradio:** criação da interface web interativa.
- **Pandas:** organização e exibição dos dados em tabelas.

## ▶️ Como executar

O projeto foi desenvolvido para execução em ambiente Python e pode ser testado no Google Colab.

1. Baixe ou abra o notebook do projeto no Google Colab.
2. Instale as dependências necessárias:

   ```python
   !pip install gradio pandas
   ```

3. Execute as células do notebook na ordem apresentada.
4. Ao executar a aplicação, o Gradio disponibilizará a interface para interação.

**Observação:** a disponibilidade de um endereço público de demonstração depende da sessão de execução do Gradio. O link temporário pode deixar de funcionar quando a sessão for encerrada.

## 🧩 Como os dados são armazenados

Nesta versão, os pedidos ficam armazenados em uma lista Python durante a execução da aplicação. Os dados não são persistidos em um banco de dados, portanto, podem ser perdidos quando a sessão é reiniciada.

## ⚠️ Limitações da versão atual

- A solicitação de cotação é simulada; o sistema não envia e-mails reais.
- A transportadora sugerida e o valor do frete são informados no cadastro. Ainda não existe seleção automática da melhor tarifa.
- O armazenamento é temporário e utiliza dados em memória.
- A aplicação é um protótipo em desenvolvimento, não um sistema de produção.

## 🔭 Melhorias futuras

- Implementar envio real de solicitações de cotação por e-mail.
- Criar regras para comparar tarifas e sugerir fretes conforme as rotas.
- Integrar um banco de dados para armazenamento persistente dos pedidos.
- Desenvolver critérios de seleção de transportadoras com base em região, preço e prazo de entrega.

## 🎯 Objetivo do projeto

Explorar como Python e ferramentas de desenvolvimento web podem apoiar a organização de operações logísticas, reduzir atividades manuais e criar oportunidades de automação na gestão de transportes.

## 📌 Status

**Protótipo funcional em desenvolvimento.**

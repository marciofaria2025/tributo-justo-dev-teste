# 🧪 Desafio Técnico – Desenvolvedor(a) Python ou .NET

Seja bem-vindo(a)! Este é o desafio técnico da Tributo Justo para a vaga de Desenvolvedor(a). Queremos avaliar seu raciocínio, organização de código e capacidade de resolver problemas de forma objetiva.

## 🚀 O Desafio

### 👨‍💻 Desenvolvedor Pleno

Você deverá construir uma API que:

1. Faça upload e leia um arquivo `.csv` com os seguintes campos:
   - `cnpj`, `numero_nota`, `valor_total`, `imposto_recolhido`, `data_emissao`

2. Armazene os dados em um banco de dados relacional (SQLite, PostgreSQL etc).

3. Calcule a diferença entre `valor_total` e `imposto_recolhido` e salve essa informação.

4. Exponha um endpoint `/relatorio` que:
   - Retorne o total de impostos por CNPJ
   - Calcule a média da diferença
   - Permita filtro por intervalo de datas (`data_emissao`)

### ⚙️ Requisitos Técnicos

- Linguagem: Python (Flask/FastAPI/Django) ou .NET (C# com ASP.NET Core)
- Banco de dados relacional
- Endpoints REST
- Organização de código (camadas, modularização)
- README com instruções de execução

## 📦 O que esperamos na entrega

- Código funcional e organizado
- README com instruções para rodar localmente
- Histórico de commits com mensagens claras
- Documentação básica da API (pode ser Swagger, Postman ou Markdown)

## ⏱️ Tempo estimado

Você pode realizar o teste no seu tempo, mas pedimos que seja entregue em até **3 dias úteis** após o envio.

## 📧 Entrega

1. Faça um **fork deste repositório** ou copie seu conteúdo para um novo repo público no seu GitHub.
2. Ao finalizar, envie o link do seu repositório para: **[marcio.faria@tributojusto.com.br]** com o assunto: `Entrega Desafio Técnico – [Seu Nome]`.

## 📎 Arquivo de exemplo

Veja o arquivo em `/dados/exemplo_dados.csv` para simulação.

---

Qualquer dúvida durante o teste, pode nos acionar. Boa sorte e esperamos que você se divirta resolvendo!
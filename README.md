# 🖱️ Automação de Cadastro de Produtos com Python
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/96976a7f-5173-411e-aab7-c371af71da76" />

Este projeto automatiza o processo de login em um sistema online e o cadastro de produtos a partir de uma base de dados em CSV.
Ele foi desenvolvido em **Python** utilizando a biblioteca **PyAutoGUI** para automação de interface e **Pandas** para leitura e manipulação de dados.

---

## 🚀 Funcionalidades

✅ Abre o navegador e acessa o sistema automaticamente
✅ Faz login com usuário e senha de forma automatizada
✅ Lê a base de produtos de um arquivo CSV
✅ Preenche o formulário de cadastro para cada produto
✅ Repete o processo para todos os produtos da base

---

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **PyAutoGUI** – Automação de teclado e mouse
* **Pandas** – Leitura e manipulação da base de dados
* **time** – Controle de espera entre ações

---

## 📂 Estrutura do Projeto

O projeto é bem simples e contém:

* Um arquivo principal que executa toda a automação
* Um arquivo CSV contendo a base de produtos
* Este README com toda a explicação

---

## 📜 Explicação do Funcionamento

1️⃣ **Abrindo o Sistema** – O script abre o navegador, acessa o site do sistema e aguarda alguns segundos para garantir o carregamento da página.

2️⃣ **Login Automático** – Preenche automaticamente o e-mail e a senha e realiza o login no sistema.

3️⃣ **Leitura da Base de Dados** – Lê o arquivo CSV com as informações de cada produto que será cadastrado.

4️⃣ **Cadastro de Produtos** – Percorre cada linha da tabela e preenche os campos do formulário no site, cadastrando produto por produto.

5️⃣ **Repetição para Todos os Produtos** – Repete o processo até que todos os produtos sejam cadastrados com sucesso.

---

## 📊 Estrutura da Base de Dados

A base de dados utilizada é um arquivo CSV com colunas como:

* **codigo** → Código do produto
* **marca** → Marca do produto
* **tipo** → Tipo ou modelo
* **categoria** → Categoria em que o produto se encaixa
* **preco\_unitario** → Preço de venda
* **custo** → Custo do produto
* **obs** → Observações adicionais (opcional)

> É importante que os nomes das colunas estejam exatamente como o projeto espera para evitar erros.

---

## ⚠️ Cuidados Importantes

* As coordenadas de clique do mouse podem variar de computador para computador, sendo necessário ajustá-las.
* Não mexa no mouse ou teclado durante a execução para evitar falhas na automação.
* O site precisa estar acessível no momento da execução.

---

## ▶️ Como Executar

1. Instale as bibliotecas necessárias (PyAutoGUI e Pandas).
2. Salve o arquivo `produtos.csv` na mesma pasta do script.
3. Execute o script.
4. Aguarde a automação preencher todos os cadastros sozinha.

---

## 🎯 Resultado Esperado

Ao final da execução, todos os produtos presentes no arquivo CSV terão sido cadastrados no sistema de forma rápida e sem digitação manual.

---

## 💡 Próximos Passos

* Adicionar tratamento de erros para produtos inválidos
* Criar logs para acompanhar o progresso do cadastro
* Criar uma interface gráfica para facilitar o uso

---

Quer que eu já deixe esse README com **emoji no título e seções bem destacadas** (como ✅🚀📂⚠️) para ele ficar ainda mais estiloso no GitHub?


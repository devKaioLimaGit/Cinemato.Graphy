# 📄 Bot Scraper de Filmes (IMDb)

Este projeto automatiza a coleta de dados de filmes diretamente do [IMDb](https://www.imdb.com/), permitindo extrair informações detalhadas a partir de uma lista de nomes de filmes em um arquivo `.txt`.

---

## 🔧 O que este software faz?

Ao fornecer um arquivo `.txt` contendo os nomes dos filmes, o bot executa as seguintes tarefas:

- 🔍 Busca automaticamente os filmes no IMDb  
- 🎬 Coleta informações como:
  - Título
  - Ano de lançamento
  - Nota
  - Duração
  - Diretor
  - Sinopse
  - Imagem do pôster
- 📦 Gera um arquivo `.json` com os dados extraídos
- 🌐 Envia os dados para uma API backend via `POST`

---

## 📁 Como usar?

1. Arraste e solte um arquivo `.txt` contendo os nomes dos filmes na interface.
2. O bot iniciará automaticamente o processo de coleta no IMDb.
3. Um log em tempo real será exibido na tela.
4. O arquivo `.json` com os dados será salvo no mesmo diretório do arquivo original.

---

## 📦 Tecnologias utilizadas

- **Selenium** – Automação do navegador  
- **Pandas** – Leitura e manipulação do arquivo `.txt`
- **Requests** – Comunicação HTTP com a API  
- **Tkinter** – Interface gráfica do usuário (GUI)

---

## 🌐 Consumir a API de Filmes

Se quiser integrar os dados de filmes em outro projeto, você pode consumir a API diretamente:

```bash
GET https://faculdade-cv39.onrender.com/movie

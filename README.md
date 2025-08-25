# DisplayFrontend

## 🚗🚲  - Carros e Bicicletas

Este é um projeto simples, feito com HTML e CSS, para praticar a criação de caixas e a estilização de elementos. Ele simula uma página de e-commerce que exibe informações sobre um carro e uma bicicleta, com links para compra.

### ✨ Funcionalidades

  - **Exibição de Produtos:** A página apresenta dois produtos principais: um carro e uma bicicleta.
  - **Detalhes:** Cada produto possui detalhes como preço, ano do modelo e quilometragem.
  - **Links de Compra:** Botões interativos que direcionam o usuário para sites externos, simulando a compra dos produtos.

### 📁 Estrutura do Projeto

O projeto é composto por apenas dois arquivos:

  - `index.html`: Contém toda a estrutura e o conteúdo da página, divididos em contêineres para cada veículo.
  - `style.css`: Responsável por toda a estilização, como cores, fontes, tamanhos e o layout das caixas.

### 🚀 Como Usar

Para visualizar o projeto, basta abrir o arquivo `index.html` em qualquer navegador web.

-----

### 👨‍💻 Tecnologias Utilizadas

  - **HTML5:** Para a estrutura e o conteúdo da página.
  - **CSS3:** Para a estilização e o design.

Sinta-se à vontade para clonar o projeto e fazer suas próprias modificações e melhorias\!

-----

### Código do Projeto

#### `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Carros e Bicicletas</title>
  <link rel="stylesheet" href="./style.css">
</head>
<body>
  <h1 id="Automoveis">Carros e Bicicletas</h1>
  <div class="conteinercarros">
    <h2>Carro: <span class="veiculo">R$ 500000</span></h2>
    <p>Carro modelo <span class="ano">2025</span>, com <span class="km">0km</span> rodados.</p>
    <a href="https://www.bmw.com.br/pt/topics/fascination-bmw/electromobility/veiculos-eletricos.html?tl=sea-goog-eang-pro-miy-.-text-.-.-.-eb3ae8f5ebaa&gad_source=1&gad_campaignid=21713855749&gbraid=0AAAAADr02X4JCfNyw4IM1ZWKdnams_2wO&gclid=Cj0KCQjw8KrFBhDUARIsAMvIApa_QN8laSlNrMruVQqsdxUhjC0WP4pzM9RF7zJsTVJ8r6fe_UNE5XwaAocCEALw_wcB">
    <button class="botão">Comprar Carro</button></a>
  </div>
  <div class="conteinercarros">
    <h2>Bicicleta: <span class="veiculo">R$ 1090</span></h2>
    <p>Bicicleta modelo <span class="ano">2025</span>, com <span class="km">0km</span> rodados.</p>
    <a href="https://www.lojagtsm1.com.br/">
      <button class="botão">Compra Bicicletas</button></a>
  </div>
</body>
</html>
```

#### `style.css`

```css
#Automoveis {
  text-align: center;
  margin-top: 50px;
}

.conteinercarros {
  border: 2px solid black;
  width: 500px;
  height: 200px;
  background-color: rgb(211, 211, 211);
  padding: 20px;
  margin: 30px auto;
  font-family: sans-serif;
}

.veiculo {
  color: blue;
}

.ano {
  color: rgb(12, 12, 12);
}

.km {
  color: rgb(82, 82, 82);
}

.botão {
  color: rgb(255, 255, 255);
  background-color: rgb(65, 65, 245);
  border: none;
  border-radius: 5px;
  padding: 10px;
  cursor: pointer;
  margin-top: 15px;
}
```

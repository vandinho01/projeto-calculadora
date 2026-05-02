# Calculadora JavaScript

[![Hcode Treinamentos](https://www.hcode.com.br/res/img/hcode-200x100.png)](https://www.hcode.com.br)

Calculadora desenvolvida como exemplo prático do Curso Completo de JavaScript na Udemy.com. O projeto simula uma calculadora física tanto no visual quanto no comportamento, utilizando tecnologias web modernas.

---

## 📌 Funcionalidades

* **Interface Realista e Vetorial:** O design da calculadora foi inteiramente construído utilizando SVG (Scalable Vector Graphics), garantindo que ela não perca qualidade em nenhuma resolução e possua efeitos de sombra (`drop-shadow`) para profundidade.
* [cite_start]**Display Autêntico:** Utiliza a fonte customizada `Digital-7` (criada por Sizenko Alexander [cite: 185, 187][cite_start]) para imitar fielmente os displays de cristal líquido (LCD)[cite: 183].
* **Histórico de Cálculos:** Uma seção dedicada e interativa que registra as expressões matemáticas e seus respectivos resultados. Permite visualizar operações passadas e possui a funcionalidade de "Limpar".
* **Feedback Sonoro:** Integração com arquivo de áudio (`click.mp3`) para reproduzir o som de clique das teclas, aprimorando a experiência do usuário.

---

## 🛠 Tecnologias Utilizadas

* **HTML5:** Estruturação da página e uso extensivo da tag `<svg>` para renderizar as partes e botões da calculadora.
* **CSS3:** Estilizações com `radial-gradient` para criar um fundo imersivo, transições e efeitos de hover na seção de histórico.
* **JavaScript:** Lógica de operações e controle de interface (arquitetura MVC, separando a lógica no `calcController.js` e a inicialização no `calculator.js`).

---

## 📁 Estrutura do Projeto

| Arquivo/Diretório | Descrição |
| :--- | :--- |
| `index.html` | Arquivo principal contendo a marcação HTML, estilos CSS embutidos e o desenho vetorial da calculadora. |
| `digital-7.ttf` | [cite_start]Arquivo de fonte da família Digital-7[cite: 192]. [cite_start]Usado para renderizar os números no visor[cite: 187]. |
| `click.mp3` | Arquivo de áudio acionado pelos eventos de clique na calculadora. |
| `scripts/` | Diretório que armazena os arquivos JavaScript que controlam as regras de negócio (`calcController.js`) e a inicialização (`calculator.js`). |

---

## 🚀 Como Executar

1. Faça o download ou clone este projeto para o seu computador.
2. Certifique-se de manter a mesma estrutura de pastas, garantindo que o `index.html` consiga encontrar os scripts e os assets (áudio e fonte).
3. Abra o arquivo `index.html` em qualquer navegador web moderno.
4. *Dica:* Para evitar eventuais bloqueios de segurança do navegador (CORS) ao carregar a fonte local ou o arquivo de áudio, recomenda-se abrir o projeto através de um servidor local (como a extensão *Live Server* do VSCode).

---

## 📸 Prévia do Projeto

![Calculadora](https://firebasestorage.googleapis.com/v0/b/hcode-com-br.appspot.com/o/calculadora-hcode.jpg?alt=media&token=5406aa3f-b965-401c-9b4e-654609c78b33)

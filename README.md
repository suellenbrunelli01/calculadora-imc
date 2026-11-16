# Calculadora de IMC

Uma aplicação web simples, leve e responsiva para calcular o Índice de Massa Corporal (IMC) diretamente no navegador, sem necessidade de instalação ou dependências externas.

🔗 **Acesse a aplicação online:** [Clique aqui para acessar no GitHub Pages](https://seu-usuario.github.io/seu-repositorio/) *(substitua pelo link do seu repositório)*

---

## 🎯 Objetivo

Fornecer uma ferramenta rápida e acessível para que qualquer pessoa possa calcular seu IMC e consultar sua classificação nutricional com base nos parâmetros estabelecidos pela Organização Mundial da Saúde (OMS).

---

## 🚀 Tecnologias Utilizadas

O projeto foi construído em um único arquivo (`index.html`), utilizando apenas tecnologias nativas da web:

* **HTML5:** Estruturação semântica do formulário e exibição dos resultados.
* **CSS3:** Estilização moderna, layout centralizado, responsividade e feedback visual por cores conforme o resultado.
* **JavaScript (Vanilla):** Lógica de validação de dados, conversão automática de unidades (centímetros para metros), cálculo matemático e manipulação dinâmica do DOM.

---

## 📖 Como Utilizar

1. Acesse o link da aplicação publicada ou abra o arquivo `index.html` em qualquer navegador web.
2. No campo **Peso (kg)**, insira o seu peso atual (exemplo: `70.5`).
3. No campo **Altura (m ou cm)**, insira a sua altura em metros ou centímetros (exemplo: `1.75` ou `175`).
4. Clique no botão **Calcular** para visualizar o valor do seu IMC e a respectiva classificação.
5. Caso deseje realizar uma nova consulta, clique no botão **Limpar** para resetar os campos.

---

## 🧮 Fórmula Matemática do IMC

O cálculo do Índice de Massa Corporal é realizado dividindo o peso (em quilogramas) pelo quadrado da altura (em metros):

$$\text{IMC} = \frac{\text{Peso (kg)}}{\text{Altura (m)}^2}$$

### Tabela de Classificação (OMS)

| Resultado do IMC | Classificação |
| :--- | :--- |
| Abaixo de 18,5 | Abaixo do peso |
| Entre 18,5 e 24,9 | Peso normal |
| Entre 25,0 e 29,9 | Sobrepeso |
| Entre 30,0 e 34,9 | Obesidade Grau I |
| Entre 35,0 e 39,9 | Obesidade Grau II |
| Acima de 40,0 | Obesidade Grau III |

> **Nota:** O IMC é um indicador geral e não substitui a avaliação individualizada de um profissional de saúde.

---

## 🛠️ Créditos e Ferramentas de Desenvolvimento

Este projeto foi desenvolvido com o apoio do seguinte ecossistema de ferramentas:

* **Geração de Código:** [Google Gemini](https://gemini.google.com/)
* **Editor de Código:** [Visual Studio Code (VS Code)](https://code.visualstudio.com/)
* **Versionamento:** [GitHub Desktop](https://desktop.github.com/)
* **Hospedagem e Publicação:** [GitHub Pages](https://pages.github.com/)

---

Desenvolvido por **Suellen Brunelli**.
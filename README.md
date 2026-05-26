# 🌸 Date App - Quer ir a um encontro comigo? 🌸

> Um site interativo, responsivo e super fofo desenvolvido para fazer um pedido de encontro especial, com direito a agendamento e escolha do cardápio!

---

## ✨ Funcionalidades

* **🎈 Botão "Não" Fugitivo:** Se o usuário tentar recusar o pedido, o botão foge aleatoriamente pela tela (tanto no mouse hover quanto no touch do celular), tornando a rejeição matematicamente impossível.
* **🎉 Tela de Surpresa:** Uma reação divertida e comemoração após o clique no "SIM".
* **📅 Agendamento Inteligente:** Inputs interativos para a pessoa escolher a melhor data e horário para o encontro.
* **🍕 Cardápio de Escolha Única:** Uma seção estilizada em Grid onde a pessoa escolhe o que está com desejo de comer (Pizza, Sushi, Hambúrguer, etc.).
* **💌 Envio via E-mail Assíncrono:** Os dados de data, hora e comida são enviados diretamente para o meu e-mail em segundo plano (via Fetch API), sem recarregar a página ou quebrar a experiência.
* **📱 100% Responsivo:** Design adaptado perfeitamente para telas de computadores e smartphones.

---

## 🚀 Tecnologias Utilizadas

Para manter o projeto leve, rápido e de fácil hospedagem, foi utilizado apenas front-end nativo:

* **HTML5** (Estruturação das telas em formato Single Page Application)
* **CSS3** (Estilização baseada em paleta de cores pastel, Google Fonts `Quicksand`/`Nunito` e transições suaves)
* **JavaScript (Vanilla)** (Lógica do botão fugitivo, controle de estados das telas e consumo de API)
* **Web3Forms / Formspree** (Serviço de integração de e-mail sem necessidade de back-end próprio)

---

## 🛠️ Como Funciona o Envio de E-mail?

O formulário está integrado com uma API rest de e-mail. Para rodar o seu próprio:
1. Pegue uma chave de acesso gratuita em [Web3Forms](https://web3forms.com/).
2. Adicione sua chave no input hidden do arquivo `index.html`:
   ```html
   <input type="hidden" name="access_key" value="SUA_CHAVE_AQUI">
3. Pronto! As respostas do date cairão direto na sua caixa de entrada.

   
## 🌐 Hospedagem
O site está configurado para ser distribuído estaticamente de forma gratuita em plataformas como:

GitHub Pages 🐙
Vercel ▲
Netlify ⚡

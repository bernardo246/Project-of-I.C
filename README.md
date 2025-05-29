#  Portfólio de Projeto — The Last Defuse

Este é um projeto simples em HTML com estrutura de layout, botões interativos e conteúdo descritivo. Ele representa um portfólio estudantil voltado para a área de Ciência da Computação, com foco em projetos físicos envolvendo Arduino e conceitos de interação homem-máquina.

---

##  Descrição do Projeto

O artefato apresentado chama-se **The Last Defuse**, inspirado no jogo *Keep Talking and Nobody Explodes*. Trata-se de um dispositivo interativo construído com **Arduino**, **LEDs**, **botões arcade** e outros componentes eletrônicos, simulando uma bomba de treinamento para jogos e atividades educativas.

---

##  Objetivos Profissionais

-  Ganhar em dólar (freelancer, remoto ou internacional)
-  Trabalhar com Inteligência Artificial
-  Resolver problemas sociais através da tecnologia
-  Atuar com análise e manipulação de dados

---

##  Componentes Utilizados

- **Arduino Uno/Nano/Mega** – microcontrolador principal
- **Botões arcade** – interação principal do usuário
- **LEDs indicadores** – mostram o estado de cada módulo
- **Buzzer e temporizador** – simulam efeitos de tensão
- **Gabinete temático** – inspirado em bombas de filmes/jogos

---

##  Imagem do Protótipo

O projeto exibe uma imagem (`prototipo.JPG`) do dispositivo físico desenvolvido, representando o protótipo funcional.

---

##  Links de Estudo

Dois botões interativos levam a conteúdos educativos sobre Arduino:

- **Curso de Arduino** – redireciona para um curso online
- **Aulas no YouTube** – redireciona para vídeos tutoriais

Esses redirecionamentos são feitos com **JavaScript externo**.

---

##  Estrutura do Projeto


---

##  Exemplo do `script.js`

```javascript
document.getElementById("botao").addEventListener("click", function () {
  window.open("https://www.primecursos.com.br/arduino-basico", "_blank");
});

document.getElementById("click").addEventListener("click", function () {
  window.open("https://www.youtube.com/results?search_query=curso+arduino", "_blank");
});
```
## Arquivo do `style.css`
O arquivo contem estruturas para promover o aprimoramento estético da pagina `HTML` como a mudança de cor do background e ajuste do tamanho das imagens como é mostrado a seguir:

```css
img {
    width: 300px;
    height: auto;
    /* mantém a proporção */
    alt: "prototipo não funcional ";
}
body {
    background-color: #04d5ff;
    display: flexbox;
    align-items: center;
```

## Outras páginas 
- Página de curiosidades
aborda curiosidades sobre o arduino e seus possíveis usos como exemplo Automação Residencial 
- Página sobre o curso de Ciência da computação
aborda os interesses de seguimento de carreira, uma breve descrição do curso e o perfil mais comum do tipo de estudante 

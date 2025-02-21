# 🏆 Projeto Mario Kart com Node.js

<table>
        <tr>
            <td>
                <img src="./docs/header.gif" alt="Mario Kart" width="200">
            </td>
            <td>
                <b>Objetivo:</b>
                <p>Mario Kart é uma série de jogos de corrida desenvolvida e publicada pela Nintendo. Nosso desafio será criar uma lógica de um jogo de vídeo game para simular corridas de Mario Kart, levando em consideração as regras e mecânicas abaixo.</p>
            </td>
        </tr>
    </table>

## 🎯 Objetivo
Este projeto simula uma corrida inspirada no universo de **Mario Kart**, utilizando lógica de programação para representar as mecânicas do jogo.

## 🚀 Como rodar o projeto

### 🔧 Pré-requisitos
Antes de começar, certifique-se de ter o **Node.js** instalado.

### 📅 Instalação
Clone o repositório:
```bash
git clone https://github.com/Matheusisa/Mario_Kart_NodeJS.git
cd mario-kart-nodejs
npm install
```

### ▶️ Executando o jogo
Para iniciar a simulação, utilize o comando:
```bash
node index.js
```

---

## 🏁 Regras & Mecânicas

- Dois personagens são sorteados para competir.
- A corrida tem 5 rodadas e cada rodada pode ter um dos três cenários:
  - **Reta**: Vence quem tiver maior soma entre um dado de 6 lados e o atributo **velocidade**.
  - **Curva**: Vence quem tiver maior soma entre um dado de 6 lados e o atributo **manobrabilidade**.
  - **Confronto**: O jogador com menor soma entre um dado de 6 lados e o atributo **poder** perde um ponto.

✅ **Vitória:** No final, o personagem com mais pontos vence!

---

## 🏃️️ Personagens

<h2>Players</h2>
      <table style="border-collapse: collapse; width: 800px; margin: 0 auto;">
        <tr>
            <td style="border: 1px solid black; text-align: center;">
                <p>Mario</p>
                <img src="./docs/mario.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 4</p>
                <p>Manobrabilidade: 3</p>
                <p>Poder: 3</p>
            </td>
             <td style="border: 1px solid black; text-align: center;">
                <p>Peach</p>
                <img src="./docs/peach.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 3</p>
                <p>Manobrabilidade: 4</p>
                <p>Poder: 2</p>
            </td>
              <td style="border: 1px solid black; text-align: center;">
                <p>Yoshi</p>
                <img src="./docs/yoshi.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 2</p>
                <p>Manobrabilidade: 4</p>
                <p>Poder: 3</p>
            </td>
        </tr>
        <tr>
            <td style="border: 1px solid black; text-align: center;">
                <p>Bowser</p>
                <img src="./docs/bowser.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 5</p>
                <p>Manobrabilidade: 2</p>
                <p>Poder: 5</p>
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Luigi</p>
                <img src="./docs/luigi.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 3</p>
                <p>Manobrabilidade: 4</p>
                <p>Poder: 4</p>
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Donkey Kong</p>
                <img src="./docs/dk.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 2</p>
                <p>Manobrabilidade: 2</p>
                <p>Poder: 5</p>
            </td>
        </tr>
    </table>

<p></p>
## 🛠️ Tecnologias utilizadas
- Node.js
- JavaScript

---

## 🤝 Contribuições
Se quiser contribuir, siga os passos:
1. **Faça um fork** do repositório
2. **Crie uma branch** (`git checkout -b feature-minha-mudanca`)
3. **Commit suas alterações** (`git commit -m 'Adicionando nova funcionalidade'`)
4. **Envie um Pull Request**

---

## 🐝 Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 📩 Contato
Caso tenha dúvidas ou sugestões, entre em contato:

- 🐙 GitHub: [@Matheusisa](https://github.com/Matheusisa)

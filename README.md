# Grupo

| Nome | Número |
| Gabriel Lima | Nº34981 |
| Andre | Nº34984 | 


Patos em Fuga 
Descrição do Jogo


O objetivo é chegar primeiro à meta enquanto evita obstáculos, atravessa zonas especiais e utiliza habilidades para ganhar vantagem sobre os adversários.

O jogo utiliza:
- movimento livre em mundo aberto;
- colisões;
- efeitos sonoros;
- inteligência artificial;
- HUD de classificação;
- habilidades especiais.

---


# Funcionalidades Implementadas

## Movimento do Jogador
- Movimento em 8 direções;
- Sistema de aceleração ("boost");
- Rotação do pato conforme a direção.

---

## Sistema de Câmara
- Câmara segue o jogador;
- O mapa é maior que a janela do jogo.

---

## Mundo Aberto
O jogo não utiliza tiles tradicionais.  
O mapa é gerado através da leitura de pixels de uma imagem.

---

## ✅ Colisões
Existem colisões com:
- pedras;
- limites da pista;
- zonas especiais.

---

## Sons
O jogo tem:
- música ambiente;
- som ao atravessar folhas;
- som ao tocar no lixo;
- som de quack ao bater em obstáculos;
- ataque sonoro.

---

## Inteligência Artificial
Os patos inimigos:
- movimentam-se autonomamente;
- seguem a pista;
- desviam-se de obstáculos;
- competem pela meta.

---

## Sistema de Ranking
HUD no canto superior esquerdo:
- 1º lugar
- 2º lugar
- 3º lugar
- último lugar

---

## Efeitos Especiais
- Efeito de cegueira;
- Ataque sonoro em área;
- Cooldown de habilidades.

---

# 🎯 Controlos

| Tecla | Ação |
|---|---|
| W | Mover para cima |
| S | Mover para baixo |
| A | Mover para esquerda |
| D | Mover para direita |
| Espaço | Ataque sonoro |

---

# Decisões Tomadas

## Uso de mapa por cores
Foi utilizado um sistema baseado em cores para facilitar:
- criação da pista;
- spawn de jogadores;
- definição de zonas especiais.

### Cores utilizadas:
| Cor | Função |
|---|---|
| Azul | Pista |
| Preto | Obstáculos |
| Roxo | Zona lenta |
| Vermelho | Lixo |
| Amarelo | Spawn do jogador |
| Verde | Spawn dos inimigos |
| Laranja | Meta |

---


## Sistema de IA
Foi criada uma IA simples baseada em:
- direção até à meta;
- deteção de obstáculos;
- movimentação autónoma.

---

## HUD visual
Foram utilizadas imagens para representar a posição do jogador de forma mais intuitiva.

---

# Estrutura do Projeto

```text
Content/
│
├── mapa.png
├── Pato.png
├── Pedra.png
├── Water.mp3
├── Quack.wav
├── Leaves.wav
├── Trash.wav
└── ...

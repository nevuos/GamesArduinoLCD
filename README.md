
### README.md para o Projeto "Stickan Runner"

---

## Descrição
"AMADO Runner" é um jogo simples e divertido projetado para ser executado em um Arduino com um display LCD 16x2 e um botão. No jogo, o jogador controla um personagem (o "herói") que corre continuamente, evitando obstáculos. O objetivo é percorrer a maior distância possível sem colidir com os blocos que aparecem no caminho. O jogo aumenta de dificuldade conforme a distância percorrida, com a velocidade do herói aumentando gradualmente.

## Componentes Necessários
- Arduino UNO (ou similar)
- Display LCD 16x2 ou 16X4 com interface I2C
- Buzzer
- Botão
- Resistores, cabos e protoboard para as conexões

## Conexões
- O display LCD deve ser conectado ao Arduino via I2C.
- O botão deve ser conectado ao pino definido por `PIN_BUTTON` (pino 2 por padrão).
- O buzzer deve ser conectado ao pino `BUZZER_PIN` (pino 3 por padrão).

## Configuração e Execução
1. **Carregar o Código:** Carregue o código-fonte no Arduino usando a IDE do Arduino.
2. **Montagem do Hardware:** Monte o circuito conforme descrito na seção "Conexões".
3. **Iniciar o Jogo:** Após ligar o Arduino, o jogo iniciará com uma animação. Pressione o botão para começar a jogar.
4. **Jogar:** Pressione o botão para fazer o herói pular sobre os obstáculos. O jogo termina quando o herói colide com um obstáculo.
5. **Reiniciar:** Após o fim do jogo, aguarde alguns segundos para a tela de Game Over desaparecer, e então pressione o botão para iniciar um novo jogo.

## Personalização
O código é modular e permite fácil personalização. Você pode alterar os sprites dos personagens, a velocidade do jogo, e outros parâmetros para criar uma experiência de jogo única.

---


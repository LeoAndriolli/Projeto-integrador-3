# Concepção

Acesso rápido:

- [Início](https://github.com/JoaoMario109/projeto-integrador-2)
- [Design/Projeto](./design.md)
- [Implementação](./implement.md)
- [Operação](./operate.md)

<p>
O projeto visa o desenvolvimento de um sistema de automação de tarefas residenciais que atendam aos requisítos do cliente, implementando todas as necessidades e estabelecendo um sistema final de baixo custo, fácil utilização e manutenção bem como visando o conforto e praticidade gerada pelo sistema final.
</p>
<p>
Cada participante da disciplina irá desenvolver o projteto em torno de uma maquete que terá por objetivo apresentar de maneira simplificada o funcionamento do sistema simulando sua operação em um ambiente de produção.
</p>
<hr>

### Materiais Utilizados

<ul>
  <li>Controlador:
    <ul>
      <li>Placa MEGA 2560 R3 + Fonte + Cabo USB para Arduino</li>
    </ul>
  </li>
  <li>Sensores:
    <ul>
      <li>Umidade e Temperatura DHT11</li>
      <li>Presença e Movimento PIR</li>
      <li>Gás MQ-2 Inflamável e Fumaça</li>
      <li>Ultrasônico HC-SR04</li>
    </ul>
  </li>
  <li>Módulos:
    <ul>
      <li>Sensor de Umidade/Nível Água Chuva</li>
      <li>Relé 5 V e um Canal</li>
      <li>Matriz de LED 8×8 com MAX7219</li>
    </ul>
  </li>
  <li>Micro Servo SG92R 9g TowerPro</li>
  <li>Display LCD 16×2 I2C Backlight Azul</li>
  <li>Buzzer Passivo</li>
</ul>

<hr>

### Objetivação Prévia do Projeto

<ul>
  <li>Monitoramento:
    <ul>
      <li>Vazamentos de gás e focos de fumaça no ambiente</li>
      <li>Presença de indivíduo próximo à central</li>
      <li>Presença de indivíduo na área com vazamento de gás / foco de fumaça</li>
      <li>Monitoramento da temperatura no ambiente</li>
    </ul>
  </li>
  <li>Controle:
    <ul>
      <li>Controle de sprinklers de água para incêndio</li>
      <li>Abertura e fechamento de janela para ventilação em caso de gás / incêndio</li>
      <li>Controle do estado de ligado ou não do display da central de controle</li>
    </ul>
  </li>
  <li>Ações:
    <ul>
      <li>Na presença de gás, abrir a janela</li>
      <li>Ligamento e desligamento do display da central no caso de presença de indivíduo próximo</li>
      <li>Disparo de alarme(buzzer) no caso de fumaça ou vazamento de gás</li>
      <li>Se é identificada fumaça, abre ou fecha a janela dependendo se há ou não indivíduos próximos</li>
      <li>Quando alguém se aproxima ao ambiente com risco, padrão do buzzer muda</li>
      <li>Acionar relé para ligar sprinklers de água no caso de incêndio, enquanto a temperatura permanecer alta(fogo) manter o sprinkler ligado</li>
    </ul>
  </li>
  <li>Visualização:
    <ul>
      <li>Fornecer uma interface para interação com o sistema usando o display lcd</li>
      <li>Exibir padrões sonoros do buzzer diferentes dependendo da situacão de risco</li>
      <li>Mostrar estado do sistema usando a matriz de leds 8x8</li>
    </ul>
  </li>
</ul>

## Referências

Colocar aqui as referências. _Sempre em formato ABNT_.

ADMIN. **Casa inteligente: a tecnologia de Black Mirror já está o seu alcance!** Disponível em: <https://www.delmak.com.br/casa-inteligente-a-tecnologia-de-black-mirror-ja-esta-ao-seu-alcance/>. Acesso em: 23 mai. 2021.

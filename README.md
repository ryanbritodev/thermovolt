# 🌱⚡ Global Solution Green Energy 

<p align="center">
<a href=""><img src="assets/samepy-logo.png" alt="Samepy Logo" border="0" width=60%></a>
<a href="https://www.fiap.com.br/graduacao/global-solution/"><img src="assets/green-energy.svg" alt="Green Energy Logo" border="0" width=38%></a>
</p>

## 👨🏻‍💻 Equipe:
- Diogo Leles Franciulli, RM558487
- Felipe Sousa de Oliveira, RM559085
- Ryan Brito Pereira Ramos, RM554497
<div style="display: flex;">
 <a href="https://www.linkedin.com/in/diogo-leles-franciulli/"><img src="assets/diogo.jpg" alt="Diogo Leles Franciulli" width="150px"></a>
 <a href="https://www.linkedin.com/in/ulipese/"><img src="assets/felipe.jpg" alt="Felipe Sousa de Oliveira" width="150px"></a>
 <a href="https://www.linkedin.com/in/ryanbritodev"><img src="assets/ryan.jpg" alt="Ryan Brito Pereira Ramos" width="150px"></a>
</div>

## 👨🏻‍🏫 Professor: 
- Paulo Marcotti, PF2150
<div style="display: flex;">
<a href="https://www.linkedin.com/in/pmarcotti/"><img src="assets/marcotti.jpg" alt="Paulo Marcott" width="150px"></a>
</div>

# ♻️ SamepyEco: Gerador Termoelétrico Sustentável 

## 📜 Descrição

O SamepyEco é uma solução inovadora e sustentável que utiliza o calor gerado pelos raios solares para produzir energia elétrica de maneira eficiente e ecológica. Nosso sistema termoelétrico aproveita a diferença de temperatura entre dois reservatórios (um de água quente e outro de água fria) para gerar eletricidade, eliminando a necessidade de combustíveis fósseis. O SamepyEco foi projetado para atender tanto áreas remotas, que frequentemente sofrem com falta de acesso a fontes confiáveis de energia, quanto indústrias que desejam reduzir seu desperdício energético e custo operacional. Nosso objetivo é contribuir para o uso consciente de recursos naturais, promovendo a preservação ambiental e a sustentabilidade energética.

A ideia da geração de energia termoelétrica sustentável surgiu a partir do tema proposto pelo Global Solution: encontrar maneiras de gerar energia limpa e eficiente enquanto aproveitamos recursos disponíveis de maneira sustentável. A inspiração para o projeto veio ao observar fontes de calor "desperdiçadas" no ambiente, como o calor produzido por águas termais, processos industriais, aquecimento solar, e até mesmo o calor dissipado em equipamentos eletrônicos. Nossa visão foi transformar esse calor não aproveitado em eletricidade, utilizando uma solução compacta, acessível e sustentável.

A pastilha de Peltier foi escolhida como a tecnologia central do projeto devido à sua capacidade de converter diferenças de temperatura diretamente em energia elétrica. Isso, aliado à possibilidade de escalabilidade em aplicações como sistemas solares, termas, indústrias, ou até residências, tornou o conceito especialmente relevante no contexto de preservação ambiental e sustentabilidade energética.

## 🌡️❄️ Como Funciona a Geração de Energia com a Pastilha de Peltier? 
A pastilha de Peltier (ou módulo termoelétrico) é um dispositivo que pode funcionar de duas maneiras:

- **Gerador Termoelétrico (Modo Seebeck):**
Quando há uma diferença de temperatura (Δ𝑇) entre suas faces, a pastilha converte esse gradiente térmico em energia elétrica, gerando uma tensão proporcional à diferença de temperatura. Este fenômeno é utilizado em aplicações de geração de energia a partir de calor residual.
- **Bomba de Calor (Modo Peltier):**
Ao aplicar uma corrente elétrica, o módulo transfere calor de uma face para a outra, criando uma diferença de temperatura. Essa propriedade é utilizada para aquecer ou resfriar superfícies, sendo comum em sistemas de refrigeração compactos (como bebedouros ou purificadores de água).

<br>
<img src="assets/peltier-diagram-fiap.png" width="30%" alt="Diagrama Peltier"/>

_Em ambas as funções, a eficiência da pastilha depende das propriedades termoelétricas dos materiais utilizados e do coeficiente de Seebeck, que mede a relação entre a diferença de temperatura e a tensão gerada._
<br>

No nosso projeto, a pastilha funciona no **modo Seebeck**. A pastilha é composta por dois tipos de semicondutores, chamados N-type (rico em elétrons) e P-type (pobre em elétrons). Quando uma das superfícies da pastilha é aquecida (e a outra permanece fria), cria-se uma diferença de temperatura (ΔT). Essa diferença de temperatura provoca um movimento de elétrons através dos semicondutores, gerando uma corrente elétrica. Esse fenômeno é conhecido como efeito Seebeck.

No caso do nosso projeto, o calor gerado por águas aquecidas (como em fontes termais ou reservatórios aquecidos pelo sol) aquece um lado da pastilha, enquanto o outro lado é resfriado por água fria ou em temperatura ambiente (como em um reservatório isolado ou refrigerado).
A diferença de temperatura gera eletricidade, que pode ser armazenada em baterias ou usada diretamente para alimentar dispositivos.

<br>
<img src="assets/peltier.png" width="40%" alt="Interior Peltier"/>

## 🧮 O que é o Coeficiente Seebeck?
O coeficiente Seebeck é uma propriedade intrínseca dos materiais termoelétricos, que determina a eficiência com que eles convertem uma diferença de temperatura em energia elétrica. Ele é medido em **microvolts por kelvin (µV/K)** e representa a tensão elétrica gerada por cada unidade de diferença de temperatura entre os dois lados do material.

### Matematicamente, a tensão gerada (V) pela pastilha de Peltier pode ser expressa como:

<img src="assets/seebeck.png" width="40%" alt="Fórmula Seebeck"/>

### Onde:
- S é o coeficiente Seebeck.
- ΔT é a diferença de temperatura entre os dois lados da pastilha.

Quanto maior o coeficiente Seebeck de um material, mais eficiente ele será na conversão de calor em eletricidade. Por isso, materiais avançados como ligas de bismuto-telúrio são frequentemente usados em módulos Peltier de alta eficiência.

## 🔌 Componentes
<img src="assets/componentes-circuito.png" width="70%" alt="Componentes"/>

- 1 ESP32
- 1 Protoboard
- 3 Pastilhas Peltiers TEC1-12706
- 2 Sensores Encapsulados de Temperatura DS18B20
- 1 Sensor de Tensão DC 0-25V
- 1 Display LCD I2C
- 2 Recipientes de Alumínio
- 1 Pasta Térmica
- 1 Rolo de Barbante
- 1 Placa de Isopor
- 1 Power Bank
- Jumper Cables

### Todos os componentes eletrônicos foram adquiridos na loja de eletrônicos [Saravati](https://www.saravati.com.br/), localizada na Rua Vitória Número 39, no Bairro da Santa Ifigênia em São Paulo. Gostaríamos de agradecer a equipe da Saravati pelo rápido atendimento e pelo desconto especial oferecido aos alunos da FIAP 😄

<img src="assets/saravati.jpg" width="35%" alt="Saravati"/>

## ⚒️ Montagem
<div>
 <img src="assets/circuito.jpg" width="35%" alt="Circuito"/>
 <img src="assets/maquete.jpg" width="37.5%" alt="Protótipo"/>
 <img src="assets/peltier-pasta.jpg" width="14.1%" alt="Peltier com Pasta Térmica"/>
</div>

<br>

Criamos um protótipo que demonstra como a energia pode ser gerada de forma sustentável utilizando o diferencial de temperatura. O sistema utiliza as pastilhas Peltier posicionadas entre os dois recipientes (formas de bolo feitas de alumínio): um com água quente e outro com água fria. O calor da água quente aquece um lado das pastilhas, enquanto a água fria resfria o outro, criando um gradiente térmico que gera energia elétrica (entre os recipientes, utilizamos uma pasta térmica que auxilia na troca de calor). No protótipo, essa energia é usada para alimentar um pisca-pisca instalado na cerca de uma casinha, ilustrando o funcionamento do sistema de forma prática. Para criar o monitoramento, utilizamos um ESP32 abastecido por um Power Bank, que registra as temperaturas dos recipientes com sensores DS18B20 e mede a tensão gerada por meio de um sensor DC 0-25V. Os dados são exibidos em tempo real em um display LCD e enviados através do protocolo HTTP ao ThingSpeak, permitindo acompanhar a eficiência do sistema em tempo real enquanto ele funciona.

## 📊 Canal de Processamento de Dados no Thingspeak
<div>
 <img src="assets/thingspeak.png" width="35%" alt="Thingspeak"/>
 <img src="assets/samepyeco-thingspeak.png" width="25.6%" alt="SamepyEco Thingspeak"/>
</div>
Nosso sistema integra o monitoramento local com o envio de dados para a plataforma oficial da Samepy utilizando o ESP32 e o ThingSpeak. Esses dados são coletados, tratados e enviados para análise e acompanhamento remoto:

### Coleta de Dados
#### Dados de Localização:
- Os dados de latitude, longitude, cidade e país são capturados utilizando a API da [ipgeolocation.io](https://ipgeolocation.io/). Essa API utiliza informações da rede Wi-Fi conectada ao ESP32 para determinar a localização geográfica do dispositivo, eliminando a necessidade de sensores GPS adicionais.
<img src="assets/ipgeolocation.png" width="35%" alt="IP Geolocation"/>

#### Temperaturas da Água:
- As temperaturas do lado frio e do lado quente das pastilhas Peltier são monitoradas por sensores de temperatura DS18B20. Esses dados são lidos pelo ESP32 em tempo real para avaliar a diferença térmica (ΔT) no sistema.

#### Tensão Gerada:
- O sensor de tensão DC 0-25V mede a energia elétrica gerada pelas pastilhas. Esse valor também é processado pelo ESP32.

## 🔗 Fields:
### [Canal SamepyEco no Thingspeak](https://thingspeak.mathworks.com/channels/2738000)
- Field 1: Latitude
- Field 2: Longitude
- Field 3: Cidade
- Field 4: País
- Field 5: Temperatura (Água Fria)
- Field 6: Temperatura (Água Quente)
- Field 7: Tensão

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>.github</b>: Nesta pasta ficarão os arquivos de configuração específicos do GitHub que ajudam a gerenciar e automatizar processos no repositório.

- <b>assets</b>: aqui estão os arquivos relacionados a elementos não-estruturados deste repositório, como imagens.

- <b>config</b>: Posicione aqui arquivos de configuração que são usados para definir parâmetros e ajustes do projeto.

- <b>document</b>: aqui estão todos os documentos do projeto que as atividades poderão pedir. Na subpasta "other", adicione documentos complementares e menos importantes.

- <b>scripts</b>: Posicione aqui scripts auxiliares para tarefas específicas do seu projeto. Exemplo: deploy, migrações de banco de dados, backups.

- <b>src</b>: Todo o código fonte criado para o desenvolvimento do projeto ao longo das 7 fases.

- <b>README.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

## 🔧 Como executar o código

*Acrescentar as informações necessárias sobre pré-requisitos (IDEs, serviços, bibliotecas etc.) e instalação básica do projeto, descrevendo eventuais versões utilizadas. Colocar um passo a passo de como o leitor pode baixar o seu código e executá-lo a partir de sua máquina ou seu repositório. Considere a explicação organizada em fase.*


## 🗃 Histórico de lançamentos

* 0.5.0 - XX/XX/2024
 * 
* 0.4.0 - XX/XX/2024
 * 
* 0.3.0 - XX/XX/2024
 * 
* 0.2.0 - XX/XX/2024
 * 
* 0.1.0 - XX/XX/2024
 *

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>


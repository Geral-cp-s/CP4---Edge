<p align='center' >
  <img width="250px" loading="lazy" src = "https://github.com/Geral-cp-s/Sprint-Edge/assets/110639916/aa204473-bba7-4dc2-8db1-ea5744b8e9bc"/>
</p>
<h1 align="Center">Monitoramento Global de Vinherias com FIWARE e ESP32</h1>

# Índice
* [Descrição do Projeto](#descricao)
* [Funcionalidades](#funcionalidades)
* [Pré-requisitos](#componentes)
* [Instalação](#exibicao)
* [Links Importantes](#links)
* [Autores](#autores)


<h2 id="Descricao">Descrição do projeto</h2>
<p>Este projeto faz parte do Check Point 4, com o objetivo de integrar uma solução de monitoramento de vinhedos globais utilizando a plataforma FIWARE como back-end. Utilizamos um ESP32 DEVKIT 1 equipado com um sensor de luminosidade (LDR) para coletar dados e enviá-los para o FIWARE, demonstrando a interoperabilidade da solução. O controle é feito utilizando o Postman para enviar comandos ao dispositivo.</p>

<h2 id="funcionalidades">Funcionalidades</h2>
  
 - `Funcionalidade 1` Capturar dados de luminosidade em um ambiente de vinhedo com um ESP32 equipado com um sensor LDR;

 - `Funcionalidade 2` Enviar os dados de luminosidade capturados para uma instância FIWARE, onde são processados e armazenados;

 - `Funcionalidade 3` Receber comandos do FIWARE via Postman, como ligar e desligar o LED onboard do ESP32.

<h2 id="Componentes">Pré-requisitos</h2>
  <ul>
    <li><strong>FIWARE Descomplicado</strong> instalado e configurado em um serviço de cloud;</li>
    <li><strong>ESP32 DEVKIT 1</strong> com sensor LDR;</li>
    <li><strong>Wokwi</strong> para simulação;</li>
    <li><strong>Postman</strong> para envio de comandos ao ESP32;</li>
    <li><strong>Docker e Docker Compose</strong> (para configurar FIWARE);</li>
    <li><strong>Conexão à Internet</strong> para interagir com a instância FIWARE;</li>
  </ul>

<h2 id="exibicao">Instalação</h2>
<p>1. Configuração do FIWARE:</p>
<ul>
  <li>Faça o download e configure o FIWARE Descomplicado em um Cloud Service Provider.</li>
  <li>Realize o setup e configure as medidas de segurança adequadas.</li>
  <li>Verifique o status com os procedimentos de health check.</li>
</ul>
<p>2. Configuração do ESP32:</p>
<ul>
  <li>Utilize o código disponível no repositório GitHub para programar o ESP32 DEVKIT 1.</li>
  <li>O código foi testado utilizando o simulador Wokwi.</li>
</ul>

<h2 id="links">Links Importantes</h2>
<h3>Medição de Voltas</h3>
  <ul>
    <li>Código .ino no GitHub:</li>
    <li>Simulação no Wokwi: https://wokwi.com/projects/407652271504728065 </li>
    <li>Vídeo Time-lapse: https://youtu.be/X6tdklxeRwI?si=hW-imGlvXW7bLGLj </li>
  </ul>

<h2 id="Autores">Autores</h2>

<div align="center">
  
| [<img loading="lazy" src="https://github.com/gvqsilva/CP2-Edge/assets/110639916/d022ed18-0057-4944-9e00-db796c6d2e45" width=115><br><sub>Gabriel Vasquez</sub>](https://github.com/gvqsilva)  |  [<img loading="lazy" src="https://github.com/gvqsilva/CP2-Web/assets/110639916/1eb7df1a-c0e8-4170-aabf-444cfb3c64f9" width=115><br><sub>Guilherme Araujo</sub>](https://github.com/guilhermearaujodec)  |  [<img loading="lazy" src="https://github.com/gvqsilva/CP2-Edge/assets/110639916/86514492-2b1e-4422-bdc0-0ec3c8be3dcc" width=115><br><sub>Augusto Douglas</sub>](https://github.com/gutomend)  |  [<img loading="lazy" src="https://github.com/gvqsilva/CP2-Edge/assets/110639916/4bb3084d-d1ff-4b49-ba37-96c8046f6e14" width=115><br><sub>Gustavo Oliveira</sub>](https://github.com/Gusta346) |
| :---: | :---: | :---: | :---: |

<ul>
  <li>Gabriel Vasquez - RM: 557056</li>
  <li>Guilherme Araujo - RM: 558926</li>
  <li>Gustavo Oliveira - RM: 559163</li>
  <li>Augusto Mendonça - RM: 558371</li>
</ul><br>

</div>

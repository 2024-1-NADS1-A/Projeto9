# FECAP - Fundação de Comércio Álvares Penteado

<p align="center">
<a href= "https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação de Comércio Álvares Penteado" border="0"></a>
</p>

# Projeto de Medição de Temperatura e Turbidez da Água com ESP32 e Firebase.

## Grupo Ocean

## Integrantes: <a href="https://www.linkedin.com/in/alexandra-christine-silva-590092257">Alexandra Christine </a>, <a href="https://linkedin.com/in/hebert-/">Hebert dos Reis Esteves	</a>, <a href="https://www.linkedin.com/in/karoline-lemos-540461296/">Karoline Lemos Avelar	</a>, <a href="https://www.linkedin.com/in/matheus-santos-morais/">Matheus Santos Morais	</a>.

## Professores Orientadores: <a href="https://www.linkedin.com/in/victorbarq/">Victor Bruno Alexander Rosetti de Quiroz</a>, <a href="https://www.linkedin.com/in/adriano-valente-534576135/">Adriano Valentea</a>, <a href="https://www.linkedin.com/in/eduardo-savino-gomes-77833a10/">Eduardo Savino Gomes</a>.

## Descrição

<p align="center">
<img src="https://pix4free.org/assets/library/2021-01-20/originals/game.jpg" alt="NOME DO JOGO" border="0">
  Game by <a href="http://www.nyphotographic.com/">Nick Youngson</a> <a rel="license" href="https://creativecommons.org/licenses/by-sa/3.0/">CC BY-SA 3.0</a> <a href="http://pix4free.org/">Pix4free</a>
</p>


O aumento da temperatura dos oceanos é uma ameaça grave para a biodiversidade marinha e a sustentabilidade dos ecossistemas costeiros. Nesse contexto, propomos implementar um sistema de monitoramento integrado, utilizando tecnologia IoT (Internet das Coisas), que compreende o Arduino, um sensor DS18B20 para temperatura e um Sensor de Turbidez para Monitoramento de Qualidade da Água.

Esse sistema permitirá avaliar a saúde dos ecossistemas marinhos ao fornecer dados precisos e em tempo real sobre a temperatura e a qualidade da água em regiões críticas, como próximas a recifes de coral. Os dados serão transmitidos para um banco de dados Firebase, que estará conectado a um aplicativo mobile desenvolvido no Flutter Flow. Esse aplicativo permitirá que os usuários visualizem e compreendam as variações de temperatura e turbidez da água de forma acessível.

Além de fornecer informações cruciais para a conservação marinha sustentável, o projeto visa promover a conscientização sobre a importância da preservação dos ecossistemas marinhos. Esperamos que esses dados influenciem positivamente políticas públicas e práticas de conservação ambiental para proteger o meio ambiente costeiro e garantir a sustentabilidade dos recursos marinhos no Brasil.

## 🛠 Estrutura de pastas

-Raiz<br>
|<br>
|-->documentos<br>
  &emsp;|-->antigos<br>
  &emsp;|Documentação.docx<br>
|-->executáveis<br>
  &emsp;|-->windows<br>
  &emsp;|-->android<br>
  &emsp;|-->HTML<br>
|-->imagens<br>
|-->src<br>
  &emsp;|-->Backend<br>
  &emsp;|-->Frontend<br>
|readme.md<br>

A pasta raiz contem dois arquivos que devem ser alterados:

<b>README.MD</b>: Arquivo que serve como guia e explicação geral sobre seu projeto. O mesmo que você está lendo agora.

Há também 4 pastas que seguem da seguinte forma:

<b>documentos</b>: Toda a documentação estará nesta pasta.

<b>executáveis</b>: Binários e executáveis do projeto devem estar nesta pasta.

<b>imagens</b>: Imagens do sistema

<b>src</b>: Pasta que contém o código fonte.

<br>## 🛠 Requisitos</br>
<br>🛠 Hardware</br>
<br>•	ESP32</br>
<br>•	Sensor de temperatura DS18B20</br>
<br>•	Sensor de turbidez</br>
<br>•	Protoboard e Jumpers</br>
<br>•	Conexão Wi-Fi</br>
<br>💻 Software:</br>
<br>•	Arduino IDE</br>
<br>•	Conta no Firebase</br>
<br>•	Conta no Flutter Flow (para visualização dos dados)</br>


<b>Android:</b>

Faça o Download do JOGO.apk no seu celular.
Execute o APK e siga as instruções de seu telefone.

```sh
Coloque código do prompt de comnando se for necessário
```

<b>Windows:</b>

Não há instalação! Apenas executável!
Encontre o JOGO.exe na pasta executáveis e execute-o como qualquer outro programa.

```sh
Coloque código do prompt de comnando se for necessário
```

<b>HTML:</b>

Não há instalação!
Encontre o index.html na pasta executáveis e execute-o como uma página WEB (através de algum browser).

## 💻 Configuração para Desenvolvimento

Descreva como instalar todas as dependências para desenvolvimento e como rodar um test-suite automatizado de algum tipo. Se necessário, faça isso para múltiplas plataformas.

Para abrir este projeto você necessita das seguintes ferramentas:

-<a href="https://godotengine.org/download">GODOT</a>

```sh
make install
npm test
Coloque código do prompt de comnando se for necessário
```

## 🗃 Histórico de lançamentos

A cada atualização os detalhes devem ser lançados aqui.

* 0.2.1 - 21/05/2024
    * CONSERTADO: Correção no Bug da turbidez  (Hebert)
* 0.2.0 - 21/05/2024
    * MUDANÇA: Compra da caixa organizadora (Alexandra) `setDefaultXYZ()`
* 0.1.1 - 11/01/2022
    * CONSERTADO: Crash quando chama `baz()` (Obrigado @NomeDoContribuidorGeneroso!)
* 0.1.0 - 10/01/2022
    * O primeiro lançamento adequado
    * MUDANÇA: Renomeia `foo()` para `bar()`
* 0.0.1 - 01/01/2022
    * Trabalho em andamento

## 📋 Licença/License

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/2024-1-NADS1-A/Projeto9">Ocean</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/2024-1-NADS1-A/Projeto9">FECAP, Alexandra Christine Silva Raimundo, Hebert dos Reis Esteves, Karoline Lemos Avelar, Matheus Santos Morais.</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>


## 🎓 Referências

Aqui estão as referências usadas no projeto.

1. MSC (Marine Stewardship Council). Oceanos em risco: Alterações climáticas e pesca. Disponível em: https://tinyurl.com/2nb87ddw Acesso em: 25 abr.2024.
2. CNN Brasil. Aquecimento dos oceanos está em níveis recordes há um ano; entenda o risco. Disponível em: https://tinyurl.com/4f4377f3.Acesso em: 25 abr. 2024.
3. Como usar um Sensor de Nível de Água. Disponível em: https://tinyurl.com/4a77w3kx. Acesso em: 25 abr. 2024.
4. Maretório: o impacto da maré nos territórios de comunidades costeiras. Disponível em: https://tinyurl.com/4htym3nc. Acesso em: 25 abr. 2024.
5. Efeitos do aquecimento global ameaçam vida marinha. Disponível em: https://tinyurl.com/bdcfmnnr. Acesso em: 25 abr. 2024.
6. Paulo Horta et a. Mudanças Climáticas e a zona costeira do Brasil: vulnerabilidades socioambientais e estratégias de ação. Vol.11.3, dez/2020. Disponível em: https://tinyurl.com/mrxezh7w. Acesso em: 25 abr. 2024.
7. Random Nerd Tutorials. ESP32 with DS18B20 Temperature Sensor using Arduino IDE. Disponível em: https://randomnerdtutorials.com/esp32-ds18b20-temperature-arduino-ide/. Acesso em: 22 maio 2024.
8. Blog da Robótica. Como utilizar o módulo sensor de turbidez de partículas suspensas na água com Arduino. Disponível em: https://www.blogdarobotica.com/2023/01/10/como-utilizar-o-modulo-sensor-de-turbidez-de-particulas-suspensas-na-agua-com-arduino/. Acesso em: 22 maio 2024.
9. TFK IoT Blog. Send DHT11 Sensor Data to Firebase. Disponível em: https://tfkiot.blogspot.com/2023/12/send-dht11-sensor-data-to-firebase.html. Acesso em: 22 maio 2024.
10. TFK IoT GitHub. Esp32-Esp8266_Send_DHT11_Data_To_FireStore. Disponível em: https://github.com/tfkiot/Esp32-Esp8266_Send_DHT11_Data_To_FireStore/tree/main. Acesso em: 22 maio 2024.

# Projeto_Objetos-inteligentes
Repositório criado para armazenar o código do projeto desenvolvido na matéria de objetos inteligentes conectados.

O código está disponibilizado nos aruivos abaixo: Teste_Portao e config.h

O arquivo "Teste_Portao" é o comando principal da placa ESP32, que é responsável por receber as informações da internet e acionar as informações de acordo.
O aruivo "config.h" é o reponsável por estabelecer a conexão da placa ESP32 com um roteador local para comunicação entre o Broker e a placa.



#Funcionamento
O ESP32 funciona como o controlador principal das entradas e saídas, assim como é o responsável pela conexão com a internet. O comando principal do sistema viria por meio da comunicação com a internet, via Adafruit.IO sendo o gatilho para o acionamento do motor executando a abertura do portão, onde permaneceria acionado até alcançar o fim de curso de portão aberto, no qual, após acionado a opção de fechamento do portão, acionaria a rotação inversa do motor para fechar o portão até o fim de curso de fechamento ficar acionado, onde se encerra o ciclo do programa.


#Materiais
Esp32, um chip microcontrolador que já vem integrado com uma antena que permite a conexão com a internet; Chave Táctil PBS-11B Preta e vermelha que irão simular a função dos sensores de fim de curso definindo os limites de estado de portão aberto ou fechado; Ponte H L298 H-bridge é o módulo para definir o sentido de rotação do motor; Motor DC 5V RF-300 elétrico  que é o atuador do sistema e fará o movimento de abrir e fechar do portão; compilador do arduino que terá a função de compilar e gravar o código no controlador; AdafruitIO que é o responsável para fazer a conexão com a internet via protocolo MQTT.

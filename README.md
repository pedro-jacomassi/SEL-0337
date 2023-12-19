# SEL-0337
Neste projeto, foram desenvolvidos duas práticas visando o uso de dois periféricos de uma Raspiberry Pi: um módulo de câmera e uma tag RFID. Além disso, o projeto tem o intuito de introduzir sobre o controle de versões de programa via Git/Github.

TAG RFID
Nesta parte da prática, foi desenvolvido um programa em python que foi capaz de gravar um texto com uma combinação dos números USP da dupla pelo módulo de identificação por rádio frequência e exibir o ID da tag utilizada no terminal da Raspi. Posteriormente, utilizou-se o mesmo código para a verificação do ID da tag no módulo de identificação e o respectivo print de "Acesso liberado"
Foi utilizado para isso, um módulo RFID-RC522 operando com High Frequency. A comunicação com a Raspiberry Pi é feito através da SPI. O programa desenvolvido está no código TAG.py

Nas imagens a seguir estão apresentadas fotografias de execução da prática. A primeira representa a montagem do circuito com os LEDs, seus respectivos resistores e o módulo de identificação, a segunda representa o acesso liberado e a terceira, o acesso negado.

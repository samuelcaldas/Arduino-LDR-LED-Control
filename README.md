# LDR_LED_Control

## Descrição

Este projeto demonstra como usar um resistor dependente de luz (LDR) como um sensor para medir a luz ambiente e controlar um LED de acordo. O código Arduino lê o valor analógico do LDR e o mapeia para uma porcentagem. Em seguida, ele envia a porcentagem para o monitor serial e liga o LED se a luz estiver abaixo de um determinado limite. O código é escrito no Arduino IDE e testado em uma placa Arduino Uno.

## Código

O código está disponível na pasta `src` com o nome `Aula_Pratica_8.ino`. Ele contém comentários explicando cada parte do código. Para executar o projeto, é necessário ter o Arduino IDE instalado e configurado. Em seguida, basta abrir o código, conectar a placa Arduino ao computador, selecionar a porta e o modelo da placa e fazer o upload do código. Depois, pode-se abrir o monitor serial para ver a porcentagem de luz e observar o comportamento do LED.

## Imagens

![Esquemático do projeto](images/Aula_Pratica_1_schematics.jpg)

Esquema do projeto.

![Imagem do projeto](images/Aula_Pratica_1.png)

Imagem do projeto montado em uma protoboard.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
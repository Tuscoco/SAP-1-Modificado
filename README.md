# SAP-1 Modificado
Este projeto visa a melhoria e expansão funcional da arquitetura do processador SAP-1, no contexto da disciplina de Arquitetura de Computadores 1.

O trabalho é uma evolução de um projeto anterior desenvolvido pelos alunos:
- Joana Mundim Cicarelli Pinheiro
- Lucas Fernandes Marinho
- Matheus Filipe Rocha Viana
- Lucas Grossi
- Ana Paula Natsumi Yuki

> [!WARNING]
> Compatibilidade: Este projeto é compatível exclusivamente com o simulador [Logisim](http://www.cburch.com/logisim/). Não é garantido que funcione no [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution).

## Sobre
O projeto funciona com as microinstruções sendo armazenadas em uma ROM (Read-Only Memory), fazendo com que o uma matriz de controle para gerá-las seja desnecessária. Essa ROM é endereçada com base nos estados do contador sequencial, T1, T2, T3, T4, T5 e T6 e nos códigos de operação das instruções o que permite modificações sem grandes dificuldades. Portanto, adicionamos elementos do trabalho do Gabriel ao projeto do André , incluindo instruções como  JMP,  SV, MUL, DIV, e principalmente a possibilidade de recriar a sequência de Fibonacci. Também foram criadas as instruções INC e DEC que não existiam antes. 

## Vídeo Demonstrativo
<p align="center">
	<a href="https://youtu.be/S2QjUBcLVOU">
		<img src="https://www.revista-programar.info/wp-content/uploads/2015/06/sap-1.png" width="500" alt="SAP-1 Turbo - AC1">
	</a>
</p>


## Como Executar
O sistema utiliza duas ROMs no contador-sequenciador: uma para endereços e outra para o controle. Caso as ROMs não contenham o conteúdo correto, você pode carregá-las a partir de arquivos de texto.

Arquivos de ROM
Os arquivos necessários para as ROMs estão disponíveis na pasta [`/roms_content`](/roms_content/).

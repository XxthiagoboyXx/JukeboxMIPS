**# JukeboxMIPS**  
#Nome   
JukeBoxMIPS  
#Descrição  
O JukeBoxMIPS  é um programa feito em Assembly MIPS através da ferramenta Mars. Este projeto é composto pelo code.asm, que é o arquivo onde está presente o código do programa, e uma série de arquivos .txt onde estão presentes as músicas que serão reproduzidas. Além disso, também foi criada a ferramenta “Transformador de musica.jar”, tal ferramenta possui a função de transformar notas musicais por extenso para caracteres ASCII, que são tocados em programas Assembly MIPS no Mars.  
#Objetivo   
O objetivo deste projeto foi desenvolver um programa capaz de realizar a reprodução, o toque de músicas no padrão MIDI(Musical Instrument Digital Interface).
#Avisos  
Para que o programa consiga ser executado de uma forma correta e cumprir seu objetivo de reproduzir músicas, a ferramenta Mars deve estar na mesma pasta em que o projeto com o código e os arquivos com as músicas.
#Modo de usar   
Inicialmente, após realizar a execução do código, aparecerá o menu em que o usuário deve escolher qual música deseja. Para selecionar a música desejada, o usuário deve informar o número que corresponde a música.  

![imageMenu](https://user-images.githubusercontent.com/72053163/146601895-efd5f46c-3cab-45b1-9694-983e1ca780d7.png)  

No caso de o usuário clicar em cancelar, aparecerá uma nova janela para que o usuário confirme se realmente deseja sair do programa ou não.  

![image](https://user-images.githubusercontent.com/72053163/146601964-c593c1d0-69c3-47ca-a1a8-1ecf5414745f.png)  

Se o usuário informe um valor que não consta no menu, aparecerá uma mensagem de erro e, o usuário voltará para o menu inicial.  

![image](https://user-images.githubusercontent.com/72053163/146601982-f8058324-49d5-41aa-8a8e-348d4a57386a.png)  

![image](https://user-images.githubusercontent.com/72053163/146601993-662a8d33-ec5b-4ff5-89f8-b52c9510614e.png)  

Caso a opção escolhida esteja entre 1 e 8, a música já é reproduzida automaticamente. Porém, no caso de o usuário optar pela opção 9, o mesmo deve informar o nome do arquivo em que a música está contida. De modo que, na nova janela que se é aberta, o usuário deve digitar NomeDoArquivo.txt. Por exemplo, supondo que o usuário deseja escolher a música “Despacito” e, o nome do arquivo em que a música está é despacito.txt, então o usuário deverá digitar o seguinte:  

![image](https://user-images.githubusercontent.com/72053163/146602025-2707bdf8-d349-40fe-8028-d964ed4ee038.png)  

Após dar o “OK”, caso o nome do arquivo informado seja válido e, contenha a música, então aparecerá uma nova tela para que o usuário informe em qual instrumento o mesmo deseja que a música seja tocada. Os instrumentos são: 1 – Piano; 2 – Violão; 3 – Flauta; e 4 – Teclado com efeitos. Neste caso, deve-se informar o número referente ao instrumento.  

![image](https://user-images.githubusercontent.com/72053163/146602049-6ae2a198-bee2-44c3-89ff-ff899b0ce52c.png)  

## 1. Introdução

O processo de inicialização é uma etapa fundamental em sistemas embarcados, sendo responsável por preparar o hardware e carregar o sistema operacional. Nesse processo, os *bootloaders* desempenham um papel importante ao realizar as etapas iniciais de configuração e transferir a execução para o kernel. Entre as soluções disponíveis para essa finalidade, destacam-se o Barebox e o U-Boot, utilizados em diferentes plataformas embarcadas.

Nesse contexto, este trabalho propõe a implementação do Barebox na plataforma BeagleBone Black, utilizando o cartão SD como meio de inicialização, de forma a preservar o conteúdo da memória eMMC. Além de explorar os procedimentos necessários para compilar e executar o *bootloader*, o projeto busca investigar seu desempenho em comparação com o U-Boot, considerando aspectos como o tempo de inicialização e o tamanho dos binários gerados.

O objetivo geral é implementar o Barebox na BeagleBone Black e avaliar seu funcionamento e desempenho em relação ao U-Boot. Como objetivos específicos, destacam-se a configuração do processo de inicialização pelo cartão SD, o carregamento do kernel Linux, a implementação de scripts e variáveis de ambiente e o desenvolvimento de um comando próprio no *bootloader*. Por fim, pretende-se realizar uma avaliação experimental que permita comparar as duas soluções em condições equivalentes.

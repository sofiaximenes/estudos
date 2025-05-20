# Estrutura dos diretórios Linux

## /bin (Binary)
possui executáveis essenciais ao sistema que podem ser usador pelos administradores e usuários comuns, como:

ls (listen) Lista os arquivos no diretório atual
ls -l Moatra detalhes dos arquivos (permissões, proprietário, tamanho...)
ls -a Mostra também os arquivos ocultos
ls -lh Mostra o tamanho dos arquivos de forma legível (ex: KB, MB)
cp (copy) Copia arquivos específicos de um diretório
ex: cp arquivo1 arquivo2: Copia arquivo1 para arquivo2
cp arquivo /destino/: Copia o arquivo para um diretório específico.

cp -r Copia recursivamente TODO o diretório (incluindo seus conteúdos)

mv (move) Move arquivos ou diretórios de um local para outro ou então o renomeia.
mv arquivo1 /destino/: Move arquivo1 para o diretório especificado.
mv arquivo1 arquivo2: Renomeia arquivo1 para arquivo2.
cat: concatena e mostra o que contém no arquivo, no terminal
ex: cat arquivo: Mostra o conteúdo do arquivo no terminal.

cat -n arquivo: Exibe o conteúdo do arquivo com números de linha.

## /sbin (System Binaries) 
Contém executáveis essenciais para administração do sistema, geralmente usados apenas pelo superusuário (root):

reboot: reinicia o sistema imediatamente

reboot -f: força o reinício

reboot now: equivale ao reboot

ifconfig (Interface Configurator): Configura e exibe informações sobre interfaces de rede no sistema (está obsoleto), substituído pelo ip.

## /boot
Armazena os arquivos necessários para inicializar o sistema, como o kernel Linux e o carregador de boot

## /etc

Contém arquivos de configuração do sistema e de aplicativos instalados

## /home

Diretório onde ficam os arquivos e configurações pessoais dos usuários do sistema

## lib e /lib64

Contém bibliotecas compartilhadas essenciais usadas por binários no /bin e /sbin.

## /usr (User System Resources)

Armazena aplicativos e bibliotecas de uso geral.

## /var (Variable)

Contém arquivos que mudam frequentemente, como logs, filas de impressão e caches.

## /tmp

Usado para arquivos temporários criados por usuários e aplicativos. Os dados aqui geralmente são apagados em cada reinicialização.

## /opt (Optional)

Local para instalação de aplicativos adicionais não gerenciados pelo sistema de pacotes padrão.

## /root

Diretório home do superusuário (root).

## /dev

Contém arquivos especiais que representam dispositivos de hardware do sistema.

## /mnt e /media

Locais para montar sistemas de arquivos temporários, como pen drives ou partições adicionais.


## /proc

Sistema de arquivos virtual que fornece informações sobre os processos em execução e o estado do kernel.

## /sys

Outro sistema de arquivos virtual, usado para expor informações sobre o hardware do sistema e a configuração do kernel.



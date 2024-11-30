Manual de Instalação do Termux e Script de Teste de Proxies

1. Instalar o Termux no Android

Abra a Google Play Store ou acesse o F-Droid.

Pesquise por Termux e instale o aplicativo.


2. Configurar o Termux

Abra o Termux e atualize o sistema executando os seguintes comandos:

pkg update && pkg upgrade


3. Instalar o Git e o Python

Para clonar o repositório e executar o script, você precisará instalar o Git e o Python. Execute os seguintes comandos no Termux:

pkg install git python


4. Clonar o Repositório com o Script

Agora, clone o repositório que contém o script de teste de proxies:

git clone https://github.com/DragonSCRIPTS/Proxy.git


5. Acessar o Diretório do Script

Navegue até o diretório onde o repositório foi clonado:

cd Proxy


6. Instalar Dependências

O script utiliza o módulo socket, que já é parte da biblioteca padrão do Python, então não é necessário instalar dependências adicionais.


7. Executar o Script

Para rodar o script de teste de proxies, execute o seguinte comando no Termux:

python script


8. Interagir com o Script

O script exibirá um menu no terminal, onde você pode gerar proxies aleatórios, testar proxies e exibir os proxies bem-sucedidos. As opções são:

1. Gerar proxies aleatórios.


2. Testar proxies gerados.


3. Exibir proxies bem-sucedidos.


4. Sair.




9. Pronto!

Agora você pode usar o script para testar proxies e visualizar os resultados diretamente no Termux.


Observações:

Certifique-se de ter uma conexão de internet estável para testar os proxies gerados.

Caso enfrente algum problema ao executar o script, verifique se o Python e as dependências estão corretamente instalados no Termux.

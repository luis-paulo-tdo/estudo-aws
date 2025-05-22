# Curso Começando em Cloud: Usando a AWS e explorando os recursos da nuvem como serviço

## 1. Navegando na Nuvem

### 1.1. Apresentação
- O curso apresentará a computação em nuvem e mostrará os primeiros passos.
- Ensinará os fundamentos da computação em nuvem (Cloud).
- Ensinará como selecionar serviços dentro da Cloud.
- Ensinará como gerenciar ambientes, criar e servir instâncias da AWS.
- Ensinará como subir um servidor na instância que foi criada.
- Ensinará como acessar a AWS via Interface de Linha de Comando.
- Ensinará sobre as diversas ferramentas, como a AWS SDK, CloudWatch, etc.

### 1.2. Identificando a Computação como Serviço
- Websites geralmente são criados para compartilhar conjuntos de informações.
- Websites possuem diferentes dados e informações textuais e multimídias.
- Estas informações geralmente estão em computadores dedicados à hospedagem.
- Estes computadores são chamados de servidores, que atendem a solicitações.
- Estas solicitações retornam conjuntos de informações para os solicitantes.
- Os solicitantes são chamados de clientes, que consomem as informações.
- O servidor pode ser um computador local dedicado a este compartilhamento.
- Outra forma de hospedar conteúdos é através da computação em nuvem.
- A computação em nuvem é uma oferta de diferentes serviços computacionais.
	- Armazenamento, processamento, arquivos, logs, banco de dados, etc.
- A computação em nuvem eliminar a preocupação com a infraestrutura física.
- O foco da infraestrutura física é deixado para o provedor dos serviços.
- Com isso, o desenvolvedor se preocupa apenas com a aplicação e o conteúdo.
- Computação em nuvem é vista quando compartilhamos arquivos via drive.
- Pode ser visto também quando usamos uma aplicação através do navegador.
	- Este é um exemplo de Software como Serviço, que é executado na nuvem.
- O objetivo principal é a oferta de recursos computacionais como serviços.

### 1.3. Entendendo onde está a Nuvem
- Toda vez que interagimos com um site, estamos solicitando recursos dele.
- As solicitações são enviadas a um servidor, que retorna dados ao site.
- Este servidor pode estar funcionando em uma máquina ou na nuvem.
- A Internet permite que os sites se comuniquem com estes servidores.
- Esta comunicação só é possível através de um conjunto de protocolos.
- Os protocolos ajudam a organizar em pacotes toda esta comunicação.
- Todos os pacotes carregam os endereços de origem e destino da entrega.
- Os pacotes também carregam o IP dos dispositivos que se comunicam.
- Através do protocolo TCP/IP, é feita a conexão entre os dispositivos.
- A comunicação passa por diversas camadas preparam e encaminham os dados.
- Existem dispositivos no caminho que servem para encaminhar os dados.
- Isto ocorre porque o solicitante e o servidor podem estar distantes.
- Estes dispositivos que encaminham os dados são os Roteadores.
- Na comunicação, a Camada de Aplicação faz a comunicação das aplicações.
	- O protocolo mais usado nela é o HTTP ou HTTPS.
- A Camada de Transporte atua na conexão segura dos dispositivos da rede.
	- O protocolo mais usado nela é o TCP/IP para a entrega dos pacotes.
- A Camada de Rede é responsável pelo endereçamento dos pacotes na rede.
	- O protocolo mais usado nela é o IP em suas versões 4 e 6.
- A Camada de Acesso provê os dispositivos físicos para a comunicação.
- Dentro de uma Rede de Computadores, existem os Dispositivos de Rede.
- Diferente dos Clientes e Servidores, eles atuam como encaminhadores.
- São através deles que as diferentes Redes são interconectadas no mundo.
- A Nuvem é um conjunto de Servidores que estão interconectados na Rede.
- O Servidores são Datacenters que centralizam recursos computacionais.
	- Eles têm uma grande capacidade de processamento e armazenamento.
- Estes Datacenters se conectam à Rede por canais de altíssima velocidade.
- Com isso, a entrega rápida dos recursos computacionais é garantida.
- Há muito tempo era impensável ter este tipo de estrutura na Internet.
- As velocidades de conexão eram muito baixas há pouco mais de uma década.
- Era inviável usar qualquer software dentro de um navegador web.
	- Era mais prático fazer o download e usar o software via desktop.
- Usar a Computação como Serviço é uma ótima solução para um site.
- Porém, existem muitos serviços e servidores disponíveis atualmente.

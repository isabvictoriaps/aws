![image 1 (1)](https://user-images.githubusercontent.com/93364960/233743602-d594a535-0f45-4958-8729-c71acec06676.png)

# ☁️ Amazon Web Service

<h3>Sumário</h3>
<a href="#compNuvem">1. O que é computação em nuvem?</a> <br>
<a href="#oquee">2. O que é a AWS?</a> <br>
<a href="#beneficios">3. Por que utilizar AWS?</a> <br>
<a href="#ips">4. Modelos de serviços em nuvem</a> <br>
<a href="#opca">5. OPEX vs CAPEX</a> <br>
<a href="#regioes">6. Regiões e Zonas de Disponibilidade</a> <br>
<a href="#ofertas">7. Tipos de ofertas </a> <br>
<a href="#lambda">8. O que é o AWS Lambda?</a>

<h2 id="compNuvem">O que é Computação em Nuvem?</h2>
É a entrega sob demanda de recursos computacionais, através de uma plataforma de serviço via internet, sem o gerenciamento ativo do usuário. O fornecimento de serviços de computação, incluindo servidores, armazenamento, bancos de dados, rede, software, análise e inteligência, pela Internet (“a nuvem”) colaboram para inovações mais rápidas, recursos flexíveis e economias de escala. 

<h2 id="oquee">O que é AWS?</h2>
A plataforma de computação em nuvem da Amazon (Amazon Web Service) é utilizada para o desenvolvimento de aplicações que podem ser altamente escaláveis devido aos recursos da plataforma e a virtualização.

É a plataforma mais adotada e abrangente, possuindo mais de 200 serviços disponibilizados em datacenters por todo o mundo. A AWS possui uma infra global e foi projetada para ser segura e flexível. <br>

Como plataforma, ela entrega:

- Um conjunto de soluções para armazenamento de dados;
- Infraestrutura de redes e servidores, virtualização;
- Computação e hospedagem de aplicações;
- Além de ferramentas para Machine Learning, Inteligência Artificial, Análises e Internet das Coisas. <br><br>

<h2 id="beneficios">Por que utilizar AWS?:</h2>
Os princípais benefícios de utilizar AWS nas aplicações são: <br><br>

<b> - Escalonamento automático e elasticidade: </b><br> 
Conforme a nossa aplicação demanda de mais recursos para a execução, mais recursos podem ser automaticamente liberadas a ela. Assim, atendendo a uma demanda maior e de forma transparente para o usuário final.  Da mesma forma que, quando a demanda diminui, os recursos que estão sobrando são removidos, diminuindo drasticamente os custos com o sistema.<br> 

<b> - Alta disponibilidade: </b><br> 
Devido a presença global da AWS, a sua infraestrutura está espalhada por diversos pontos do mundo, o que permite dados mais próximos do usuário final e, consequentemente, com menos latência. Além disso, é possível fazer um balanceamento de carga afim de equilibrar os acessos entre as diversas instancias da aplicação.

<b> - Baixo acoplamento: </b><br> 
Micro-serviços podem funcionar de maneira independente (uso de SNS, SQS, entre outros)

<b> - Baixo custo: </b><br>
A AWS oferece um preço baixa para os principais serviços, tendo nível gratuito para diversos recursos. Além disso, o usuário paga apenas pelo o que usa.

<b> - Segurança: </b><br>
A AWS possui uma infra extremamente segura, contando com recursos como: IAM users, IAM Groups, IAM Policies e IAM Roles para gerenciar o acesso e visibilidade de recursos. Além disso, é possível criar e gerenciar chaves de criptografia através do KMS (Key Management Service)

<h2 id="ips">Modelos de serviços em nuvem:</h2>
<h3>- 💻 IaaS (Infraestrutura como serviço - Hospedar)</h3>
É uma forma de entrega de serviços de infraestrutura pela Internet. A AWS Gerencia servidores, armazenamentos e networks. Iaas fornece os mesmos recursos que os data centers tradicionais, mas sem a necessidade de manter ou gerenciar fisicamente. 

<h3>- 💻 PaaS (Plataforma como serviço - Desenvolver)</h3>
PaaS oferece uma estrutura para os desenvolvedores criarem seus softwares. Em vez de codificar tudo desde o início, os fornecedores de PaaS geralmente têm blocos pré-construídos que os programadores podem simplesmente conectar e usar para construir rapidamente melhores aplicações.

<h3>- 💻 Saas (Software como serviço - Consumir)</h3>
Trata-se do uso de um software 100% na nuvem, podendo ser acessado de qualquer lugar, pois é via internet. 

<h2 id="opca">OPEX vs CAPEX</h2>
<h3> 💰 OPEX (Operational Expenditure) </h3>
OPEX é uma sigla utilizada para indicar os cutos operacionais relacionados pelas empresas. As despesas operacionais são aquelas relacionadas às operações diárias e dizem respeito aos investimentos em alocação de serviços, ou seja, são os "aluguéis" pagos mensalmente pelas empresas. Os serviços na nuvem estão alocadas nessa categoria. 

<h3> 💰 CAPEX (Capital Expenditure) </h3>
É o termo usado para se referir às despesas de capital realizadas por uma empresa. São compras projetadas para serem usadas por um longo período de tempo, como a de novos equipamentos. Alguns exemplos de CAPEX são: computadores, hardwares, servidores, automóveis, etc.

<h2 id="regioes">Regiões e Zonas de disponibilidade: </h2>
<h3> 📍 Região </h3>
A região é um conjunto de data centers em uma localização geográfica.
exemplo: América do Sul (São Paulo), Leste dos EUA (Norte da Virgínia)

<h3> 📍 Zona de disponibilidade </h3>
um ou mais data centers que estão na mesma região, atuando de forma independente em caso de falha.

<h3> 📍 Ponto de presença </h3>
É uma infra de servidores localizado próximo de uma Zona de Disponibilidade, que armazena os dados mais solicitados no cache, para entregar com menor latência uma requisição de consulta. 

<h2 id="ofertas">Tipos de ofertas: </h2>

<h3>🆓 Testes Gratuitos </h3>
Testes gratuitos de curto prazo

<h3>🆓 12 meses gratuitos </h3> 
Serviços gratuitos por 12 meses - com recursos limitados.

<h3>🆓 Sempre gratuito </h3> 
Nível gratuito que está disponível para todos.


<h2 id="lambda">O que é o AWS Lambda?:</h2>

O AWS Lambda é um serviço de computação sem servidor e orientado a eventos que permite executar código para praticamente qualquer tipo de aplicação ou serviço de backend sem provisionar ou gerenciar servidores. Você pode acionar o Lambda a partir de mais de 200 serviços da AWS e aplicações de software como serviço (SaaS) e pagar apenas pelo que usar. Algumas características do serviço são:
- O AWS Lambda escala automaticamente as aplicações, executando código em resposta a cada acionamento. O código é executado em paralelo e processa cada acionamento individualmente, escalando precisamente de acordo com o tamanho da carga de trabalho. <br>
<i>(ex: se chegar 5 requisições ao mesmo tempo, ele vai subir 5 instâncias lambda, vai processar cada um individualmente, uma não vai saber da existência da outra e vai retornar cada um para quem solicitou)</i> <br>
- Com o AWS Lambda, você é cobrado a cada 100 ms de execução do código e pelo número de vezes que o código é acionado. Você paga apenas pelo tempo de computação consumido
- Com o AWS Lambda, você pode otimizar o tempo de execução do código escolhendo o tamanho de memória ideal para a sua função. Você também pode habilitar a Simultaneidade provisionada para manter suas funções inicializadas e prontas para responder em questão de poucos segundos.
- É pago apenas pelo tempo de computação consumida
- Basta Carregar o código e o lambda se encarrega de todos os itens necessários para executar e permitir que o código seja escalável e com alta disponibilidade

<h3>Como funciona o Lambda na prática?</h3>

![WhatsApp Image 2023-04-23 at 13 51 50](https://user-images.githubusercontent.com/93364960/233853321-a924eb14-dbe2-4213-a939-a368c991a457.jpeg)

1. Você faz o upload do seu código para o AWS lambda ou escreve lá direto no editor da console AWS
2. Você configura seu código para ser executado a partir de outros serviços da AWS, como end-points HTTP (API Gateway) ou pode ser a partir de um arquivo ou evento do S3 
3. O Lambda executa o seu código apenas quando acionado, usando apenas os recursos de computação necessários
4. Você paga apenas pelo tempo de computação que você utilizar. <br><br>

<h3>Por trás do passo 3 - Quando o Lambda é executado</h3>

![image](https://user-images.githubusercontent.com/93364960/233853788-1fa049a8-a7c4-4028-944d-80956f1d9484.png)

1. Antes de tudo, quando o lambda é executado acontece o Download do código, a AWS faz isso por trás dos panos e com altíssima velocidade
2. Além de baixar o código, a AWS também faz o setup do container, preparando o ambiente que será rodado o noso código.
3. Inicialização e start do código, que é quando inicia o script/execução do código
4. Quando a execução de fato inicia, depois de todo o preparo e aquecimento do lambda

<i>O tempo de cold start seria o tempo antes da execução do código, no caso, o tempo entre chegar um evento de inicialização do código e ser executado</i> <br><br>

<h3>Preço no Lambda</h3>

- É cobrado pelo número de solicitações de suas funções e pela duração, o tempo que leva para seu código seja executado.
- O Lambda conta uma solicitação cada vez que começa a executar em resposta a uma notificação de evento ou chamada de invocação, incluindo invocações de teste do console.
- A duração é calculada a partir do momento m que seu código começa a ser executado até ele retornar ou encerrar, arredondando para os 100 ms mais próximos
- O preço depende da quantidade de memória que você alocar para sua função
- No modelo de recursos do AWS Lambda, você seleciona a quantidade de memória que quer para sua função. Capacidade de CPU e outros recursos são alocados de forma proporcional
- Um aumento no tamanho da memória aciona um aumento equivalente na CPU disponível para sua função

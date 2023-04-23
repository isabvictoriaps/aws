![image 1 (1)](https://user-images.githubusercontent.com/93364960/233743602-d594a535-0f45-4958-8729-c71acec06676.png)

# ☁️ Amazon Web Service

<h3>Sumário</h3>
<a href="#oquee">1. O que é a AWS?</a> <br>
<a href="#beneficios">2. Por que utilizar AWS?</a> <br>
<a href="#lambda">2. O que é o AWS Lambda?</a> 


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

<h2 id="lambda">O que é o AWS Lambda?:</h2>

O AWS Lambda é um serviço de computação que permite executar código sem o provisionamento ou gerenciamento de servidores, basta escrever o código e fazer o upload para a Lambda. Algumas características do serviço são:
- O AWS Lambda escala automaticamente as aplicações, executando código em resposta a cada acionamento. O código é executado em paralelo e processa cada acionamento individualmente, escalando precisamente de acordo com o tamanho da carga de trabalho. <br>
<i>(ex: se chegar 5 requisições ao mesmo tempo, ele vai subir 5 instâncias lambda, vai processar cada um individualmente, uma não vai saber da existência da outra e vai retornar cada um para quem solicitou)</i> <br>
- Com o AWS Lambda, você é cobrado a cada 100 ms de execução do código e pelo número de vezes que o código é acionado. Você paga apenas pelo tempo de computação consumido
- Com o AWS Lambda, você pode otimizar o tempo de execução do código escolhendo o tamanho de memória ideal para a sua função. Você também pode habilitar a Simultaneidade provisionada para manter suas funções inicializadas e prontas para responder em questão de poucos segundos.
- É pago apenas pelo tempo de computação consumida
- Basta Carregar o código e o lambda se encarrega de todos os itens necessários para executar e permitir que o código seja escalável e com alta disponibilidade

<h3>Como funciona o Lambda?</h3>
O AWS Lambda é um serviço de computação sem servidor e orientado a eventos que permite executar código para praticamente qualquer tipo de aplicação ou serviço de backend sem provisionar ou gerenciar servidores. Você pode acionar o Lambda a partir de mais de 200 serviços da AWS e aplicações de software como serviço (SaaS) e pagar apenas pelo que usar. <br> <br>

![WhatsApp Image 2023-04-23 at 13 51 50](https://user-images.githubusercontent.com/93364960/233853321-a924eb14-dbe2-4213-a939-a368c991a457.jpeg)

1. Você faz o upload do seu código para o AWS lambda ou escreve lá direto no editor da console AWS
2. Você configura seu código para ser executado a partir de outros serviços da AWS, como end-points HTTP (API Gateway) ou pode ser a partir de um arquivo ou evento do S3 
3. O Lambda executa o seu código apenas quando acionado, usando apenas os recursos de computação necessários
4. Você paga apenas pelo tempo de computação que você utilizar


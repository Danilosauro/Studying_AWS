## **Estudos para a certificação AWS Practitioner**  
___
&nbsp;

Conceitos chave do *Amazon Web Services*: 

* Pay as you go 
* Pay for what you need 

Para iniciar, é necessário dizer que a AWS é um conjunto de serviços de computação em nuvem, ou Cloud Computing, neste contexto, os conceitos acima consistem em dizer que o usuário irá pagar apenas pelo necessário e quando determinado serviço for necessário, tornando assim o uso da AWS menos dispendioso e mais justo, de acordo com a necessidade de cada companhia.  

&nbsp; 

___ 

## **Mas o que é Cloud computing ?**

Computação em nuvem ou cloud computing é a entrega de recursos de T.I sob demanda, na internet com precifiação no modelo Pay as you go. A computação em nuvem permite as companhias se preocuparem menos com a sua capacidade de hardware, servidores e manutenção de sistemas físicos, desta forma, dando foco ao desenvolvimento adequado das aplicações e ao material humano que possuem.  

&nbsp;
___

## **Principais serviços AWS - Mais comentados** -  

* EC2
* Aws Lamba 
* ECS  

___
* ## **EC2** 

O EC2 ou Elastic Cloud computing, é composto de instâncias, tais instâncias são capazes de escalonamento virtual, ou seja, a medida em que determinada necessidade surge, as instâncias podem aumentar a sua capacidade única de funcionamento ou até mesmo se multiplicarem para atender a demanda de um serviço a ser executado, isso consiste em aumento de memória disponível e ou aumento da capacidade de processamento. 

Os principais tipos de instâncias, de acordo com a necessidade são: 

* Memory optimized instances 
* Computer optimized instances 
* General purpose instances 
* Storage Optimized instances 

Todas tem como objetivo a entrega da execução dos serviços de acordo com a demanda, porém, aumentando os recursos necessários para a execução deste, seja aumento de memória, processamento, armazenamento ou todos estes aspectos unidos. 

**Pricing**

Os modelos de pagamento do EC2 podem ser dos seguintes tipos: 

* On-demand: Pago pelo uso (funcionalidade + tempo de uso) 
* Saving plans: Planos de economia de 1 a 3 anos, de acordo com o contrato do cliente. 
* Reserved instances: Plano com descontos, de acordo com o contrato do cliente. 
* Spot instances: Uso de apenas instâncias pontuais 
* Dedicated hosts: Uso de hospedagem dedicada apenas para um tipo de serviço. 


O Amazon EC2 é reconhecido pela sua capacidade de ser amplamente escalável, isto se dá por ser construído no modelo *Auto Scalling*, onde este serviço entrega sempre o necessário para cumprir as requisições em execução dentro das regras de um negócio. Além disso, o Amazon EC2 é dotado de serviços de controle de tráfego, como o *Elastic load balancing*, promovendo o fluxo adequado dentro de uma aplicação sem que esta congestione, sempre aplicando a solução mais adequada, seja a ampliação de uma função em execução ou multiplicação desta para atender uma demanda.  

___ 

## **AWS Lambda** 

O Aws Lambda se enquadra nos serviços computacionais adicionais.  

Utilizamos o AWS lambda quando necessitamos de uma função lambda que se conecte a um thrigger, este, quando ativado interage com as funções e as inicia, gerando assim a execução necessária para atender um requisito dentro das regras de negócio.  


___ 

## **AWS ECS ou EKS** 

Estes serviços são focados no uso de containers (Docker Containers ou Kubernetes), cada um destes depende do uso, caso utilizemos docker containers, optaremos pelo ECS, caso utilizemos Kubernetes containers, optaremos pelo EKS. 

___

## **Serviços de acordo com um panorama geral de uso:** 

| EC2 | AWS LAMBDA | ECS OU EKS |
|--- |--- |--- |
| hospedar aplicações tradicionais | Event driven | Containers |
| acesso completo ao S.O | Short running apps |  |
|    |    Service oriented apps | | 
|    |  No provisioning managing servers



____
## **Infraestrutura e entrega** 








# CRMAuto
Desenvolvimento projeto CRM Automotivo

# 1. Introdução 

<p align="justify">
    Cada dia que passa, a informação tem se tornado o ativo mais importante na vida de pessoas e das oficinas mecânicas. Inseridas num cenário  altamente competitivo, as oficinas mecânicas primam pelo alcance da vantagem competitiva.
</p>

<p align="justify">
    As relações entre oficinas mecânicas e seus clientes, necessitam de uma maior transparência para o aumento da confiança entre ambos. E as informações precisas,obtidas e fornecidas no momento exato são fundamentais para alcançar este objetivo.
</p>

<p align="justify">
    Diante disso, torna-se fundamental que existam ferramentas de informação e mecanismo que permitam ao usuário acessar os seus dados, serviços e produtos contratados.
</p>

<p align="justify">
    Neste contexto, surge o CRM (Custumer Relationship Management) como estratégia de negócio que representa uma solução viável para o estreitamento das relações entre clientes e oficinas.
</p>

## Problema 

<p align="justify">
    Obter o controle dos seus clientes usando planilhas e agendas é possível, contudo, as informações captadas muitas vezes ficam dispersas, desorganizadas e acabam por dificultando a tomada de decisões para promover a oficina mecânica junto ao cliente. À medida que a empresa cresce, este tipo de ferramenta improvisada vai se tornando cada vez mais um empecilho para o sucesso da empresa.
</p>
 
<p align="justify">
    Portanto, o problema que se busca resolver com este projeto é a substituição da diversificação massiva da utilização de planilhas ou sistemas internos pouco flexíveis que prejudicam o acompanhamento das oportunidades. E, portanto, o CRM é uma solução prática e eficaz.
</p>

## Objetivos

<p align="justify">
    A aplicação WEB, CRMAuto, tem como objetivo principal disponibilizar para as oficinas mecânicas todas as informações pertinentes aos clientes e os seus serviços solicitados.
</p>

<p align="justify">
    O sistema terá orientação mais voltada para os mecânicos e o setor de relacionamento com o cliente, ajudando a agilizar a emissão das propostas e fechamento das mesmas dentro da própria plataforma.
</p>

<p align="justify">
    Como objetivos específicos, podemos ressaltar:
    <ul>
        <li>
            Fornecer ao cliente acesso fácil e completo ao orçamento sobre as demandas solicitadas para o reparo do seu veículo;
        </li>
        <li>
            Permitir ao cliente que através da plataforma, ele defina quais os serviços serão realizados de acordo com a proposta da oficina;
        </li>
        <li>
            Acompanhamento em tempo real dos serviços que estão sendo realizados;
        </li>
        <li>
            Solicitar serviços extras.
        </li>
    </ul>
</p>
 
## Justificativa

<p align="justify">
    O vínculo construído entre a oficina e seus clientes é tão importante quanto a qualidade do serviço e a competitividade do preço. E boa parte do seu sucesso depende das estratégias que são utilizadas para conquistar e manter a satisfação dos clientes.
</p>

<p align="justify">
    Imagine que, atualmente, há uma infinidade de empresas onde eles podem buscar os produtos e serviços pelos quais se interessam. Encontrá-las está à distância de um clique. É possível pedir recomendações ou pesquisar diversos negócios na internet rapidamente. Além disso, também é possível acessar o mundo online para fazer elogios e reclamações, impulsionando ou atrapalhando os resultados do empreendimento.
</p>
 
<p align="justify">
    Diante de todas essas particularidades, os donos de empresas têm se preocupado cada vez mais em garantir a satisfação do consumidor. Afinal, um problema não resolvido pode não apenas acarretar a perda de um cliente, mas provocar um marketing negativo sobre a imagem que o negócio vem construindo.
</p>

<p align="justify">
    Nesse sentido, podemos dizer que a excelência no atendimento ao cliente na oficina mecânica está despontando como um dos diferenciais competitivos mais centrais para um empreendedor. E a tendência é que isso se aprofunde cada vez mais nos próximos anos.
</p>
 
## Público alvo

<p align="justify">
    Estabelecemos que o público alvo são as oficinas mecânica automotivas que desejam ter uma plataforma que lhes permitam estarem sempre atualizados em relação aos serviços contratados pelos seus clientes, além de ser um canal que sane as principais dúvidas, os direcionando de forma correta na tomada de decisões.
</p>

<p align="justify">
    Esta ferramenta permitirá o aprimoramento no atendimento ao cliente. Ela ajudará os mecânicos e gerentes comerciais a atingirem todo o seu potencial com mais produtividade e aproveitando seu tempo da melhor forma.
</p>

# 2. Especificação do projeto

## 2.2 Histórias de Usuários

<p align="justify">A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários.</p>

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`                                                                       |PARA ... `MOTIVO/VALOR`                                                                        |
|--------------------|----------------------------------------------------------------------------------------------------------|-----------------------------------------------|
|Gestor da oficina |Efetuar o cadastro, alteração e exclusão de oficinas no sistema |Que a gestão da oficina matriz e das oficinas filiais seja realizada de forma centralizada em um único sistema|
|Gestor da oficina | Efetuar o cadastro, alteração e exclusão de funcionários no sistema |Conseguir realizar a gestão dos meus funcionários de maneira facilitada|
|Gestor da oficina | Efetuar o cadastro, alteração e exclusão dos serviços disponibilizados pela oficina |Que seja possível incluir, alterar e excluir informações de um determinado serviço|
|Gestor da oficina| Gerar relatórios sobre os serviços realizados pela oficina| Obter informações relevantes da minha empresa|
|Gestor da oficina| Gerar relatórios sobre os clientes da oficina | Obter informações relevantes dos meus clientes|
|Gestor da oficina / Funcionário da oficina| Efetuar o cadastro, alteração e exclusão de clientes no sistema| Que seja possível incluir e alterar informações de um determinado cliente|
|Gestor da oficina / Funcionário da oficina| Consultar os clientes cadastrados no sistema| Conseguir realizar a gestão dos clientes de maneira otimizada|      
|Funcionário da oficina |Realizar o cadastro de veículo (s) para um determinado cliente no sistema| Conseguir realizar a inclusão dos serviços solicitados para o veículo|
|Funcionário da oficina| Inserir, alterar e excluir informações sobre o andamento de um determinado serviço no sistema| Que o registro dessas informações esteja sempre atualizado|
|Cliente da oficina| Acompanhar o andamento do serviço solicitado à oficina e a data prevista para finalização| Que eu tenha informações relevantes sobre a evolução do serviço contratado|
|Cliente da oficina| Visualizar o histórico de serviços efetuados/concluídos no (s) meu (s) veículo (s) nos últimos X anos| Que eu consiga consultar os registros de forma fácil e centralizada em um único sistema|  
|Cliente da oficina| Visualizar no detalhamento do serviço informações como: peças trocadas, serviços efetuados, mecânico responsável e valores das peças e serviços |Que eu consiga consultar informações relevantes sobre os serviços que foram efetuados no (s) meu (s) veículo (s)|
|Cliente da oficina |Receber lembretes automáticos sobre revisões e serviços recomendados para o (s) meu (s) veículo (s) |Que eu seja lembrado de realizar serviços importantes para a correta manutenção do (s) meu (s) veículo (s)|

## Requisitos Funcionais

A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues:

O site deve apresentar na página principal notícias dinâmicas
obtidas por meio de canais de notícias da Internet (API)

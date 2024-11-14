# Descrever o software como serviço

O **SaaS (software como serviço)** é o modelo de serviço de nuvem mais completo do ponto de vista do produto.

Com o **SaaS**, você está essencialmente alugando ou usando um aplicativo totalmente desenvolvido. Email, software financeiro, aplicativos de mensagens e software de conectividade são exemplos comuns de uma implementação de **SaaS**.

Embora o modelo de **SaaS** possa ser o menos flexível, ele também é o mais fácil de colocar em funcionamento. Ele requer a menor quantidade de conhecimento técnico ou experiência para o emprego total.

<br>

## Modelo de responsabilidade compartilhada

O **modelo de responsabilidade compartilhada** se aplica a todos os tipos de serviço de nuvem. O **SaaS** é o modelo que coloca a maior responsabilidade sobre o provedor de nuvem e a menor responsabilidade com o usuário.

Em um ambiente de **SaaS**, você é responsável pelos dados que coloca no sistema, pelos dispositivos que permite que se conectem ao sistema e pelos usuários que têm acesso. Quase todo o resto é responsabilidade do provedor de nuvem.

O provedor de nuvem é responsável pela segurança física dos datacenters, pela energia, pela conectividade de rede e pelo desenvolvimento e aplicação de patch dos aplicativos.

<br>

<table>
    <thead>
        <tr>
            <th></th>
            <th style='text-align:center; vertical-align:middle'>Responsability</th>
            <th style='text-align:center; vertical-align:middle'>SaaS</th>
            <th style='text-align:center; vertical-align:middle'>PaaS</th>
            <th style='text-align:center; vertical-align:middle'>IaaS</th>
            <th style='text-align:center; vertical-align:middle'>On-premise</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=3 style='text-align:center; vertical-align:middle'>Responsability always <br> retained by the customer</td>
            <td>Information and data</td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
        </tr>
        <tr>
            <td>Devices (Mobiles and PCs)</td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
        </tr>
        <tr>
            <td>Acounts and Identities</td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
        </tr>
        <tr>
            <td rowspan=4 style='text-align:center; vertical-align:middle'>Responsability <br> varies by type</td>
            <td>Identities and directory infrastructure</td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100; &#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100; &#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>            
        </tr>
        <tr>
            <td>Applications</td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100; &#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>                        
        </tr>
        <tr>
            <td>Network controls</td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100; &#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>                        
        </tr>
        <tr>
            <td>Operation system</td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>                        
        </tr>
        <tr>
            <td rowspan=3 style='text-align:center; vertical-align:middle'>Responsability transfers <br> to cloud provider</td>
            <td>Physical hosts</td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>            
        </tr>
        <tr>
            <td>Physical network</td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>                        
        </tr>
        <tr>
            <td>Physical datacenter</td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#9729;&#65039;</p></td>
            <td style='text-align:center; vertical-align:middle'><p>&#128100;</p></td>                        
        </tr>             
    </tbody>
</table>

<br>

- :bust_in_silhouette: => Costumer
- :cloud: => Microsoft

<br>

## Cenários

Alguns cenários comuns de **SaaS** são:

- Email e mensagens.
- Aplicativos de produtividade empresarial.
- Controle de finanças e despesas.
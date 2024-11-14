# Descrever a infraestrutura como serviço

O **IaaS (infraestrutura como serviço)** é a categoria mais flexível de serviços de nuvem, pois oferece o máximo de controle sobre os recursos de nuvem. 

Em um modelo de **IaaS**, o provedor de nuvem é responsável por:

- Manter o hardware
- Manter a conectividade de rede (com a Internet)
- Manter a segurança física

<br>

Você é responsável por todo o resto: instalação, configuração e manutenção do sistema operacional; configuração de rede; configuração de banco de dados e armazenamento e assim por diante.

<br>

Com o **IaaS**, basicamente o hardware é alugado em um datacenter de nuvem, mas cabe a você decidir o que fazer com ele.

<br>

## Modelo de responsabilidade compartilhada

O **modelo de responsabilidade compartilhada** se aplica a todos os tipos de serviço de nuvem. No IaaS, a maior parte da responsabilidade fica com você.

O provedor de nuvem é responsável por manter a infraestrutura física e o acesso à Internet. Você é responsável por: instalação e configuração, aplicação de patch, atualizações e segurança.

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

Alguns cenários comuns em que o **IaaS** faz sentido incluem:

- **Migração lift-and-shift**: Você está configurando recursos de nuvem semelhantes aos do datacenter local e apenas migra os elementos em execução local para execução na infraestrutura **IaaS**.

- **Teste e desenvolvimento**: você estabeleceu configurações para ambientes de desenvolvimento e teste que precisa replicar rapidamente. Você pode inicializar ou desativar os diferentes ambientes rapidamente com uma estrutura de **IaaS**, mantendo o controle completo.

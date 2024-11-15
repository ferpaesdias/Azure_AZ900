# Descrever a plataforma como serviço

O **PaaS (Plataforma como serviço)** é um meio termo entre alugar espaço em um datacenter (infraestrutura como serviço) e pagar uma solução completa e implantada (software como serviço).

Em um ambiente de **PaaS**, o provedor de nuvem mantém a infraestrutura física, a segurança física e a conexão com a Internet.

Ele também mantém os sistemas operacionais, o middleware, as ferramentas de desenvolvimento e os serviços de business intelligence que compõem uma solução de nuvem. Em um cenário de **PaaS**, você não precisa se preocupar com o licenciamento nem com a aplicação de patch em sistemas operacionais e bancos de dados.

O **PaaS** é adequado para fornecer um ambiente de desenvolvimento completo sem a preocupação de manter toda a infraestrutura de desenvolvimento.

<br>

## Modelo de responsabilidade compartilhada

O modelo de responsabilidade compartilhada se aplica a todos os tipos de serviço de nuvem. O **PaaS** divide a responsabilidade entre você e o provedor de nuvem.

O provedor de nuvem é responsável por manter a infraestrutura física e o acesso à Internet, como no IaaS. No modelo de **PaaS**, o provedor de nuvem também mantém os sistemas operacionais, os bancos de dados e as ferramentas de desenvolvimento. Pense no **PaaS** como o uso de um computador conectado ao domínio: o departamento de TI mantém o dispositivo com atualizações, patches e renovações regulares.

Dependendo da configuração, você ou o provedor de nuvem pode ser responsável pelas configurações de rede e a conectividade no ambiente de nuvem, a segurança da rede e do aplicativo e a infraestrutura de diretório.

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

Alguns cenários comuns em que o **PaaS** faz sentido incluem:

- **Estrutura de desenvolvimento**: O **PaaS** fornece uma estrutura que os desenvolvedores podem usar como base para desenvolver ou personalizar aplicativos baseados em nuvem. Semelhante à forma como você cria uma macro do Excel, o **PaaS** permite aos desenvolvedores criar aplicativos usando componentes de software internos. São incluídos recursos de nuvem, como escalabilidade, alta disponibilidade e a funcionalidade de multi-tenant, reduzindo a quantidade de codificação que os desenvolvedores precisam realizar.

- **Análise ou business intelligence**: as ferramentas fornecidas como serviço com o **PaaS** permitem que as organizações analisem e minerem dados, encontrando insights e padrões e prevendo resultados para aprimorar a previsão, as decisões de design de produto, o retornos sobre investimentos e outras decisões de negócios.
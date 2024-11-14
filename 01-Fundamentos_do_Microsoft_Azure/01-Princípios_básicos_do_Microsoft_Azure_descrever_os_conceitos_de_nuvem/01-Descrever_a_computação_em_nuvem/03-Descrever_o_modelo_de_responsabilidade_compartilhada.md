# Descrever o modelo de responsabilidade compartilhada

Em um **datacenter corporativo tradicional**, a empresa é responsável por manter o espaço físico, garantir a segurança e manter ou substituir os servidores se algo acontecer. O departamento de TI é responsável por manter toda a infraestrutura e o software necessários para manter o datacenter em funcionamento. É provável que eles também sejam responsáveis por manter todos os sistemas corrigidos e na versão correta.

Com o modelo de **responsabilidade compartilhada**, essas responsabilidades são compartilhadas entre o provedor de nuvem e o consumidor. Segurança física, energia, resfriamento e conectividade de rede são responsabilidade do provedor de nuvem. O consumidor não fica na mesma localização do datacenter, portanto, não faria sentido que o consumidor tivesse algumas dessas responsabilidades.

Ao mesmo tempo, o consumidor é responsável pelos dados e pelas informações armazenados na nuvem. O consumidor também é responsável pela segurança de acesso, o que significa que você só dá acesso àqueles que precisam.

<br>

O modelo de **responsabilidade compartilhada** está fortemente vinculado aos tipos de serviço de nuvem:

- IaaS (infraestrutura como serviço)
- PaaS (plataforma como serviço)
- SaaS (software como serviço)

<br>

A **IaaS** coloca a maior responsabilidade sobre o consumidor, com o provedor de nuvem sendo responsável pelas questões básicas de segurança física, energia e conectividade. Na outra ponta do espectro, o **SaaS** coloca a maior parte da responsabilidade no provedor de nuvem. A **PaaS**, sendo um meio termo entre IaaS e SaaS, situa-se no meio desses dois cenários e distribui uniformemente a responsabilidade entre o provedor de nuvem e o consumidor.

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

Ao usar um provedor de nuvem, o cliente sempre será responsável por:

- Informações e dados armazenados na nuvem
- Dispositivos que têm permissão para se conectar à nuvem 
- Contas e identidades das pessoas, serviços e dispositivos em sua organização

<br>

O provedor de nuvem é sempre responsável por:

- Datacenter físico
- Rede física
- Hosts físicos

<br>

Seu modelo de serviço determinará a responsabilidade por coisas como:

- Sistemas operacionais
- Controles de rede
- Aplicativos
- Identidade e infraestrutura
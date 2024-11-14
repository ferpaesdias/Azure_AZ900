# Descrever os benefícios da alta disponibilidade e da escalabilidade na nuvem

<br>

## Alta disponibilidade

A **alta disponibilidade** se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.

Ao arquitetar sua solução, você precisará considerar as garantias de disponibilidade do serviço. O Azure é um ambiente de nuvem altamente disponível com garantias de tempo de atividade, dependendo do serviço. Essas garantias fazem parte dos **SLAs** (Contratos de Nível de Serviço).

<br>

## Escalabilidade

A **escalabilidade** refere-se à capacidade de ajustar recursos para atender à demanda. Se você experimentar um pico repentino de tráfego e seus sistemas ficarem sobrecarregados, a capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.

O outro benefício da **escalabilidade** é que você não está pagando além do necessário pelos serviços. Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa. Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.

A escala geralmente vem em duas variedades:

- **vertical**: A escala vertical se concentra em aumentar ou diminuir a capacidade dos recursos.
- **horizontal**: A escala horizontal é adição ou subtração do número de recursos.

<br>

## Dimensionamento vertical

Com a *escala vertical*, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual. Por outro lado, se você percebesse que superestimou as necessidades, poderia reduzir verticalmente, diminuindo as especificações de CPU ou RAM.

<br>

## Dimensionamento horizontal

Com a *escala horizontal*, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente). Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão. Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).

## Resumo lab introdução ao Azure
### Módulo 1
No laboratório de introdução à computação em nuvem e ao Azure da DIO, aprendi sobre os seguintes tópicos:
- Todas as ferramentas que existem disponíveis no Azure (armazenamento, banco de dados, etc)
- Modelos de nuvens: Nuvens privadas, públicas e híbridas
- CapEx e OpEx (tipos de pagamentos):
  - O CapEx é para capital, que seria a infraestrutura para máquinas. E seu custo diminui com o tempo
  - O OpEx é o valor de operações, como uma mensalidade dos recursos da nuvem utilizados.
<br>

### Módulo 2
No módulo 2, titulado "Benefícios da Nuvem: Escalabilidade e Elasticidade", aprendi sobre os seguintes assuntos:
- Alta disponibilidade -> tempo que um serviço estará disponível para uso. Esse tempo é medido em porcentagem, como 99%, 99,99% ou 99,95%. Isso, e muito mais é definido no SLA (Service Level Agreement) do cloud provider.
- Escalabilidade -> capacidade de ajustar recursos para atender à demanda. Quando a demanda abaixa, diminui recursos, quando aumenta, acrescenta recursos.
  - Vertical -> se um aplicativo precisa de mais processamento, é possível *escalar verticalmente* para adicionar mais CPUs ou RAM à máquina virtual.
- Elasticidade -> se houvesse um salto repentino na demanda, os recursos poderiam ser expandidos (automaticamente ou manualmente).
  - É possível adicionar VMs ou contêineres por meio da expansão. E se houver uma queda na demanda, os recursos podem ser reduzidos horizontalmente (automaticamente ou manualmente).
- Confiabilidade -> a nuvem tem design descentralizado, então naturalmente dá suporte a uma infraestrutura confiável. Também permite que tenha recursos implantador em diferentes regiões do mundo.
- Previsibilidade -> permite avançar com confiança, seja no desempenho ou no custo.
- Segurança -> a nuvem oferece ferramentas de segurança, mas a implementação de grande parte delas precisam ser feitas pelo cliente.
  - Se desejar que a aplicação de patches e manutenção sejam tratadas automaticamente, as implantações de PaaS ou SaaS podem ser as melhores estratégias de nuvem.
- Governança -> auditoria baseada em nuvem que ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação.
  - Dependendo do modelo, patches de software e atualizações também podem ser aplicados automaticamente, ajudando na governança e na segurança.
  - Estabelecendo uma presença de governança o mais cedo possível, permite manter a presença de nuvem atualizada, protegida e bem gerenciada.
- Gerenciabilidade -> um dos principais benefícios: opções de capacidade de gerenciamento. 
  - O gerenciamento da nuvem tem como exemplo: escalar automaticamente a implantação de recursos com base na necessidade.
  - Implantar recursos cmo base num modelo pré-configurado, removendo a necessidade de configuração manual.

<br>

Tabela de indisponibilidade em porcentagem SLA (Azure):
|SLA|Inatividade por semana|Inatividade por mês|Inatividade por ano|
|---|---|---|---|
|99%|1,68 hora|7,2 horas|3,65 dias|
|99,9%|10,1 minutos|43,2 minutos|8,76 horas|
|99,95%|5 minutos|21,6 minutos|4,38 horas|
|99,99%|1,01 minuto|4,32 minutos|52,56 minutos|
|99,999%|6 segundos|25,9 segundos|5,26 minutos|

Caso o tempo de indisponibilidade no período seja maior do que o definido, é permitido pedir ressarcimento.

<br>

### Módulo 3
Módulo sobre tipos de serviço de nuvem na Azure: IaaS, PaaS e SaaS.  
- IaaS (Infraestrutura como Serviço) -> servidores e armazenamentos; firewalls/segurança de rede; planta física/edifício do datacenter. 
  - O modelo mais personalizável, pois pode gerir quase tudo: SO da máquina virtual, configurações de rede, segurança etc, já que é apenas uma infraestrutura que vem do provedor.
- PaaS (Plataforma como serviço)-> engloba o IaaS, sistemas operacionais e ferramentas para desenvolvedores, análise de negócios de gerenciamento de database. Não se envolve com a infraestrutura, apenas a aplicação disponibilizada.
  - Como exemplo a configuração de um banco de dados: nome do servidor, localização, como vai ser autenticado.
- SaaS (Software como Serviço) -> aplicativos e apps hospedados. Microsoft Teams. Esse é o nível mais "alto": quanto mais o nível sobe, menos os administradores precisam configurar coisas. Os usuários pagam pelo software que utilizam em um modelo de assinatura.
- Modelo de responsabilidade compartilhada -> na Azure, existe esse modelo, que define como se divide a responsabilidade entre o cliente e a Microsoft.  

Na tabela abaixo, o "No local" é um modelo on-premise, onde toda responsabilidade é do cliente. Conforme vai indo para a esquerda, a responsabilidade vai caindo mais para o provedor.  
Há responsabilidades completamentes do cliente (as 3 de cima) e as apenas do provedor (as 3 de baixo, excluindo o on-premise).

![Tabela de modelo de responsabilidade compartilhada](images/modelo-responsabilidade-compartilhada.png)

---

<br>

*Nota: Estarei atualizando este repositório com o conhecimento adicional que eu adquirir ao longo do curso de Azure!*

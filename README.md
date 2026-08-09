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
- Alta disponibilidade -> tempo que um serviço estará disponível para uso. Esse tempo é medido em porcentagem, como 99%, 99,99% ou 99,95%. Isso, e muito mais é definido no SLA do cloud provider.
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

---

<br>

*Nota: Estarei atualizando este repositório com o conhecimento adicional que eu adquirir ao longo do curso de Azure!*

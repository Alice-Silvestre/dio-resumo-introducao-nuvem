# dio-resumo-introducao-nuvem
Resumo do curso de introdução a computação em nuvem, usando Microsoft Azure. 

## O que é computação em Nuvem? 
Computação em nuvem é o fornecimento, por meio da internet, de serviços de computação como servidores, bancos de dados, redes e etc. Esses serviços são ofertados por provedores de nuvem, como Microsoft Azure, Google Cloud Platform (GCP) e Amazon Web Services (AWS). 

### Nuvem Privada
São ambientes em nuvem criados por organizações em seu Datacenter que somente os usuários de dentro da organização tem acesso, nesse modelo as organizações são responsáveis por operar os serviços que fornecem e realizar manutenção e atualização de hardware. O modelo de nuvem privada permite que as organizações mantenham controle total sobre recursos e segurança. 

### Nuvem Pública
São serviços oferecidos por um provedor de nuvem por meio da internet, onde se paga somente o que é utilizado. 

### Nuvem Híbrida
É a combinação do uso das nuvens pública e privada. 

### Nuvem Multi-Cloud
É o uso de múltiplos serviços de nuvem de diferentes provedores. 

## Modelo Baseado em Consumo
Os provedores de serviços em nuvem operam em um modelo baseado em consumo e permitem que os usuários utilizem recursos de computação sob demanda, sem a necessidade de investir em infraestrutura física. Isso traz uma série de benefícios, como: 
- Escalabilidade: capacidade de aumentar ou diminuir recursos de acordo com a demanda.
- Economia: por não haver custos com aquisição de hardware, manutenção e energia há significativa redução de custos.
- Acessibilidade: os resursos e dados podem ser acessados de qualquer lugar via internet.
- Segurança: os provedores de nuvem oferecem medidas avançadas de segurança para proteger dados e aplicações.

## Benefícios da computação em nuvem
- Alta Disponibilidade: refere-se a garantia de disponibilidade dos serviços, independentemente de interrupções ou eventos que possam ocorrer, por meio de SLA (Service Level Agreement - Acordo de Nível de Serviço) o provedor fornece um contrato com determinado nível de resiliência/disponibilidade. 
- Escalabilidade: capacidade de adicionar/ajustar recursos para atender à demanda, exemplo: em caso de necessidade de aumentar a capassidade de processamento pode-se adicionar mais CPUs ou RAM à máquina virtual.
- Elasticidade: está ligada a escalabilidade, permite dimensionar o ambiente em nuvem baseado em requisições, por exemplo, caso haja um aumento repentino na demanda, os recursos implantados podem ser expandidos (esse processo pode ser feito automaticamente ou manualmente) ou em caso de queda significativa na demanda os recursos podem ser reduzidos.
- Confiabilidade: Devido ao design descentralizado a nuvem dá suporte a uma infraestrutura confiável e resiliente e permite ter recursos implantados em diversas localidades do mundo.
- Previsibilidade: o ambiente em nuvem permite avançar com confiança em relação ao custo ou desempenho por ambos estarem infuenciados pelo [Microsoft Well Architecture Framework](https://learn.microsoft.com/en-us/azure/well-architected/what-is-well-architected-framework).
- Segurança: A nuvem ofere ferramentas e recursos de segurança que atendem às necessidades dos clientes, porém a implementação de muitas dessas ferramentas/recursos devem ser realizadas pelos clientes.
- Governança: a auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com padrões coorporativos e fornece estratégias de mitigação.
- Gerenciabilidade: trata-se da maneira de gerenciar o ambiente em nuvem e seus recursos, por exemplo, implantar recursos com um modelo pré-configurado, removendo a necessidade de configuração manual ou escalar automaticamente a implantação de recursos com base na necessidade. O gerenciamento pode ser realizado de diferentes maneiras, por meio de um portal da web, usando interface de linha de comando, usando APIs ou usando PowerShell.

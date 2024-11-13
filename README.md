# Resumo das Aulas

Este repositório contém um resumo dos principais aprendizados obtidos durante o desenvolvimento dos laboratórios na Digital Innovation One (DIO) com foco em Microsoft Azure.

## Microsoft Azure - Localizando Serviços por Categoria

Nesta aula, foram abordadas as ferramentas para personalização e organização do Portal do Azure, além de uma introdução a recursos de segurança e armazenamento. Aprendi a:

* **Personalizar o Portal:** Alterando o idioma e o tema visual para melhorar a experiência.
* **Organizar Recursos:** Agrupando serviços por categoria para facilitar a navegação e o gerenciamento.
* **Explorar a Rede Azure:** Conhecendo Bastions (Jump Servers) e Firewalls, fundamentais para garantir segurança.
* **Estudar Opções de Armazenamento:** Entendendo como migrar dados e considerando as limitações de recursos em Versão Prévia.
* **Visualizar a Localização dos Serviços:** Um laboratório prático forneceu uma visão geográfica dos serviços disponíveis no Azure.

### Observações
  * **Versão Prévia:** Recursos nessa fase estão em desenvolvimento e podem não ser recomendados para ambientes de produção.
  * **Bastions:** Bastions atuam como Jump Servers, permitindo acesso seguro aos recursos na nuvem.

## Microsoft Azure - Criando Máquinas Virtuais na Azure

Esta aula focou nos diferentes níveis de SLA (Service Level Agreement) e como eles impactam o tempo de inatividade de um serviço, permitindo entender a relação entre a disponibilidade contratada e o tempo de indisponibilidade esperado.

| Nível de SLA | Tempo de Inatividade por Semana | Tempo de Inatividade por Mês | Tempo de Inatividade por Ano |
|---|---|---|---|
| 99% | 1,68 horas (2h 8min) | 7,2 horas | 3,65 dias |
| 99,9% | 10,1 minutos | 43,2 minutos | 8,76 horas |
| 99,95% | 5 minutos | 21,6 minutos | 4,38 horas |
| 99,99% | 1,01 minuto | 4,32 minutos | 52,56 minutos |
| 99,999% | 6 segundos | 25,9 segundos | 5,26 minutos |

### Análise
* **SLA e Disponibilidade:** Quanto mais “9s” no SLA, menor o tempo de inatividade esperado.
* **Impacto no Custo:** Níveis de SLA mais elevados tendem a aumentar os custos.
* **Escolha do SLA:** Ao escolher o SLA, é importante avaliar a tolerância a falhas do seu sistema e os impactos financeiros da indisponibilidade.

## Microsoft Azure - Modelos de Nuvem

Esta aula aprofundou os três principais modelos de computação em nuvem: IaaS, PaaS e SaaS, cada um com diferentes níveis de gerenciamento e flexibilidade, permitindo que empresas escolham a solução mais adequada às suas necessidades.

### IaaS (Infraestrutura como Serviço)
* Fornece infraestrutura de TI sob demanda, como servidores, armazenamento e redes virtuais.
* O cliente gerencia o sistema operacional, aplicativos e dados.
* Proporciona flexibilidade e controle total do ambiente.

### PaaS (Plataforma como Serviço)
* Oferece um ambiente de desenvolvimento com ferramentas e bancos de dados prontos.
* O cliente foca no desenvolvimento e conteúdo do aplicativo, sem se preocupar com a infraestrutura.
* Reduz a complexidade da gestão e acelera o desenvolvimento.

### SaaS (Software como Serviço)
* Disponibiliza aplicativos completos e acessíveis via navegador.
* O cliente gerencia apenas os dados e configurações do aplicativo.
* Oferece facilidade de uso e rápida implantação.

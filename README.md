# Thiago Azenha

Pesquisa e desenvolvimento em Análise de Sistemas, com ênfase em administração de infraestrutura Linux, redes operacionais e engenharia de software para a web. A trajetória de formação articula os fundamentos computacionais desenvolvidos no Centro Universitário IESB à bagagem analítica originária das Ciências Sociais (Antropologia / Universidade de Brasília - UnB), orientando a prática técnica por critérios de rigor estrutural, documentação sistemática e clareza de escopo.

```
+-------------------------------------------------------------------------+
| SISTEMAS & INFRAESTRUTURA                                               |
| Host: engine.lat | Linux KVM | Docker | Nginx | MySQL 8.0               |
+-------------------------------------------------------------------------+
| ENGENHARIA DE SOFTWARE                                                  |
| TypeScript | Node.js / Express | Fastify | Python | React Native (Expo) |
+-------------------------------------------------------------------------+
| SEGURANÇA & REDES                                                       |
| SSH Keypair Auth | OpenVPN Tunneling | Reverse Proxy | Systemd Services |
+-------------------------------------------------------------------------+
```

## Linhas de Atuação

A atuação divide-se em três eixos complementares:

1. **Administração de Sistemas e Servidores Linux:** Configuração, particionamento e manutenção de instâncias remotas sob virtualização KVM, estabelecendo rotinas de automação com `systemd`, isolamento de processos mediante contêineres Docker e tunelamento seguro via OpenVPN.
2. **Engenharia de Software e Modelagem de Domínio:** Construção de aplicações sustentadas em tipagem estrita, arquiteturas modulares (Hexagonal e DDD) e suítes de testes orientadas a comportamento (TDD com Vitest e Jest).
3. **Gestão de Dados e Engenharia de ETL:** Estruturação de esquemas relacionais no MySQL, elaboração de rotinas de sanitização de grandes volumes de catálogos industriais e integração entre camadas de persistência e serviços em nuvem (GCP).

## Projetos em Destaque

### [SOIL • Especificação Técnica Automotiva & Orçamentos B2B](https://github.com/sagihtt/soil)
Plataforma multi-tenant voltada à padronização de especificações técnicas veiculares e formação de propostas comerciais para oficinas e centros automotivos.
* **Arquitetura:** Clean Architecture (Hexagonal) com separação rígida entre entidades de domínio, casos de uso e adaptadores de infraestrutura em TypeScript estrito.
* **Volume e Dados:** Pipeline de extração e tratamento de dados (ETL em Python) cobrindo 65 montadoras e 3.856 veículos da frota nacional, com persistência relacional no MySQL 8.0.
* **Garantia de Qualidade:** Suíte com 40 testes unitários e de integração de ponta a ponta desenvolvidos sob o ciclo TDD (Vitest), com taxa nula de falhas em tempo de compilação.

### [Engine • Infraestrutura Operacional e Serviços](https://github.com/sagihtt/engine)
Ambiente de gerenciamento remoto, orquestração e barramento de serviços implantado no domínio `engine.lat`.
* **Ambiente Operacional:** Servidor Linux dedicado com monitoramento de processos via PM2, proxy reverso Nginx e controle de acesso baseado estritamente em pares de chaves SSH.
* **Integração Contínua:** Serviços autônomos (`engine-autopull.service` e `engine-autopush.service`) para sincronização segura e espelhamento entre o repositório remoto e a infraestrutura em produção.

### Krono • Gestão de Frequência e Ponto Eletrônico
Aplicação mobile e web para registro de jornada corporativa com suporte a regras de conformidade trabalhista.
* **Interface e Plataforma:** Interface adaptativa desenvolvida em React Native e Expo SDK 58, combinando navegação modular, controle de estado local e responsividade entre dispositivos móveis e navegadores.
* **Recursos Nativos:** Autenticação biométrica local (`expo-local-authentication`), geolocalização com verificação de raio de atuação (`expo-location`), captura documental fotográfica e geração de relatórios de auditoria.

## Matriz Técnica

| Domínio | Ferramentas e Tecnologias |
| :--- | :--- |
| **Sistemas Operacionais** | Linux (Ubuntu Server, Debian), KVM, Bash, Shell Scripting, Powershell |
| **Infraestrutura & Redes** | Docker, Docker Compose, Nginx, OpenVPN, SSH, Systemd, GCP |
| **Desenvolvimento Backend** | Node.js, TypeScript, Express, Fastify, Python, REST APIs, OpenAPI |
| **Desenvolvimento Frontend & Mobile** | React, React Native, Expo SDK, HTML5, CSS3 Moderno, JavaScript ES6+ |
| **Persistência de Dados** | MySQL, Modelagem Relacional, Migrations SQL, Scripts ETL |
| **Metodologias & Controle** | Git, GitHub, TDD, Clean Architecture, Domain-Driven Design (DDD) |

## Formação Acadêmica

* **Análise e Desenvolvimento de Sistemas** | Centro Universitário IESB (3º semestre)
* **Ciências Sociais / Antropologia** | Universidade de Brasília - UnB (Período: 2017 - 2021, trancado)

## Contato e Referências

* **Domínio Pessoal / Servidor:** [engine.lat](https://engine.lat)
* **Correio Eletrônico:** [t.aazenha@gmail.com](mailto:t.aazenha@gmail.com)
* **Localidade:** Brasília, Distrito Federal - Brasil

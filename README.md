# Joadson Silva

**Engenharia de Infraestrutura Cloud | GCP & AWS**

Meu foco técnico é infraestrutura em Google Cloud Platform e AWS, com ênfase em arquitetura de nuvem, redes, segurança, governança, confiabilidade, FinOps e Infraestrutura como Código (IaC).

Estou construindo um portfólio de estudos de caso de infraestrutura que conectam requisitos de negócio a decisões de arquitetura, implementação e evidências de validação. Os cenários e as empresas são fictícios, sem dados ou artefatos de empregadores e clientes.

[Explore meu portfólio de infraestrutura cloud](https://github.com/Joads0n/cloud-infrastructure-portfolio).

## Case em destaque: Landing Zone no GCP

Uma base de infraestrutura no nível de um projeto, provisionada com Terraform para hospedar uma aplicação simples em VMs. O cenário inclui:

- Criação do projeto, vínculo com faturamento, labels e ativação de APIs.
- VPC, sub-rede, regras de firewall, Cloud NAT e endereços IP reservados.
- Load Balancer de aplicação externo global, duas réplicas Nginx em VMs sem IP público e em zonas distintas, com expansão manual para três réplicas.
- Conta de serviço da aplicação, OS Login, Ops Agent e política de snapshots.
- Parâmetros organizados por responsabilidade, documentação de implantação e limpeza, testes Terraform com provedores simulados e testes Python.

A implementação e os testes locais estão disponíveis. O registro de evidências separa os resultados locais das sessões anteriores no GCP; a revisão atual, simplificada para usar estado local, ainda requer uma nova validação ponta a ponta na nuvem.

[Conheça o case](https://github.com/Joads0n/cloud-infrastructure-portfolio/tree/5829802063f2611e2e271418a881ef394a3cc033/gcp-enterprise-landing-zone) · [Testes e resultados esperados](https://github.com/Joads0n/cloud-infrastructure-portfolio/blob/5829802063f2611e2e271418a881ef394a3cc033/gcp-enterprise-landing-zone/tests/README.md) · [Evidências e limites da validação](https://github.com/Joads0n/cloud-infrastructure-portfolio/blob/5829802063f2611e2e271418a881ef394a3cc033/gcp-enterprise-landing-zone/docs/single-project-validation.md)

## Próximas frentes

O catálogo também prevê cases de fundação organizacional no GCP, engenharia de IaC, redes, segurança, governança, FinOps, conectividade híbrida, recuperação de desastres e migração de cargas de trabalho. Essas frentes permanecem planejadas, com escopos separados da Landing Zone.

## Como abordo engenharia

- Explicitar requisitos, restrições, alternativas e os impactos de cada decisão.
- Aplicar controles de segurança, confiabilidade, governança e custos adequados ao cenário.
- Usar Terraform para tornar o provisionamento reproduzível e os parâmetros compreensíveis.
- Documentar testes, resultados esperados, limitações e procedimentos de limpeza.
- Distinguir propostas, verificações locais e resultados observados na nuvem.

## Contato

[LinkedIn](https://www.linkedin.com/in/joadson-costa-6bb5641a4) · [E-mail](mailto:joadson83@gmail.com)

# Arquitetura da Solução

A arquitetura foi projetada seguindo os princípios do AWS Well-Architected Framework, priorizando:

- Alta disponibilidade
- Escalabilidade automática
- Segurança
- Otimização de custos

## Componentes
- Amazon VPC
- Sub-rede pública para camada web
- Sub-rede privada para banco de dados
- EC2 Auto Scaling
- Amazon RDS
- Amazon S3

A separação por camadas garante isolamento, segurança e facilidade de manutenção.

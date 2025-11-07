# 🏍️ GPSMottu - Compliance, Quality Assurance and Tests

## 📘 Visão Geral do Projeto

O GPSMottu - Gestão de Motos é uma aplicação desenvolvida com foco em auxiliar operadores e gestores de filiais no controle e monitoramento de motos, funcionários e setores da empresa.

O sistema foi projetado para oferecer gestão eficiente e rastreabilidade total da frota, permitindo que as empresas tenham visibilidade completa sobre a localização e o status de suas motos em tempo real.

## 🔧 Funcionalidades Principais

Gestão de motos: cadastro, atualização de status e rastreamento em diferentes filiais.

Controle via QR Code: associação de motos a QR Codes, permitindo rápida identificação e verificação no momento de entrada, saída ou movimentação.

Mapeamento de setores e filiais: estruturação de áreas internas da empresa para facilitar a localização e organização.

Gestão de funcionários: registro de colaboradores vinculados a cada filial, integrando informações relevantes para a operação.

## 🎯 Benefícios para o Negócio

Com essas funcionalidades, o sistema GPSMottu contribui diretamente para os seguintes objetivos estratégicos:

Redução de perdas e prejuízos: evita que motos sejam extraviadas ou deixem de ser monitoradas.

Melhor comunicação interna: facilita a troca de informações entre operadores, gestores e filiais.

Maior rastreabilidade: garante que cada moto esteja sempre associada a uma filial, setor e responsável.

## 👥 Equipe
| Nome                              | RM       | Turma  |
|-----------------------------------|-----------|---------|
| Gustavo Dias da Silva Cruz        | RM556448  | 2TDSPH  |
| Júlia Medeiros Angelozi           | RM556364  | 2TDSPH  |
| Felipe Ribeiro Tardochi da Silva  | RM555100  | 2TDSPH  |


[🔗 Repositório: Link para o projeto no Azure Devops](https://dev.azure.com/RM556448/GpsMottuChallenge)

## Planos de Teste
```yaml
epic: cadastro e gerenciamento de motos
└── feature: cadastro de motos
    ├── Testar acesso ao repository Hibernate via swagger - DELETE
    ├── Testar acesso ao repository Hibernate via swagger - GET
    ├── Testar acesso ao repository Hibernate via swagger - POST
    ├── Testar acesso ao repository Hibernate via swagger - PUT
    └── Teste de entidade moto

epic: painel administrativo
├── feature: login e controle de acesso
│   ├── Teste de Login API JAVA
│   ├── Teste de Logout MVC JAVA
│   ├── Teste de Registro API JAVA
│   └── Teste de Login MVC JAVA
│
└── feature: dashboard de motos
    └── Teste de visualização de motos por seção de filial
```

# 🧁 Doces Gab's Atelier - PWA de Gestão Comercial

> 🔒 **Nota sobre Propriedade Intelectual:** Este é um software de natureza comercial (SaaS) desenvolvido para operação real. Por questões de segurança e proteção de negócio, o código-fonte original é mantido em um repositório privado. Este espaço serve como documentação técnica, arquitetural e demonstração das funcionalidades.

## 📱 Demonstração Visual

![tela-inicial](https://github.com/user-attachments/assets/ee6e178d-6ce2-4b0f-b2a1-1c7f52ec315b)
![novas-vendas](https://github.com/user-attachments/assets/66e1e23a-7d14-47d5-8a00-69917c59b821)
![encomendas](https://github.com/user-attachments/assets/317842d7-4235-443a-8cef-f2d0418d01cb)
![catalogo](https://github.com/user-attachments/assets/0723e721-c597-4e0a-8c47-445ba99bc89a)
![calculadora-integrada](https://github.com/user-attachments/assets/a579545c-fedc-4814-8c1e-b8b246e0df05)
![lista-compras](https://github.com/user-attachments/assets/ce68fb9a-80f6-4a75-8717-3c49a56afd07)
![historico-vendas](https://github.com/user-attachments/assets/794026e5-5175-4080-b4db-3003de2ccc76)
![lista-ingredientes](https://github.com/user-attachments/assets/139e8a9e-55b2-4eb5-a8bc-01dcc496a9e6)



## O Problema e a Solução
O controle de encomendas, estoque e fechamento de caixa via papel e bloco de notas gerava gargalos operacionais no negócio da Gabriella Dantas. Desenvolvi este PWA com um CRUD completo para unificar a rotina de ponta a ponta, focando na dor operacional real e na escalabilidade da confeitaria.

## Funcionalidades de Alto Valor
- **Controle Financeiro Blindado:** Suporte a pagamentos mistos, aplicação de descontos com travas de segurança (exibição de porcentagem para evitar erro humano) e fechamento de caixa diário.
- **Gestão de Insumos:** Sistema de lista de ingredientes com conversão inteligente para lista de compras.
- **Inteligência de Negócio:** Gráficos de faturamento (semanal/mensal) e exportação total de dados em TXT para backup.
- **Automação de Atendimento:** Calculadora com histórico e integração direta para disparo de confirmações via WhatsApp.

## Arquitetura e Engenharia
Como engenheiro de software, utilizei a metodologia de desenvolvimento acelerado para a interface, concentrando o esforço técnico no que sustenta o produto:

* **Persistência e Segurança:** Modelagem de banco de dados relacional no **Supabase** com camadas de **RLS (Row Level Security)** para proteção total de dados.
* **Regras de Negócio:** Implementação manual de lógicas complexas de transação, cálculo de descontos e controle de estados do carrinho.
* **QA & Refatoração:** Testes extensivos de usabilidade mobile e correção de roteamento para garantir um PWA estável e instalável.

## Stack Técnica
- **Front-end:** React, Vite, Tailwind CSS.
- **Back-end:** Supabase (Auth, Database, RLS).
- **Modelo:** PWA (Progressive Web App).

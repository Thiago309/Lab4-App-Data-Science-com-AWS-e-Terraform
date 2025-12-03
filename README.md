# Lab 4 - Deploy de Infraestrutura e API de Data Science na AWS com Terraform

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Engenharia de Dados](https://img.shields.io/badge/Engenharia%20de%20Dados-orange?style=for-the-badge)

> **Resumo:** Neste Laboratório realizei a automação completa de uma aplicação composta por uma API que interage entre o front-end (web) e o back-end (modelo de Machine Learning).

---

## 🎯 Definição de Negócio e Arquitetura da Solução

O objetivo principal deste Lab é desenvolver e implementar uma infraestrutura na nuvem usando **Terraform** para hospedar uma aplicação de Data Science na **AWS**. 

A aplicação foca em um modelo de **Machine Learning (ML)** projetado para prever se clientes vão realizar novas compras com base em seus históricos de gastos.

---

## 📋 Especificações do Lab

#### 🧠 Desenvolvimento de Modelo de ML
* Construir um modelo de Machine Learning utilizando dados históricos de compras para prever futuras ações.
* Garantir a precisão e eficiência do modelo.

#### ☁️ Implementação de Infraestrutura na AWS
* Utilizar serviços AWS (**Amazon EC2, S3 e IAM**) para hospedar a aplicação.
* Garantir segurança, escalabilidade e alta disponibilidade.

#### 🤖 Automatização com Terraform
* Empregar **Terraform** para automatizar a implantação na AWS (IaC), assegurando consistência.
* Documentar o código para facilitar manutenção e atualizações futuras.

#### 🔌 Desenvolvimento de API
* Criar uma API para integrar o modelo de ML com a aplicação de front-end.
* Assegurar que a API seja segura, escalável e de fácil utilização.

## 📂 Estrutura do Projeto

```bash
LAB4-APP-DATA-SCIENCE-COM-AWS-E-TERRAFORM
├── IaC/
│   ├── dsa_iac_deploy/
│   │   ├── main.tf                # Configuração principal do Terraform
│   │   ├── outputs.tf             # Definição das saídas (outputs)
│   │   └── upload_to_s3.sh        # Script auxiliar para upload no S3
│   └── dsa_ml_app/
│       ├── templates/
│       │   └── index.html         # Front-end da aplicação (HTML)
│       ├── app.py                 # API / Aplicação principal
│       ├── cria_modelo.py         # Script de treinamento do modelo ML
│       └── modelo_dsa_treinado.pkl # Arquivo do modelo serializado (Pickle)
├── .gitattributes
├── .gitignore                     # Arquivos ignorados pelo Git
├── Dockerfile                     # Configuração da imagem Docker
├── LEIAME.txt                     # Instruções adicionais
├── LICENSE
└── README.md                      # Documentação do projeto
```

---

## 🚀 Resultados Esperados

A conclusão bem-sucedida deste Lab resulta em uma aplicação de Data Science **totalmente funcional e automatizada**, capaz de fornecer insights valiosos sobre o comportamento de compra dos clientes, apoiando decisões estratégicas de negócios e marketing.

---

## 📝 Autor

Desenvolvido por [Thiago Vinicius](https://www.linkedin.com/in/thiagoviniciusbsantos/).

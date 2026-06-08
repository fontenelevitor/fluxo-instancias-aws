# 🧠 Desafio DIO - Usabilidade AWS Lambda + S3

Este projeto faz parte do desafio da **Digital Innovation One (DIO)** sobre gerenciamento de instâncias e serviços na AWS.  
O objetivo é demonstrar a integração entre **Amazon S3** e **AWS Lambda**, aplicando os conceitos aprendidos em um cenário prático e realista.

---

## 🚀 Objetivo do Projeto

Criar um fluxo automatizado de **processamento de imagens** utilizando **AWS Lambda** e **Amazon S3**, consolidando o aprendizado sobre:
- Funções serverless (Lambda)
- Armazenamento de objetos (S3)
- Eventos e triggers
- Documentação técnica e versionamento com GitHub

---

## 🧩 Cenário Realista

Imagine um sistema onde usuários enviam imagens para um site.  
Assim que uma imagem é enviada, o **Amazon S3** armazena o arquivo e aciona uma **função Lambda** que:

1. Redimensiona a imagem para diferentes tamanhos (thumbnail e alta resolução);
2. Otimiza o arquivo para reduzir o tamanho;
3. Armazena as versões otimizadas em buckets separados;
4. Registra metadados (nome, tamanho, data, URL) em uma tabela **DynamoDB**;
5. Registra logs da execução no **CloudWatch**.

---

## 🧱 Arquitetura do Fluxo

[https://github.com/fontenelevitor/fluxo-instancias-aws/images](https://github.com/fontenelevitor/fluxo-instancias-aws/blob/main/images/fluxo%20lambda%20e%20s3.png)

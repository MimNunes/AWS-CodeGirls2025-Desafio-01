# 🚀 Desafio DIO – Gerenciamento de Instâncias EC2 na AWS

Este repositório documenta meus aprendizados no desafio da **DIO**, com foco no **gerenciamento de instâncias EC2 da AWS**. O objetivo principal foi aprofundar o conhecimento sobre como configurar, utilizar e integrar instâncias de computação em nuvem com outros serviços essenciais da AWS, além de desenvolver a capacidade de **documentar arquiteturas de sistemas** de forma clara e organizada.

---

## 📌 Objetivos do Desafio

- Entender os **fundamentos do serviço EC2** e sua importância em ambientes de computação em nuvem.  
- Explorar os **diferentes tipos de instâncias** e identificar os cenários ideais para cada uma.  
- Aprender a integrar o EC2 com outros serviços AWS, como **EBS, S3 e Lambda**, de forma eficiente.  
- Desenvolver habilidades de **documentação técnica**, incluindo a representação visual de arquiteturas com **Draw.io**.  
- Consolidar boas práticas de **planejamento e organização de infraestrutura em nuvem**.  

---

## 🖥️ Conteúdos Estudados

### 🔹 EC2 (Elastic Compute Cloud)
O **EC2** é o serviço de computação em nuvem da AWS que permite criar e gerenciar **servidores virtuais escaláveis**. Ele oferece flexibilidade para rodar aplicações de diversos tipos, desde websites simples até sistemas corporativos complexos, permitindo controlar o **processamento, memória, armazenamento e rede** de cada instância.

### 🔹 Tipos de Instâncias EC2
As instâncias EC2 são organizadas de acordo com suas características e finalidade:

- **General Purpose (Uso Geral):** equilibradas em CPU, memória e rede. Exemplos: T3, T3a, M5, M6g.  
- **Compute Optimized (Computação Otimizada):** ideais para cargas de trabalho que demandam alto processamento. Exemplos: C4, C5, C6g.  
- **Memory Optimized (Memória Otimizada):** indicadas para aplicações que exigem grande capacidade de memória, como bancos de dados e análise de dados em larga escala. Exemplos: R5, R6g, X1e.  
- **Storage Optimized (Armazenamento Otimizado):** projetadas para aplicações que requerem alto desempenho de I/O em disco. Exemplos: I3, D2, H1.  
- **Accelerated Computing (Aceleração/GPUs):** voltadas para processamento gráfico, aprendizado de máquina e simulações de alto desempenho. Exemplos: P3, G4, F1, Inf1.  

### 🔹 Integração com Outros Serviços AWS
- **EBS (Elastic Block Store):** oferece armazenamento em blocos persistente, ideal para sistemas que necessitam de **armazenamento de dados de alta performance** ligado diretamente à instância EC2.  
- **S3 (Simple Storage Service):** serviço de armazenamento de objetos escalável e acessível via internet, utilizado para guardar **arquivos, backups e conteúdos de aprendizado**, como vídeos e PDFs.  
- **Lambda:** permite executar funções serverless para **automatizar processos**, como geração de certificados, validação de uploads e organização de conteúdos.

### 🔹 Documentação e Visualização de Arquitetura
- Uso do **Draw.io** para criar diagramas claros e intuitivos da infraestrutura, incluindo instâncias, volumes de armazenamento, buckets S3 e fluxos de automação.  
- Facilita o **planejamento, compartilhamento e manutenção** de projetos de TI, tornando a documentação compreensível para desenvolvedores e stakeholders.  

---

## 📚 Principais Aprendizados

- Diferença entre **armazenamento em blocos (EBS)** e **armazenamento de objetos (S3)**, e quando utilizar cada um.  
- Aplicação prática do **S3 como repositório centralizado de conteúdos educativos**, garantindo escalabilidade e acesso seguro para alunos e professores.  
- Importância da **documentação visual** na compreensão de sistemas distribuídos e integração entre serviços AWS.  
- Planejamento e automação de processos usando **Lambda**, melhorando eficiência operacional e garantindo que certificados e materiais estejam sempre atualizados.  

---

## 📊 Cenário Prático – Plataforma de Educação Online 🎓

Para aplicar os conceitos estudados, desenvolvi um **cenário de plataforma de educação online**, simulando como professores e alunos poderiam interagir em um ambiente seguro e escalável:

- **EC2:** hospeda a aplicação web da plataforma, permitindo o acesso a cursos, aulas e dashboards de desempenho.  
- **EBS:** armazena o código-fonte, configurações e logs da aplicação, garantindo persistência e desempenho.  
- **S3:** funciona como repositório de materiais didáticos, vídeos de aulas e certificados em PDF.  
- **Lambda:** automatiza tarefas importantes, como geração de certificados, validação de uploads de materiais e organização de conteúdos por curso.  

💡 Este cenário demonstra como a AWS pode ser utilizada para criar uma **plataforma educacional escalável e segura**, permitindo que alunos acessem conteúdos, concluam cursos e recebam certificados digitais de forma prática e confiável.

---

## 📎 Tecnologias e Ferramentas Utilizadas

- **AWS:** EC2, EBS, S3, Lambda  
- **Draw.io:** criação de diagramas de arquitetura  
- **Markdown:** documentação técnica  

---

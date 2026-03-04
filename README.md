# 📄 Resenha Crítica: Arquitetura de Microsserviços

> Atividade acadêmica desenvolvida para a disciplina de **Projeto de Software** na **PUC Minas**.

👨‍🏫 **Professor Orientador:** João Paulo Aramuni ([@joaopauloaramuni](https://github.com/joaopauloaramuni))  
📅 **Data de Realização:** 03/03/2025 

📢 Aproveita que você leu até aqui e leia o artigo: https://martinfowler.com/articles/microservices.html

---

## 🎯 Objetivo do Repositório
Este repositório contém uma resenha crítica focada no artigo seminal *"Microservices"*, de James Lewis e Martin Fowler. O objetivo deste trabalho é dissecar a teoria por trás da arquitetura distribuída e, em seguida, aplicar esses conceitos arquiteturais a sistemas web reais desenvolvidos ao longo da minha formação.

## 🔨 Estrutura da Resenha
A análise foi estruturada em duas etapas fundamentais:

* **Parte 1: Fundamentação Teórica** Síntese da abordagem de Lewis e Fowler sobre microsserviços. Exploro o contraste com o modelo monolítico, as vantagens operacionais (como *deploy* independente e escalabilidade direcionada) e os desafios inerentes à infraestrutura (complexidade de rede e consistência de dados).
  
* **Parte 2: Aplicação Prática e Estudo de Caso** Uma auditoria arquitetural de projetos do meu próprio portfólio. Analiso como as aplicações que desenvolvi na universidade poderiam ter sua resiliência e estabilidade maximizadas através do isolamento de domínios.

## 💻 Projetos Analisados na Resenha
Para validar a teoria no mundo físico, utilizei a premissa de microsserviços nos seguintes projetos interdisciplinares da PUC Minas:

1. **Re.use:** Plataforma focada em economia circular e doação de roupas. A resenha reflete sobre como a separação entre o serviço de identidade e o motor de *match* (cruzamento de doações) otimizaria o sistema em picos de acesso.
2. **Detalhes Prata:** Plataforma de e-commerce de joias. O texto aborda a necessidade crítica de aplicar o princípio de *Design for Failure*, isolando o serviço de vitrine do gateway de pagamento para garantir tolerância a falhas durante o *checkout*.

## 📈 Conclusão e Aprendizado
Na engenharia de software, assim como no cálculo de otimização, a primeira iteração de um sistema raramente atinge o limite da eficiência máxima. Desenvolver aplicações centralizadas no início da graduação forneceu a base perfeita para a absorção deste artigo. A teoria estudada me permitiu visualizar a refatoração e necessária para transformar arquiteturas fortemente acopladas em ecossistemas modernos e escaláveis.

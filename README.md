<p align="center" style="font-size:28px;"><strong><em>Documentação do Projeto Integrador</em></strong></p>

<div align="center" id="inicio">

  # Sistema de Agendamento para Clinica de Estética
  ### Centro Paula Souza
  ### Faculdade de Tecnologia de Jahu 
  ### Curso de Tecnologia em Desenvolvimento de Software Multiplataforma
  ### Jaú, SP, BR
  ### Início: 2º Semestre / 2025

  </div>

  # Autores:
<h3 align="center">
  <a href="icone Linkedin"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linkedin/linkedin-original.svg" alt="LinkedIn" align="center" width="20"></a> &nbsp;
  <a href="https://www.linkedin.com/in/tainaravit-santos2025/">Tainara Santos</a>;
  <a href="#">Evellyn</a>;
  <a href="#">Lucas</a>;
  <a href="#">Aline</a>;
  <a href="#">Luhan</a>.
</h3>

# Projeto-Integrador-Fatec-Jau
O projeto tem como objetivo desenvolver um sistema de agendamento e gestão de atendimentos para uma clínica de estética, trazendo mais organização, praticidade e eficiência no relacionamento entre clientes e esteticistas.



# *Documentação do Projeto Integrador (PI)*  

<details>
  <summary><strong>Sumário</strong></summary>

- [1. Introdução](#1-introdução)
  - [Objetivos](#-objetivos)
  - [Metodologia](#-metodologia)
- [2. Requisitos](#2-requisitos)
  - [Requisitos funcionais](-requisitos-funcionais)
  - [Requisitos não funcionais](#-requisitos-não-funcionais)
- [3. Modelo de casos de uso](#3-modelo-de-casos-de-uso)
- [4. Modelo do banco de dados](#4-modelo-do-banco-de-dados)
- [5. Banco de dados](#5-banco-de-dados)
- [6. Diagrama de classes](#6-diagrama-de-classes)
- [7. Estudo de viabilidade](#7-estudo-de-viabilidade)
- [8. Regras de negócio (Modelo Canvas)](#8-regras-de-negócio-modelo-canvas)
- [9. Design](#9-design)
- [10. Protótipo](#10-protótipo)
- [11. Aplicação](#11-aplicação)

</details>

---

# 1. Introdução  
*(Contextualização, justificativa do projeto: Por quê?)*  

## 🎯 Objetivos  

## 🛠️ Metodologia  
*(Métodos, tecnologias, modelos de processo, ferramentas utilizadas.  
Responde às perguntas: Como? Com o quê? Onde? Quando?)*  

---

# 2. Requisitos  

## ⚙️ Requisitos Funcionais (RF)
RF01 – Cancelamento/Remarcação pelo Cliente:
O sistema deve permitir que o cliente cancele uma sessão com antecedência mínima de 24 horas.

RF02 – Cancelamento pela Esteticista:
O sistema deve permitir que a esteticista cancele o horário de um cliente e deve notificar o cliente automaticamente.

RF03 – Agenda Individual:
O sistema deve permitir que cada esteticista possua login individual, com acesso apenas à sua própria agenda.

RF04 – Escolha de Esteticista:
O sistema deve permitir que o cliente escolha a esteticista desejada no momento do agendamento.

RF05 – Relatórios Gerenciais:
O sistema deve gerar relatórios gerenciais, incluindo:

Serviços mais realizados
Horários de pico
Profissionais mais requisitados
RF06 – Relatórios de Clientes:
O sistema deve gerar relatórios relacionados ao cliente, incluindo:

Frequência de atendimento
Lembretes de aniversário
RF07 – Notificações e Lembretes:
O sistema deve enviar notificações/lembretes de consultas aos clientes, preferencialmente via WhatsApp.

RF08 – Controle Financeiro:
O sistema deve incluir controle financeiro, permitindo registrar:

Pagamentos
Pacotes de sessões
Inadimplências
OBS: O acesso a esses dados deve ser restrito apenas à administradora.

RF09 – Integração Externa:
O sistema deve permitir integração com redes sociais e aplicativos de mensagens.

RF10 – Responsividade:
O sistema deve possuir versão responsiva, funcionando tanto em computador quanto em celular.

RF11 – Personalização da Identidade Visual:
O sistema deve permitir que a administradora personalize a identidade visual (cores e logotipo).

RF12 – Agendamento e Pagamento Online:
O sistema deve possibilitar agendamento e pagamentos online, incluindo opção de pré-pagamento parcial como garantia.

RF13 – Marketing Automatizado:
O sistema deve disponibilizar recursos de marketing, incluindo:

Promoções
Lembretes de aniversário
Programa de fidelidade
RF14 – Autonomia da Administradora:
O sistema deve permitir que a administradora tenha autonomia para realizar alterações, como ajustes em funcionalidades, regras ou conteúdos.

## ⚙️ Requisitos Não Funcionais (RNF)
RNF01 – Segurança (Autenticação):
O sistema deve exigir login e senha válidos para acesso, garantindo a proteção dos dados do usuário.

RNF02 – Desempenho:
As páginas do sistema devem carregar em no máximo 3 segundos, mesmo em condições de internet limitada.

RNF03 – Usabilidade:
Um novo usuário deve conseguir realizar um agendamento em até 3 minutos, sem necessidade de treinamento prévio.

RNF04 – Personalização da Interface:
A interface deve ser personalizada e detalhada, sem comprometer a clareza e a facilidade de uso.

RNF05 – Experiência do Usuário:
O sistema deve proporcionar uma experiência agradável e intuitiva, incentivando o retorno e a fidelização dos clientes.

RNF06 – Segurança (Dados Sensíveis):
Os dados de pagamento devem ser armazenados e transmitidos de forma criptografada, seguindo boas práticas de segurança.

RNF07 – Responsividade:
O sistema deve ser responsivo, funcionando corretamente em dispositivos desktop e mobile.

Regras de Negócio (RN)
RN01 – Cancelamento de Cliente:
O cliente só poderá cancelar sessões até 24 horas de antecedência.

RN02 – Cancelamento de Esteticista:
Esteticistas podem cancelar sessões, mas o sistema deve notificar o cliente automaticamente.

RN03 – Agenda de Esteticista:
Cada esteticista só pode visualizar e gerenciar sua própria agenda.

RN04 – Controle Financeiro:
Somente a administradora terá acesso ao controle financeiro (pagamentos, pacotes e inadimplência).

RN05 – Escolha de Esteticista:
O cliente pode selecionar a esteticista desejada durante o agendamento.

RN06 – Pré-pagamento:
Em agendamentos online, o cliente deverá pagar um percentual definido pela administradora como pré-pagamento.

RN07 – Lembretes Automáticos:
Todos os clientes devem receber lembretes automáticos de consulta, preferencialmente via WhatsApp.

RN08 – Marketing Automatizado:
O sistema deve executar ações de marketing automatizadas, como promoções, lembretes de aniversário e fidelização.

RN09 – Restrição de Acesso:
O acesso aos dados será restrito e protegido por login com credenciais válidas.

RN10 – Autonomia da Administradora:
A administradora deve ter autonomia para alterar regras e configurações diretamente no sistema.




# 7. Estudo de viabilidade  

<h1> Sistema ERP para Clínica de Estética </h1>

## Viabilidade Técnica:
  A análise sobre a viabilidade técnica do sistema ERP mostrou que sua criação e funcionamento é possível com os recursos disponíveis. O time de desenvolvimento possui e está evoluindo em níveis de programação, gerenciamento e conhecimento técnico nos recursos necessários. A infraestrutura do projeto permite fácil integração e manuseio por parte do usuário.

## Viabilidade Operacional:
Fluxo operacional:
-	O cliente acessa o site e agenda o horário.
-	O sistema envia automaticamente um lembrete por WhatsApp ou e-mail.
-	Profissional confirma o agendamento.
-	O sistema financeiro integrado faz o controle das cobranças.

Usuários principais:
-	Esteticistas.
-	Gestores da clínica.
-	Clientes.

Benefícios esperados:
-	Redução de erros como agendamentos duplicados ou esquecidos.
-	Fidelização dos clientes com programas de assinatura e promoções.
-	Comunicação automática.
-	Melhor tomada de decisão com base nos relatórios.

Conclusão operacional:
O sistema vai se integrar de forma natural às rotinas da clínica. A equipe só precisará de um treinamento curto, para aprender a utilizar todas as funções.

## Viabilidade Financeira:
Custos estimados:
O projeto não terá custo de desenvolvimento, pois será elaborado com apoio academico dos alunos e professores do curso DSM – Fatec Jahu

Modelos de receita possíveis:
-	SaaS: a clínica paga valor mensal de R$ 149,90. 

Exemplo de retorno no modelo SaaS:
Se 10 clínicas assinarem o sistema por R$ 149,900/mês, o faturamento será de R$ 1.499,00/mês.
Com isso, o investimento inicial pode ser recuperado em 7 meses.

Conclusão financeira:
O projeto é financeiramente viável. O modelo de mensalidade SaaS é mais vantajoso, pois garante retorno contínuo e sustentável.

## Viabilidade de Mercado:
O setor de estética no Brasil está em crescimento e muitas clínicas ainda utilizam métodos manuais, como planilhas ou cadernos, o que causa falhas na gestão. Isso mostra uma grande oportunidade de digitalização.
Concorrentes identificados:
-	MP Sistemas Jaú
-	STi3 Sistemas (localizado em Jaú)
-	Gestek (Goiania, porém é um sistema online totalmente focado em atender clinicas de estética)

Diferenciais do projeto:
-	Maior facilidade de acesso
-	Mais flexível
-	Maior adaptabilidade

Conclusão de mercado:
Existe uma demanda crescente no setor. O diferencial do projeto está no foco exclusivo em clínicas de estética e na personalização, indo além do básico oferecido pelos concorrentes.

Resumo Final
O estudo mostrou que o projeto é: 
-	Tecnicamente viável: os recursos necessários foram adquiridos.
-	Operacionalmente aplicável: simples de usar, exigindo pouco treinamento.
-	Financeiramente sustentável: com possibilidade de retorno rápido no modelo SaaS.


---

# 8. Regras de negócio (Modelo Canvas)  

<a href="IMGS/ModeloCANVA.jpg" class="image fit"><img src="IMGS/ModeloCANVA.jpg" alt="Modelo de negocio canva"></a>

---

# 9. Design  
- 🎨 Paleta de cores  
- ✍️ Tipografia  
- 🔖 Logo  
- 🧩 Wireframes  
- 🗺️ Modelo de navegação  

---

# 10. Protótipo  
*(Protótipo funcional no Figma ou outra ferramenta. Colocar o link aqui)*  

---

# 11. Aplicação




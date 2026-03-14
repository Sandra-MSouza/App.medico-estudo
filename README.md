🏥 Medical Appointment App (Case Study)

📋 Visão Geral
Este projeto é uma plataforma end-to-end de agendamento médico desenvolvida para resolver desafios reais de gestão em saúde. 

O sistema cobre desde a descoberta de profissionais até a confirmação automatizada de consultas, dividindo-se entre uma interface focada em conversão para pacientes e um back-office completo para administradores.

🛠️ Tech StackPlataforma: 

Bubble.io.
Banco de Dados: Modelagem Relacional e Option Sets.Integrações: API REST (Brasil API) via API Connector.
Automação: Workflows orientados a eventos e e-mails transacionais.

🏗️ Arquitetura de Dados

O coração do projeto é um banco de dados relacional estruturado para garantir integridade e escalabilidade:Data Types: Paciente, Médico e Consulta.
Option Sets: Utilizados para Especialidade Médica e Status da Consulta, otimizando a performance de busca e evitando inconsistências de texto.

🚀 Funcionalidades Principais:

Módulo Administrativo (Back-Office): Painel CRUD para gestão de médicos e monitoramento de consultas em tempo real utilizando Repeating Groups dinâmicos.

Jornada do Paciente: Motor de busca com filtros inteligentes por nome e especialidade.

Integração com Brasil API: Preenchimento automático de endereço (Rua, Bairro, Cidade) a partir do CEP, reduzindo o atrito no cadastro.

Automação de Confirmação: Workflow que processa o agendamento e dispara automaticamente um e-mail com os detalhes da consulta.

📖 O que este projeto demonstra?
Domínio de Lógica de Sistemas: Implementação de workflows assíncronos em múltiplos passos.
Habilidades de Integração: Consumo de APIs externas e manipulação de payloads JSON.
UX/UI: Criação de interfaces responsivas e orientadas à conversão

# 🚀 ClickDesk – Sistema Inteligente de Gestão de Chamados

## 📖 Sobre o Projeto
O **ClickDesk** é um sistema integrado para **gestão de chamados e suporte técnico**, desenvolvido como parte do **PIM III - UNIP**.  
Ele utiliza **Inteligência Artificial (IA)** para **triagem automática, categorização e sugestão de soluções** com base em histórico de ocorrências.

O objetivo principal é **otimizar o atendimento técnico**, reduzindo tempo de resposta e aumentando a eficiência operacional.

---

## 🎯 Objetivos
- Estruturar o sistema de chamados com regras de negócio claras.
- Implementar priorização automática de chamados via IA.
- Integrar uma base de conhecimento para problemas recorrentes.
- Modelar os principais fluxos com **UML**.
- Prototipar interfaces responsivas e intuitivas.
- Garantir segurança da informação e conformidade com a **LGPD**.

---

## 🛠 Tecnologias Utilizadas
### Backend
- Node.js / Express (ou outra linguagem definida)
- Microsoft SQL Server (SGBD)
- JWT para autenticação
- IA / NLP para classificação de chamados

### Frontend
- React.js (ou framework escolhido)
- TailwindCSS (estilização responsiva)
- Axios (requisições à API)

### Ferramentas e Metodologias
- GitHub + GitFlow
- Scrum + Kanban
- UML (casos de uso, classes, sequência, implantação)
- Figma (protótipos de interface)
- LGPD como requisito de segurança e privacidade

---

## 📂 Estrutura do Repositório
ClickDesk/
│── backend/ # Código do servidor (API REST, IA, banco de dados)
│── frontend/ # Código do cliente (interfaces web/mobile)
│── database/ # Modelagem, DER, scripts SQL
│── docs/ # Documentação (UML, PIM, protótipos, etc.)
│── .github/ # Workflows de CI/CD
│── README.md # Este arquivo
│── LICENSE # Licença do projeto
│── CONTRIBUTING.md # Guia de contribuição



---

## ▶️ Como Rodar o Projeto

### 🔧 Pré-requisitos
- Node.js (v18+)
- SQL Server
- Git

### 📌 Clonar Repositório
```bash
git clone https://github.com/SeuUsuario/ClickDesk.git
cd ClickDesk


cd backend
npm install
npm run dev


cd frontend
npm install
npm start


✅ Funcionalidades

Registro e acompanhamento de chamados.

Triagem e priorização inteligente por IA.

Base de conhecimento integrada (FAQ).

Painel do técnico com filtros e notificações.

Histórico de interações e relatórios de atendimento.

Feedback dos usuários para aprendizado contínuo da IA.


👥 Equipe de Desenvolvimento

André Luis dos Santos Barbosa – RA: G009BI6

Erika Aparecida Cordeiro – RA: T420GH6

Kaíque Loamir Siqueira Uchoa – RA: G9834H9

Vinicius de Andrade Fagundes – RA: G989CE5


Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE
 para mais detalhes.


Referências

Larman, Craig. Utilizando UML e padrões. Bookman, 2007.

Pressman, Roger. Engenharia de Software. McGraw-Hill, 2016.

Russell, Stuart; Norvig, Peter. Inteligência Artificial. Elsevier, 2013.

Lei nº 13.709/2018 – Lei Geral de Proteção de Dados (LGPD).

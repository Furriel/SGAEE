# 🧩 SGAEE - Sistema de Gestão do Atendimento Educacional Especializado

![Status](https://img.shields.io/badge/Status-Estável-green)
![Versão](https://img.shields.io/badge/Versão-15.0-blue)
![Licença](https://img.shields.io/badge/Licença-MIT-yellow)

O **SGAEE** é uma solução leve, portátil e eficiente desenvolvida para auxiliar professores do AEE (Atendimento Educacional Especializado) na gestão pedagógica, acompanhamento evolutivo e geração de relatórios oficiais de seus estudantes.

Desenvolvido como uma **Single Page Application (SPA)** contida em um único arquivo, o sistema funciona offline, prioriza a privacidade dos dados e agora conta com **geração profissional de documentos PDF**.

🔗 **Acesse Online:** [https://furriel.github.io/SGAEE/](https://furriel.github.io/SGAEE/)

---

## 🎯 Objetivo

Facilitar a rotina burocrática do professor de Educação Especial, permitindo que o foco permaneça no desenvolvimento humano. O sistema centraliza o fluxo pedagógico desde a avaliação inicial até a emissão do relatório final, alinhado às diretrizes do MEC e da Política Nacional de Educação Especial.

## ✨ Funcionalidades Principais

* **👥 Gestão de Alunos:** Cadastro completo com dados demográficos e necessidades específicas.
* **🧠 Avaliação Pedagógica Inicial:** Mapeamento detalhado em 4 eixos (Cognitivo, Acadêmico, Psicomotor, Social).
* **📝 Diário de Atendimento:** Registro de sessões com **sugestão inteligente de estratégias** baseada no objetivo selecionado.
* **📊 Monitoramento de Evolução:** Checklists periódicos que geram comparativos automáticos.
* **📈 Análise Gráfica:** Gráficos de radar (Spider Chart) para visualização clara das competências consolidadas vs. em desenvolvimento.
* **📄 PDF Engine Nativa (NOVO):** Geração de relatórios profissionais em PDF diretamente no navegador (sem janelas de impressão), com formatação ABNT, cabeçalhos automáticos e texto justificado.
* **📚 Relatórios em Lote (NOVO):** Capacidade de gerar um **Caderno de Relatórios** único contendo todos os alunos de uma determinada turma ou deficiência, facilitando a entrega semestral.
* **🔒 Privacidade Total:** Todos os dados são salvos no **LocalStorage** do navegador. Nada é enviado para a nuvem.
* **💾 Backup e Exportação:** Exportação de dados para Excel (.xlsx) e sistema de Backup/Restore via arquivo JSON.

## 🚀 Tecnologias Utilizadas

O projeto foi construído para ser **agnóstico de backend** e rodar diretamente no navegador cliente.

* **Core:** [React.js](https://react.dev/) (via CDN, sem necessidade de build).
* **Estilização:** [Tailwind CSS](https://tailwindcss.com/) (para interface moderna e responsiva).
* **Processamento de Dados & Documentos:**
    * [pdfMake](http://pdfmake.org/) (**Novo**: Engine para geração de PDFs complexos no client-side).
    * [Chart.js](https://www.chartjs.org/) (Visualização de dados).
    * [SheetJS](https://sheetjs.com/) (Manipulação de planilhas Excel).
    * [Babel](https://babeljs.io/) (Transpilação JSX em tempo real).

## 📦 Como Usar

Existem duas formas de utilizar o SGAEE:

### 🌐 1. Acesso Online (Recomendado)
Acesse diretamente pelo navegador, sem necessidade de instalação:
**[https://furriel.github.io/SGAEE/](https://furriel.github.io/SGAEE/)**

### 📂 2. Uso Offline (Arquivo Local)
Ideal para locais sem internet ou para manter uma cópia de segurança.
1.  **Baixe o arquivo:** Faça o download do arquivo `.html` mais recente neste repositório.
2.  **Abra:** Clique duas vezes no arquivo para abrir no seu navegador (Chrome, Edge, Firefox).
3.  **Pronto:** O sistema roda localmente com todas as funcionalidades.

> **Nota de Privacidade:** Independente da forma de uso (Online ou Offline), o sistema utiliza o `LocalStorage`. Isso significa que seus dados ficam salvos **apenas no navegador e computador** onde foram inseridos. Se você limpar o cache do navegador, os dados serão perdidos. **Faça backups frequentes** (botão "Baixar Backup" na aba Configurações).

## 📚 Fluxo Pedagógico

O sistema guia o professor através de 5 etapas lógicas:
1.  **Cadastro:** Entrada do estudante no sistema.
2.  **Mapeamento:** Avaliação diagnóstica inicial.
3.  **Atendimento:** Registros diários das intervenções.
4.  **Evolução:** Reavaliação para medir o progresso.
5.  **Relatório:** Geração do documento final (Individual ou Caderno da Turma).

## 🛡️ Segurança e Privacidade

Este software segue o princípio de **Privacy by Design**.
- Nenhum dado é enviado para servidores externos.
- Não há rastreamento de usuários.
- O banco de dados é o próprio navegador do usuário.

## 🤝 Contribuição

Contribuições são bem-vindas! Como o projeto é um arquivo único para facilitar a distribuição entre professores sem conhecimento técnico, ao submeter PRs, atente-se para manter a estrutura de importação via CDN.

1.  Faça um Fork do projeto.
2.  Crie uma Branch para sua Feature (`git checkout -b feature/MinhaFeature`).
3.  Faça o Commit (`git commit -m 'Adicionando nova feature'`).
4.  Faça o Push (`git push origin feature/MinhaFeature`).
5.  Abra um Pull Request.

## 👨‍💻 Autor

Desenvolvido por **Geovanne Pereira Furriel**.

---

*Este projeto é uma ferramenta de apoio pedagógico e não substitui avaliações clínicas ou médicas.*

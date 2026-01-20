# 🧩 SGAEE - Sistema de Gestão do Atendimento Educacional Especializado

![Status](https://img.shields.io/badge/Status-Estável-green)
![Versão](https://img.shields.io/badge/Versão-14.0-blue)
![Licença](https://img.shields.io/badge/Licença-MIT-yellow)

O **SGAEE** é uma solução leve, portátil e eficiente desenvolvida para auxiliar professores do AEE (Atendimento Educacional Especializado) na gestão pedagógica, acompanhamento evolutivo e geração de relatórios oficiais de seus estudantes.

Desenvolvido como uma **Single Page Application (SPA)** autida em um único arquivo, o sistema funciona offline e prioriza a privacidade dos dados.

---

## 🎯 Objetivo

Facilitar a rotina burocrática do professor de Educação Especial, permitindo que o foco permaneça no desenvolvimento humano. O sistema centraliza o fluxo pedagógico desde a avaliação inicial até a emissão do relatório final, alinhado às diretrizes do MEC e da Política Nacional de Educação Especial.

## ✨ Funcionalidades Principais

* **👥 Gestão de Alunos:** Cadastro completo com dados demográficos e necessidades específicas.
* **🧠 Avaliação Pedagógica Inicial:** Mapeamento detalhado em 4 eixos (Cognitivo, Acadêmico, Psicomotor, Social).
* **📝 Diário de Atendimento:** Registro de sessões com **sugestão inteligente de estratégias** baseada no objetivo selecionado.
* **📊 Monitoramento de Evolução:** Checklists periódicos que geram comparativos automáticos.
* **📈 Análise Gráfica:** Gráficos de radar (Spider Chart) para visualização clara das competências consolidadas vs. em desenvolvimento.
* **📄 Relatórios Automatizados:** Geração de relatórios descritivos em formato ABNT, prontos para impressão ou PDF, com campos para assinatura.
* **🔒 Privacidade Total:** Todos os dados são salvos no **LocalStorage** do navegador. Nada é enviado para a nuvem.
* **💾 Backup e Exportação:** Exportação de dados para Excel (.xlsx) e sistema de Backup/Restore via arquivo JSON.

## 🚀 Tecnologias Utilizadas

O projeto foi construído para ser **agnóstico de backend** e rodar diretamente no navegador cliente.

* **Core:** [React.js](https://react.dev/) (via CDN, sem necessidade de build).
* **Estilização:** [Tailwind CSS](https://tailwindcss.com/) (para interface moderna e responsiva).
* **Processamento de Dados:**
    * [Chart.js](https://www.chartjs.org/) (Visualização de dados).
    * [SheetJS](https://sheetjs.com/) (Manipulação de planilhas Excel).
    * [Babel](https://babeljs.io/) (Transpilação JSX em tempo real).

## 📦 Como Usar

Não é necessário instalar Node.js, NPM ou servidores complexos.

1.  **Baixe o arquivo:** Faça o download do arquivo `sgaee_v14.html` (ou clone este repositório).
2.  **Abra:** Clique duas vezes no arquivo ou arraste-o para o seu navegador (Chrome, Edge, Firefox).
3.  **Pronto:** O sistema está rodando e pronto para uso.

> **Nota:** Como o sistema utiliza o `LocalStorage`, os dados ficam salvos apenas **no navegador e computador** onde foram inseridos. Recomenda-se realizar backups frequentes usando a aba "Segurança de Dados".

## 📚 Fluxo Pedagógico

O sistema guia o professor através de 5 etapas lógicas:
1.  **Cadastro:** Entrada do estudante no sistema.
2.  **Mapeamento:** Avaliação diagnóstica inicial.
3.  **Atendimento:** Registros diários das intervenções.
4.  **Evolução:** Reavaliação para medir o progresso.
5.  **Relatório:** Geração do documento final comprovando o trabalho.

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

Desenvolvido por **Gustavo Rocha Furriel**.

---

*Este projeto é uma ferramenta de apoio pedagógico e não substitui avaliações clínicas ou médicas.*

# Sistema de QA sobre a BNCC e PPCs de Pinhais

## Visão Geral
Este projeto visa desenvolver uma aplicação de inteligência artificial capaz de responder perguntas sobre a **Base Nacional Comum Curricular (BNCC)** e as **Propostas Pedagógicas Curriculares (PPCs) de Pinhais**. O sistema buscará auxiliar educadores e gestores na consulta e exploração desses documentos para apoiar o planejamento pedagógico e a criação de atividades alinhadas aos objetivos educacionais.

## Objetivos do Projeto
- **Respostas Contextualizadas:** Permitir que usuários realizem perguntas sobre os componentes curriculares, objetivos de aprendizagem e competências transversais.
- **Sugestão de Atividades:** Gerar ideias de atividades baseadas em objetivos específicos da BNCC e PPCs.
- **Identificação de Objetivos Transversais:** Facilitar a localização de competências transversais e sua relação com os objetivos de aprendizagem.
- **Consulta Personalizada:** Proporcionar respostas adaptadas aos níveis escolares e áreas do conhecimento.

## Funcionalidades Planejadas
1. **Consulta de Objetivos:**
   - Localizar objetivos de aprendizagem por componente curricular, série ou palavras-chave.
   - Exibir descrições completas dos objetivos relevantes.

2. **Sugestão de Atividades:**
   - Propor atividades práticas com base em objetivos selecionados.
   - Incluir ideias alinhadas às competências gerais e transversais.

3. **Busca Semântica:**
   - Usar embeddings para identificar seções relevantes no texto com base em perguntas feitas pelo usuário.

4. **Interface Interativa:**
   - Criar uma interface simples para consultas e respostas.

## Tecnologias Pretendidas
- **OpenAI GPT:** Para gerar respostas baseadas nos textos da BNCC e PPCs.
- **Hugging Face Transformers:** Para ajustar o modelo de linguagem se necessário.
- **FAISS ou Pinecone:** Para armazenar e buscar embeddings.
- **Python:** Para processamento e desenvolvimento do pipeline de QA.
- **Streamlit ou Flask:** Para criar uma interface amigável ao usuário.

## Status do Projeto
Atualmente, o projeto encontra-se na fase de planejamento e organização dos documentos base. Nenhuma funcionalidade foi implementada ainda.

## Contribuições
Contribuições são bem-vindas! Se você tem experiência com NLP, educação ou desenvolvimento de sistemas de QA, fique à vontade para abrir issues ou enviar pull requests.

## Licença
Este projeto está licenciado sob a licença **MIT**. Consulte o arquivo `LICENSE` para mais detalhes.


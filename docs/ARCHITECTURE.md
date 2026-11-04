# Architecture / Arquitetura

## Português

### Modelo conceitual
A arquitetura documentada contempla componentes especializados:
1. **Interface e transporte:** interação do usuário e comunicação interna.
2. **RNA / núcleo simbólico:** representação e avaliação de relações estruturadas.
3. **Memória:** persistência e recuperação contextual.
4. **Avaliação:** critérios explícitos para medir saídas e comparar versões.
5. **Worker:** processamento de tarefas auxiliares por fila.
6. **Integrações opcionais:** serviços e modelos locais, incluindo Ollama.

Esta é uma descrição conceitual baseada nos registros de projeto disponíveis; não é um diagrama extraído e conferido diretamente de uma build distribuível.

### Princípios
- Modularidade e responsabilidades explícitas.
- Separação entre inferência simbólica e geração por modelos de linguagem.
- Testes reproduzíveis e avaliação explícita.
- Persistência com atenção à integridade e recuperação.
- Resultados desconhecidos devem permanecer desconhecidos, sem invenção.
- Componentes experimentais não devem ser promovidos sem avaliação.

### Limites
A existência de um módulo ou teste não prova integração ponta a ponta. Funcionamento integrado, desempenho sustentado, segurança operacional e instalação limpa ainda exigem validação reproduzível.

## English

### Conceptual model
The documented architecture comprises specialized components:
1. **Interface and transport:** user interaction and internal communication.
2. **RNA / symbolic core:** representation and evaluation of structured relations.
3. **Memory:** persistence and contextual retrieval.
4. **Evaluation:** explicit criteria for measuring outputs and comparing versions.
5. **Worker:** queue-based auxiliary task processing.
6. **Optional integrations:** local services and models, including Ollama.

This is a conceptual description based on available project records, not a code-derived diagram verified against a distributable build.

### Principles
- Modularity and explicit responsibilities.
- Separation of symbolic inference from language-model generation.
- Reproducible tests and explicit evaluation.
- Persistence with integrity and recovery considerations.
- Unknown results should remain unknown rather than be fabricated.
- Experimental components should not be promoted without evaluation.

### Limitations
The existence of a module or test does not prove end-to-end integration. Integrated behavior, sustained performance, operational security and clean installation still require reproducible validation.

# Sistema de Geração de Recomendações de Treinos e Dicas Alimentares com uso de Inteligência Artificial

Projeto de Formatura da Escola Politécnica da USP: Sistema de Geração de Recomendações de Treinos e Dicas Alimentares com uso de Inteligência Artificial .

## Resumo

O projeto apresenta o desenvolvimento de um sistema capaz de gerar recomendações personalizadas de treinos e planos alimentares com apoio de inteligência artificial. A solução foi pensada para aproximar profissionais da saúde — como nutricionistas e personal trainers — de seus clientes, oferecendo um ambiente unificado em que é possível acompanhar treinos, alimentação e progresso físico de forma integrada. Além do aplicativo mobile, voltado ao usuário final, o trabalho inclui a concepção de uma arquitetura modular e escalável baseada em microsserviços, responsável por orquestrar dados de usuários, treinos, planos alimentares, avaliações e o módulo de IA generativa.

## Contexto e Motivação

O ponto de partida do projeto é o cenário de saúde da população brasileira, marcado por altos índices de sedentarismo, sobrepeso e doenças crônicas como hipertensão e diabetes. Muitas pessoas têm dificuldade em manter uma rotina de exercícios e alimentação equilibrada, seja pela falta de orientação especializada, seja pelo custo de acompanhamento individualizado com profissionais como nutricionistas e personal trainers.

TCC

Além disso, as soluções disponíveis no mercado tendem a tratar treino e nutrição de forma separada, obrigando o usuário a alternar entre diferentes aplicativos e dificultando uma visão integrada do próprio progresso. Nesse contexto, o projeto propõe uma plataforma única, que combina recomendações inteligentes para treinos e alimentação, adaptadas ao perfil de cada pessoa, tornando o processo de adoção de hábitos saudáveis mais acessível, prático e personalizado.

## Objetivos

O objetivo central do trabalho é desenvolver um protótipo de produto digital para o segmento fitness que ofereça acompanhamento personalizado aos usuários finais, combinando a colaboração de profissionais da saúde com a geração automática de recomendações por meio de inteligência artificial generativa. A plataforma busca centralizar, em um único sistema, a criação e o acompanhamento de treinos, planos alimentares e avaliações, facilitando o monitoramento do progresso individual e a construção de um plano mais completo e coerente ao longo do tempo.

TCC

Entre os objetivos específicos estão: definir uma arquitetura de software modular, segura e escalável; projetar e implementar microsserviços dedicados a usuários, treinos, nutrição, avaliações e IA; desenvolver um aplicativo mobile multiplataforma para o perfil de cliente; e integrar um módulo de IA generativa, baseado em técnicas de RAG, capaz de gerar planos de treino e alimentação personalizados a partir dos dados cadastrados no sistema.

TCC

## Desenvolvimento

O desenvolvimento do projeto seguiu um processo estruturado em etapas: estudo bibliográfico sobre atividade física, nutrição, inteligência artificial generativa e boas práticas de arquitetura de software; realização de entrevistas com profissionais da saúde para levantar requisitos reais de uso; especificação de requisitos funcionais e não funcionais; prototipação das telas no Figma; e, por fim, implementação e testes.

TCC

Do ponto de vista técnico, a solução foi construída adotando arquitetura em camadas, microsserviços e princípios de Clean Architecture. O aplicativo mobile foi desenvolvido em React Native com apoio do Expo e de uma biblioteca de componentes para garantir consistência visual e agilidade na construção das interfaces. No backend, foram utilizados Node.js e o framework Fastify para estruturar os microsserviços — responsáveis por usuários, planos alimentares, treinos, avaliações e IA — em conjunto com bancos de dados adequados a cada módulo, incluindo MongoDB para alguns domínios. O módulo de IA foi implementado com o framework LangChain, empregando técnicas de RAG para combinar informações do banco de dados com modelos de linguagem de grande porte na geração de planos e treinos personalizados.

## Resultados

Como resultado, foi entregue um protótipo funcional do aplicativo para o perfil de cliente, permitindo ao usuário se cadastrar, acessar uma tela inicial que resume seu plano alimentar do dia e seu progresso, visualizar seus treinos, consultar planos alimentares detalhados, acompanhar o registro das refeições e conferir avaliações físicas e nutricionais realizadas por profissionais. A solução já é capaz de gerar treinos e planos alimentares personalizados com o auxílio da IA, a partir de dados de anamnese e informações armazenadas nos microsserviços, demonstrando na prática a viabilidade da abordagem proposta.

Do ponto de vista de engenharia de software, o projeto comprovou a viabilidade de uma arquitetura modular, segura e escalável para integrar profissionais da saúde e clientes em um ambiente colaborativo, utilizando modelos generativos com recuperação de contexto. No estágio atual, as funcionalidades voltadas ao cliente estão implementadas e integradas ao backend, enquanto as interfaces completas para nutricionistas e personal trainers são apontadas como evolução natural do sistema em trabalhos futuros, mantendo a mesma base arquitetural.

## Autores

Integrantes:

- Arthur Salvador de Almeida
- Guilherme Castelo Branco de Brito
- Renato Naves Fleury

Orientador:

- Prof. Dr. Jorge Luís Risco Becerra - Departamento de Engenharia de Computação e Sistemas Digitais da Universidade de São Paulo (USP)

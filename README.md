🚀 Desafio - Agente de Transcrição e Estruturação com AI Foundry

Este projeto foi desenvolvido como parte do desafio Build Your First Copilot do curso Microsoft AI Foundry, com o objetivo de criar um agente inteligente capaz de transformar vídeos em conhecimento estruturado.

💡 Ideia principal

A proposta nasceu da necessidade de aproveitar conteúdos ricos (como vídeos de aulas, treinamentos e mentorias) para gerar transcrições limpas, organizadas e úteis — tudo isso com mínima intervenção manual. Com isso, o agente que criei:

- Recebe um link do YouTube como entrada

- Extrai automaticamente a transcrição do vídeo (mesmo que seja gerada automática pelo YouTube)

- Remove ruídos como timestamps e quebras desnecessárias

- Organiza o conteúdo em estrutura JSON por tópicos

- Gera um resumo e sugestões de perguntas frequentes (FAQ)

- Prepara todo o conteúdo para ser reutilizado por outros agentes dentro do Foundry

💬 Isso permite, por exemplo, criar assistentes personalizados que respondem sobre o vídeo sem que o usuário precise assisti-lo. Ideal para capacitações, onboarding de novos membros ou análise de conteúdos extensos.

## 🎯 Objetivo

Criar um agente no AI Foundry capaz de:
- Receber um link de vídeo do YouTube
- Extrair automaticamente a transcrição (mesmo que seja automática)
- Limpar o texto (remover timestamps e ruídos)
- Organizar de forma estruturada
- Gerar um resumo com tópicos
- Preparar o conteúdo para uso em outro agente

---

## 📁 Estrutura do Repositório

```bash
Azure_Frontier_Girls---Challenge_Tati/
│
├── README.md                  # Explicações e roteiro da entrega (este arquivo)
├── prints/                    # Prints de todas as etapas realizadas no Foundry
├── base_conhecimento/        # Arquivo final limpo estruturado em JSON
├── srt/                       # Arquivo original de legenda .srt extraído do vídeo
├── faq_gerada/                # Arquivo de FAQ criado pelo agente final
├── scripts/                   # Scripts utilizados para limpeza, estruturação e testes

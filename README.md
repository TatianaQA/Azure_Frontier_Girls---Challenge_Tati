# 🚀 Desafio - Agente de Transcrição e Estruturação com AI Foundry

Este projeto foi desenvolvido como parte do **desafio Build Your First Copilot** do curso **Microsoft AI Foundry**, com o objetivo de criar um **agente inteligente capaz de transformar vídeos em conhecimento estruturado**.

---

## 💡 Ideia Principal

A proposta nasceu da necessidade de aproveitar conteúdos ricos — como vídeos de aulas, treinamentos e mentorias — para gerar **transcrições limpas, organizadas e úteis**, com **mínima intervenção manual**.
Com isso, o agente criado é capaz de:

* 🎥 Receber um link do **YouTube** como entrada;
* 🧠 Extrair automaticamente a **transcrição do vídeo** (mesmo gerada automaticamente pelo YouTube);
* 🧹 Remover **ruídos**, como timestamps e quebras desnecessárias;
* 📂 Organizar o conteúdo em **estrutura JSON** por tópicos;
* 📝 Gerar **resumos** e **sugestões de perguntas frequentes (FAQ)**;
* 🔄 Preparar todo o conteúdo para ser reutilizado por outros agentes dentro do **Foundry**.

💬 Isso permite criar **assistentes personalizados** que respondem sobre o vídeo sem que o usuário precise assisti-lo — ideal para **capacitações**, **onboarding de novos membros** ou **análise de conteúdos extensos**.

---

## 🎯 Objetivo

Desenvolver um agente no **AI Foundry** capaz de:

* 🔗 Receber um **link de vídeo do YouTube**;
* 🧠 Extrair automaticamente a **transcrição** (mesmo que seja automática);
* 🧹 **Limpar o texto**, removendo timestamps e ruídos;
* 🧾 **Organizar o conteúdo de forma estruturada**;
* 📝 **Gerar um resumo com tópicos principais**;
* 🔄 **Preparar o conteúdo para uso em outro agente**.

---

## ⚙️ Estrutura do Projeto

### 🧩 Criação do Agente no AI Foundry

* Definição da ação principal: **Intérprete de Código (sem arquivos)**;
* Testes iniciais via **Playground**, validando comandos e interação com o modelo.

### 🧾 Processamento da Legenda

* Download da legenda via **site externo** (com alerta de segurança sobre riscos de vírus);
* Envio do arquivo `.srt` para o agente realizar **limpeza e estruturação**;
* Retorno do resultado em formato **JSON**.

### 🧪 Execução e Testes no Playground

* Execução de comandos para validar **resumos automáticos e consultas por minuto**;
* Registro de **tentativas de download** e **correções com apoio técnico**.

### 🧱 Problemas Identificados

* 🚫 Links de download não funcionais dentro do Foundry;
* 📦 Tamanho excessivo de alguns arquivos JSON;
* 🧩 Necessidade de ajustes manuais em caminhos e formatações.

---

## 🚀 MVP Futuro

O **MVP proposto** amplia o projeto para um **fluxo 100% automatizado**, permitindo:

* 🎬 Conversão do vídeo e **extração automática da transcrição** (sem depender de site externo);
* 🧾 Geração direta do **resumo e metadados** (título, tópicos e segmentos);
* 💾 Disponibilização do resultado em **JSON, PDF e TXT** para download seguro;
* 🤖 Integração com **repositório de conhecimento interno** e **API para consultas via chatbot corporativo**.

Essa versão funcionará como um **prova de conceito (PoC)** para futuras integrações entre **Azure AI Foundry, DevOps e repositórios internos**.

---

## ⚠️ Observações de Processamento da IA

Durante o processamento das transcrições, foram observadas pequenas distorções automáticas:

* ✏️ *Cecilia Dutra* foi interpretada como *Ceclilia Duta*;
* 🧩 *Azure* e outros termos técnicos foram reescritos parcialmente em algumas respostas.

Essas variações foram mantidas para preservar a resposta original retornada pelo agente e **não comprometem o entendimento geral do conteúdo**.

---

## 📚 Referências

* 🔗 **Plataforma:** [Azure AI Foundry](https://ai.azure.com/foundry)
* 📘 **Documentação:** [Microsoft Learn - AI Foundry](https://learn.microsoft.com/azure/ai-foundry)
* 💬 **Apoio Técnico:** ChatGPT (assistência durante execução e solução de erros)
* 🎓 **Fonte do desafio:** Material acadêmico do curso *Inteligência Artificial Aplicada*

---

## 🧠 Motivação Pessoal

A ideia para este projeto surgiu para **facilitar os estudos** e **otimizar o tempo de aprendizado**.
Com tantos vídeos no curso, o agente ajuda a **localizar rapidamente as informações necessárias**, **gerar resumos** e até **criar quizzes** para reforçar o aprendizado de forma prática e dinâmica.

---

## 🏁 Conclusão

Este projeto demonstra o potencial do **Azure AI Foundry** na **criação de agentes inteligentes customizados**, integrando **interpretação de vídeos, processamento de linguagem natural e automação de fluxos**.
Mesmo com limitações técnicas pontuais, o experimento representa uma **base sólida para evolução do MVP completo** e uma **ferramenta de apoio educacional** inovadora — transformando o aprendizado em uma experiência interativa e inteligente.

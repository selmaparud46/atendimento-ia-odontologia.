# ⚙️ Demonstração de Fluxo de Automação Back-end para Clínicas

Este repositório contém um **protótipo funcional de automação** desenvolvido estritamente para fins de estudo, testes e demonstração técnica de arquitetura de back-end. 

---

## 🔍 O que este projeto demonstra (A lógica de bastidores)

O objetivo deste fluxo é simular como funciona a engrenagem de um atendimento automatizado por trás de uma interface, operando da seguinte forma:
1. **Entrada de Dados:** Recebe uma simulação de mensagem do usuário.
2. **Processamento:** Gerencia a árvore de decisão e o fluxo da conversa.
3. **Registro:** Valida as informações coletadas (Nome, Telefone) e simula o salvamento desses dados estruturados em uma linha do Google Sheets.

---

## 🛠️ Tecnologias Utilizadas no Laboratório

* **n8n:** Utilizado como a ferramenta de orquestração de nós para desenhar e rodar a lógica dos bastidores.
* **Google Sheets:** Utilizado como banco de dados simulado para registrar os dados de teste enviados durante a validação do fluxo.

---

## 📁 Como Importar o Protótipo

Este arquivo `.json` é o esqueleto da automação. Para carregá-lo no seu ambiente de testes'.
1. Faça o download do arquivo presente neste repositório.
2. Acesse o seu painel do n8n.
3. Crie um fluxo em branco, clique no menu de configurações `...` e escolha **"Import from file"**.

---
**Desenvolvido por Selma Parud**  
*Estudante de Análise e Desenvolvimento de Sistemas (ADS)*


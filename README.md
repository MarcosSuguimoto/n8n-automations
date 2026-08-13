# 🚀 n8n Automations Library

Coleção de workflows de automação desenvolvidos no **n8n**, focados em integração de APIs REST, manipulação de JSON, validação de dados via JavaScript e resiliência de serviços.

---

## 📂 Workflows Disponíveis

### 1. 💡 Buscador de Curiosidades (`v1.1.1`)
* **Arquivo:** `workflows/01-buscador-de-curiosidades/workflow-curiosidades.json`
* **Descrição:** Chatbot interativo que recebe comandos do usuário, valida a intenção por palavras-chave em JS, busca fatos aleatórios na *Useless Facts API* e traduz para PT-BR via *MyMemory API*.
* **Recursos:** Chat Trigger, tratamento de erros (*Retry on Fail*), delimitadores visuais (*Sticky Notes*).

### 2. 🐾 Fatos sobre Animais
* **Arquivo:** `workflows/02-fatos-animais/workflow-fatos-animais.json`
* **Descrição:** Fluxo automatizado focado em busca e processamento de informações e curiosidades sobre o reino animal.

---

## 🛠️ Como Importar no seu n8n

1. Escolha o fluxo desejado dentro da pasta `workflows/`.
2. Baixe ou copie o conteúdo do arquivo `.json`.
3. No seu painel do **n8n**, clique em **Workflows** > **Import from File** (ou cole o conteúdo do JSON diretamente no canvas).
4. Ative o workflow!

---

## 👤 Autor
Desenvolvido por **Marcos Suguimoto**

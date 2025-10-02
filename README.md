# 🤖 Projeto: Workflow N8N - Secretário Pessoal com Google Calendar  

## 📌 Descrição  
Este projeto implementa um **assistente pessoal automatizado** usando o **N8N**.  
O workflow conecta a **IA do Google Gemini** ao **Google Calendar**, permitindo gerenciar eventos diretamente por chat.  
A memória usada é a **memória simples do N8N**, garantindo que o assistente mantenha o contexto da conversa.  

### Funcionalidades principais:  
- 📅 Criar eventos no Google Calendar  
- ✏️ Atualizar eventos existentes  
- 🔍 Consultar compromissos na agenda  
- ❌ Excluir eventos do calendário  
- 🧠 Memória simples para manter o contexto das interações  

---

## 🛠️ Tecnologias utilizadas  
- [N8N](https://n8n.io/) – Automação de fluxos  
- [Google Gemini](https://ai.google/) – Inteligência artificial para interpretação de linguagem natural  
- [Google Calendar API](https://developers.google.com/calendar) – Gerenciamento de eventos  
- Memória simples do N8N  

---

## ⚙️ Estrutura do Workflow  
1. **When chat message received** → Captura mensagens do usuário  
2. **AI Agent (Google Gemini + Memória simples)** → Interpreta os comandos do usuário  
3. **Google Calendar Nodes** → Criar, atualizar, listar e excluir eventos conforme solicitado  

---

## 📷 Captura do Workflow  
![SECRETARIOPESSOAL](https://github.com/user-attachments/assets/9df16b2d-c621-453b-81ff-1a65afde04a3)

---

## 🚀 Como usar  
1. Configure sua instância do **N8N**  
2. Conecte sua conta do **Google Calendar** via credenciais do N8N  
3. Configure o **Google Gemini Chat Model** como modelo de IA  
4. Execute o workflow e comece a conversar com o assistente  

---

## 📌 Autor  
Projeto desenvolvido por **Heytor Alves**  

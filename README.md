# AMV AI STUDIO
Installazione e configurazione di AMV AI STUDIO

Benvenuto. Questo repository è la **knowledge base ufficiale** per l’utilizzo di **AMV AI STUDIO**: AI operativa, prompting evoluto e automazione via Python per MasterSap 4U, in un ambiente tecnico controllato e pensato per utenti consapevoli.  
AMV AI STUDIO **non** è un assistente generico / copilota universale: ogni suggerimento o script va **analizzato, modificato e validato** dall’ingegnere.  
Il sistema opera **integralmente in locale** e l’eventuale uso di motori AI esterni avviene **solo tramite MCP locale**, senza accessi diretti non controllati a servizi cloud.  

---

## 🔀 Scegli il tuo percorso

### Percorso A — Voglio usare **AMV AI STUDIO** (Chatbot ↔ MCP ↔ MasterPy)
Se vuoi collegare un client AI (Claude Desktop o OpenAI Codex) a MasterSap tramite MCP locale e MasterPy, parti da qui:

1) **Overview (cos'è AMV AI STUDIO)**  
   👉 `docs/01-Overview_AI_Studio.md`

2) **Installazione e configurazione MCP / Bridge (Claude Desktop / Codex)**  
   👉 https://github.com/AMV-Team/AMV-AI-STUDIO/blob/main/docs/02-Guida_Installazione.pdf

3) **Risoluzione problemi (FAQ)**  
   👉 `docs/03-Troubleshooting_FAQ.md`

> Cos’è il Bridge: MasterSAIBridge è un server MCP (Model Context Protocol) per Windows che collega Claude Desktop e OpenAI Codex alle funzionalità di MasterSap; l’AI può generare, salvare ed eseguire script Python MS senza uscire dalla chat.

---

### Percorso B — Voglio scrivere o riusare **script Python per MasterPy** (Python MS)
Se ti interessa soprattutto lo scripting (comandi MS, esempi, community di script):

Vai al repository scripts (esempi, regole, community):  
   👉 **MasterSap Python Scripts**: https://github.com/AMV-Team/MasterSap_Python_Scripts

---

## 🧠 Modello mentale (in una riga)
**Client AI (Claude/Codex)** → **MCP locale** → **MasterSAIBridge** → **MasterPy** → **MasterSap (con progetto aperto)**

---

## 🤝 Community & supporto
- Per domande sugli **script** e confronto con la community: usa Discussions nel repo degli script.
  https://github.com/AMV-Team/MasterSap_Python_Scripts/discussions 
- Per problemi di **installazione/configurazione AI Studio** e connessione MCP: usa questo repository (docs + FAQ).

> Nota: la community è uno spazio collaborativo e non sostituisce il supporto ufficiale AMV.

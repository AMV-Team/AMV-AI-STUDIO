# 01 — Overview AMV AI STUDIO (da zero)

## 1. Cos’è (e cosa NON è)
- AI operativa + automazione via Python per MasterSap 4U
- Non è un assistente generico / copilota universale
- Ogni output va analizzato, modificato e validato dall’ingegnere
- Target: utenti esperti, workflow non standard, attività ripetitive

## 2. Architettura in 30 secondi
- Sistema integrale in locale
- Motori AI esterni: solo via MCP locale
- Nessun accesso diretto non controllato a servizi cloud
- Componenti: MasterSap + MasterPy + MasterSAIBridge + client AI (Claude/Codex)

## 3. Prerequisiti minimi (checklist)
- MasterSap in esecuzione con un progetto aperto (preferibilmente vuoto)
- Un client AI: Claude Desktop oppure OpenAI Codex
- MasterSAIBridge installato (se incluso nella suite/installer)

## 4. Primo test “connessione OK”
- Verifica che il server MCP risulti “running” nel client AI
- Avvia una richiesta semplice (“genera uno script… salva e apri in editor”)
- Conferma che lo script venga salvato come ms.py in Documenti

## 5. Primo test “esecuzione OK”
- Richiedi l’esecuzione dello script in MasterSap tramite MasterPy (PyConsole4MS)
- Verifica che il modello compaia nella scena (ridisegno finale)

## 6. Regole di sicurezza/qualità (1 schermata)
- Controllo locale e tracciabilità
- Attenzione alle “allucinazioni”: errori sintattici o comandi impropri
- Se lo script fallisce: correggi ms.py e riparti da progetto pulito (undo/nuovo progetto)

## 7. Dove chiedere aiuto
- Problemi di connessione/configurazione: vedi 04-Troubleshooting_FAQ
- Script ed esempi: repo MasterSap_Python_Scripts + Discussions

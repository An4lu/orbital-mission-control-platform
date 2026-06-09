# Fluxo 1 - Recebimento de Alerta Crítico

Início

↓

Receber Evento

↓

Validar Evento

↓

Evento Crítico?

├── Não
│   ↓
│ Registrar Evento
│   ↓
│ Fim

└── Sim
    ↓
Gerar Alerta
    ↓
Notificar Operador
    ↓
Abrir Incidente
    ↓
Registrar Log
    ↓
Fim

---

# Fluxo 2 - Predição de Falhas

Início

↓

Coletar Histórico

↓

Executar IA

↓

Risco > 80% ?

├── Não
│   ↓
│ Encerrar Processo

└── Sim
    ↓
Gerar Alerta Preventivo
    ↓
Registrar Recomendação
    ↓
Notificar Engenheiro
    ↓
Fim

# Casos de Uso

## Atores

1. Operador de Missão

<img width="477" height="656" alt="operador" src="https://github.com/user-attachments/assets/372364d1-548b-427f-991c-01cc1002e8b1" />
   
3. Engenheiro de Sistemas

<img width="570" height="606" alt="engenheiro" src="https://github.com/user-attachments/assets/99ebeb66-23d2-4944-8a69-947683131e9f" />

4. Administrador

<img width="509" height="588" alt="admin" src="https://github.com/user-attachments/assets/48a7a8d1-e34b-4ed5-b1be-5d2ae6d698d3" />

5. IA de Bordo

<img width="482" height="544" alt="ia" src="https://github.com/user-attachments/assets/3f3ab2d1-1581-4317-8bf6-aaf8b1d057a6" />

---

## UC001
Autenticar Usuário

## UC002
Monitorar Telemetria

## UC003
Consultar Histórico

## UC004
Registrar Evento

## UC005
Gerenciar Alertas

## UC006
Receber Notificação Crítica

## UC007
Monitorar Sensores

## UC008
Monitorar Módulos

## UC009
Executar Predição de Falhas

## UC010
Gerar Relatórios

## UC011
Consultar Eventos

## UC012
Gerenciar Usuários

## UC013
Auditar Operações

## UC014
Visualizar Dashboard

---

## Relacionamentos Include

Monitorar Telemetria
<<include>>
Monitorar Sensores

Gerenciar Alertas
<<include>>
Registrar Evento

Gerar Relatórios
<<include>>
Consultar Eventos

---

## Relacionamentos Extend

Receber Notificação Crítica
<<extend>>
Gerenciar Alertas

Executar Predição de Falhas
<<extend>>
Monitorar Módulos

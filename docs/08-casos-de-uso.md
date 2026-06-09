# Casos de Uso

## Atores

1. Operador de Missão
2. Engenheiro de Sistemas
3. Administrador
4. IA de Bordo

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

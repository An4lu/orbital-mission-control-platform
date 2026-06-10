# Diagrama de Classes

## Classe Abstrata User

### Atributos

- id
- name
- email
- password

### Métodos

- login()
- logout()

---

## MissionOperator

### Métodos

- monitorMission()
- openIncident()

---

## SystemEngineer

### Métodos

- analyzeFailures()
- approveMaintenance()

---

## Administrator

### Métodos

- createUser()
- updateUser()
- removeUser()

---

## Mission

### Atributos

- id
- name
- status

---

## Sensor

### Atributos

- id
- type
- status

### Métodos

- collectData()

---

## TelemetryData

### Atributos

- timestamp
- value

---

## Alert

### Atributos

- severity
- description

### Métodos

- generate()

---

## AIEngine

### Métodos

- predictFailure()

---

## Report

### Métodos

- generatePDF()
- generateCSV()

---

# Relacionamentos

User <|-- MissionOperator

User <|-- SystemEngineer

User <|-- Administrator

Mission *-- Sensor

Sensor *-- TelemetryData

AIEngine --> Alert

Mission --> Report

MissionOperator --> Alert

SystemEngineer --> AIEngine

---


# Diagrama

<img width="1191" height="1330" alt="diagrama-de-classe" src="https://github.com/user-attachments/assets/1e6f47fa-235e-4a3c-b0b0-59583456d60c" />


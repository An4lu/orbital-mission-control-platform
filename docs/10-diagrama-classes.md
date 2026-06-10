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

<img width="482" height="544" alt="ia" src="https://github.com/user-attachments/assets/3f3ab2d1-1581-4317-8bf6-aaf8b1d057a6" />

## 📌 Sobre o Projeto de Triagem

Sistema que simula um processo de triagem hospitalar, classificando pacientes em níveis de urgência.

### 🔍 Entradas
- Nome do paciente  
- Idade  
- Frequência cardíaca (FC)  
- Pressão arterial (PA)  
- Nível de dor (0 a 10)  
- Sintoma principal  

---

### ⚙️ Regras de Classificação

#### 🔴 Vermelho (Imediato)
- FC > 150  
- PA < 80  
- Dor = 10  

---

#### 🟠 Laranja (Muito urgente)
- Dor ≥ 8  
- Sintoma grave isolado  

---

#### 🧮 Cálculo do Score

- FC > 100 ou FC < 55 → +3  
- PA < 100 → +2  
- Dor ≥ 5 → +2  
- Idade > 65 → +2  

---

#### 🟡 / 🟢 Classificação Final
- Score ≥ 7 → **Amarelo (urgente)**  
- Score < 7 → **Verde (não urgente)**  

---

### 📤 Saída
- Classificação do paciente  
- Registro na fila  
- Notificação médica  
- Geração de relatório  

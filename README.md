# <img src="https://img.icons8.com/color/48/000000/industrial-scales.png" width="32"/> STICKFRAN · Gerenciador de Pulso

> **Precisão matemática para o chão de fábrica.** > Sistema de cálculo para espuladeiras baseado na Espiral de Arquimedes, eliminando o erro da regra de três.

---

### 🔴 O Problema
O enrolamento de fio é uma função **quadrática**, não linear. 
* **Erro Sistemático:** A regra de três ignora o crescimento radial.
* **Desperdício:** Pulsos incorretos geram sobras de fio caro ou falta de material.
* **Processo Manual:** Falta de rastreabilidade entre turnos.

### 🟢 A Solução
Utilizamos modelagem matemática exata para garantir eficiência total.

* **Modelo de Arquimedes:** Representação real do acúmulo de fio.
* **Inversão via Bhaskara:** Cálculo de pulsos com precisão de 6 casas decimais.
* **Divisão em Lotes:** Separação automática entre Lote 1 (Cheias) e Lote 2 (Parciais).

---

### 🧪 Modelo Matemático
O comprimento $m(x)$ após $x$ pulsos é definido por:
$$m(x) = C_0 \cdot K \cdot x + \left( \frac{\Delta C \cdot K}{2 \cdot P_{max}} \right) \cdot x^2$$

Para encontrar os pulsos necessários a partir da metragem, o sistema resolve a raiz positiva da equação quadrática:
$$P = \lceil x \rceil$$

---

### ⚙️ Funcionalidades (Módulos)
| Status | Módulo | Descrição |
| :--- | :--- | :--- |
| 🛠️ | **Setup de Produção** | Interface visual Fotek para programação rápida. |
| 📋 | **Fichas Técnicas** | Cadastro de modelos (Branco e Vermelho). |
| 👥 | **Gestão de Acesso** | Perfis para Admin, PCP e Operador. |
| 💾 | **Backup Seguro** | Exportação de dados em JSON e CSV. |
| 📱 | **PWA Offline** | Funciona sem internet no galpão industrial. |

---

### 💻 Stack Tecnológica
![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white)
![](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

---

### 👤 Desenvolvedor
**Leonardo** — Analista de PCP e Estudante de Desenvolvimento de Software Multiplataforma (DSM/FATEC).

---
[⚡ Acessar Sistema](https://lpmpcpstk-source.github.io/Gerenciador-de-Pulsos-para-Espuladeira-STK/)
[⚡ Guia de Calculo](https://youtu.be/ANEJausdvAk)

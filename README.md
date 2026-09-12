<div align="center">

# 🧮 Calculadora

**Calculadora Android** desenvolvida em Java com interface responsiva em GridLayout.

[![Android](https://img.shields.io/badge/Android-24%2B-green?logo=android)](https://developer.android.com)
[![Java](https://img.shields.io/badge/Java-8-blue?logo=openjdk)](https://www.java.com)
[![Gradle](https://img.shields.io/badge/Gradle-8.0-02303A?logo=gradle)](https://gradle.org)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

</div>

---

## 📸 Layout

```
┌─────────────────────────┐
│                         │
│                       0 │  Display
│                         │
├──────┬──────┬──────┬────┤
│  7   │  8   │  9   │  × │
├──────┼──────┼──────┼────┤
│  4   │  5   │  6   │  ÷ │
├──────┼──────┼──────┼────┤
│  1   │  2   │  3   │  − │
├──────┼──────┼──────┼────┤
│  0   │  CE  │  =   │  + │
└──────┴──────┴──────┴────┘
```

---

## ✨ Funcionalidades

| Operação | Descrição |
|----------|-----------|
| ➕ Soma | `+` |
| ➖ Subtração | `−` |
| ✖️ Multiplicação | `×` |
| ➗ Divisão | `÷` (com proteção div/0) |
| 🔄 Limpar | `CE` reseta tudo |

---

## 🛠️ Tech Stack

| Componente | Tecnologia |
|------------|-----------|
| Linguagem | Java |
| UI | `GridLayout` + `LinearLayout` |
| SDK | Android API 24+ (min) / 33 (target) |
| Build | Gradle 8.0 + AGP 8.1.0 |
| Dependências | AppCompat, Material Design, ConstraintLayout |

---

## 🚀 Como Rodar

```bash
# Clone
git clone https://github.com/alvarossantos/calculadora.git
cd calculadora

# Build debug
./gradlew assembleDebug

# APK gerado em:
# app/build/outputs/apk/debug/app-debug.apk
```

---

## 📁 Estrutura do Projeto

```
app/src/main/
├── java/br/edu/uemg/calculadora/
│   └── MainActivity.java      # Lógica da calculadora
├── res/layout/
│   └── activity_main.xml       # Layout GridLayout 4×4
└── AndroidManifest.xml
```

---

## 📋 Changelog

| Versão | Mudança |
|--------|---------|
| `v1.1` | Fix: listeners para todos os botões, implementação de mult/div, layout migrado para GridLayout |
| `v1.0` | Versão inicial com soma e subtração |

---

<div align="center">

Feito com ☕ por [Alvaro Santos](https://github.com/alvarossantos)

</div>

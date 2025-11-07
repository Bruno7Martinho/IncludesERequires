# 📚 Apostila 5 - Inclusão de Arquivos (include e require)

## 🎯 Objetivo
Modularizar o código PHP através da inclusão de arquivos externos, compreendendo as diferenças entre `include`, `require`, `include_once` e `require_once`.

## 📖 Conceitos Principais

### ⚡ Include vs Require
- **`include`**: Gera um **aviso (E_WARNING)** se o arquivo não for encontrado, mas permite que o script continue
- **`require`**: Gera um **erro fatal (E_COMPILE_ERROR)** se o arquivo não for encontrado, interrompendo o script

### 🔄 Include_once vs Require_once
- **`include_once`** e **`require_once`**: Previnem a inclusão múltipla do mesmo arquivo, evitando erros de "redeclaration"

## 🏗️ Estrutura do Projeto
/projeto
├── /templates

│ ├── cabecalho.php

│ └── rodape.php

├── /config

│ └── conexao.php

├── index.php

├── sobre.php

└── style.css


# ⏱️ Projeto Pomodoro Timer, mas... [O que é a técnica Pomodoro?](https://pt.wikipedia.org/wiki/T%C3%A9cnica_pomodoro)


Repositório com o projeto Pomodoro Timer desenvolvido durante o curso [JavaScript e TypeScript do básico ao avançado JS/TS (Udemy)](https://www.udemy.com/course/curso-de-javascript-moderno-do-basico-ao-avancado).

---

## 🧠 Conteúdo abordado no repositório

- Fundamentos da técnica Pomodoro
- Organização modular de pastas e arquivos
- Manipulação de tempo com setInterval e useEffect
- Criação e uso de custom hook (useInterval)
- Componentes reutilizáveis (Timer, Button, PomodoroTimer)
- Estilização com CSS tradicional
- Execução de áudios ao iniciar e encerrar ciclos
- Estruturação dos ciclos de trabalho e descanso
- Cálculo de tempo total trabalhado

---

## 📁 Estrutura do projeto

- `src/`: diretório principal do código-fonte.
- `components/`: componentes reutilizáveis da interface (timer, button, pomodoro-timer).
- `hooks/`: contém o hook personalizado `useInterval`.
- `sounds/`: arquivos de áudio tocados no início e fim dos ciclos.
- `utils/`: funções auxiliares para lidar com tempo (conversão e formatação).
- `App.tsx`: componente principal da aplicação.
- `index.tsx`: ponto de entrada da aplicação React.
- `.eslintrc.js`, `.editorconfig`, `.gitignore`, `tsconfig.json`, etc.: arquivos de configuração.

---

## ⚙️ Tecnologias utilizadas

- TypeScript
- React
- HTML
- CSS
- ESLint
- Node.js (para gerenciamento de dependências com NPM)

---

## ▶️ Como executar a aplicação

1. No terminal, instale as dependências com:

```bash
npm install
```

2. Em seguida, inicie a aplicação:

```bash
npm start
```
3. A aplicação será aberta automaticamente em: http://localhost:3000

---

## 📌 Observações

- Esta aplicação segue o método Pomodoro, separando períodos de foco e descanso.
- O projeto foi desenvolvido com foco em prática de TypeScript com React, aplicando componentização, hooks personalizados, lógica de controle de tempo e boas práticas de desenvolvimento front-end.


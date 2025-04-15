---

# UniHack

**UniHack** é uma plataforma de *Capture The Flag* (CTF) gamificada, desenvolvida com o objetivo de fomentar a cultura de segurança da informação entre os alunos da **UNICEPLAC**. Através de desafios práticos, rankings, conquistas e níveis, a plataforma incentiva o aprendizado contínuo em um ambiente competitivo e colaborativo.

## 🎯 Objetivos

- Promover o estudo de cybersecurity por meio de desafios técnicos e práticos.
- Estimular a formação de equipes e o trabalho colaborativo entre estudantes.
- Integrar uma plataforma de CTF à grade extracurricular da instituição.
- Oferecer uma ferramenta escalável para organização de eventos internos de segurança.

## ⚙️ Tecnologias Utilizadas

- **Back-end:** Java + Spring Boot  
- **Front-end:** React.js  
- **Banco de Dados:** PostgreSQL  
- **Containerização:** Docker

## 🧩 Funcionalidades Previstas

- Sistema de autenticação de usuários e perfis personalizados.
- Painel administrativo para criação e gerenciamento de desafios.
- Sistema de pontuação com ranking individual e por equipe.
- Conquistas e níveis baseados no desempenho dos participantes.
- Página com histórico de competições e estatísticas.

## 🚀 Como Executar o Projeto

> Requisitos: Docker e Docker Compose instalados

```bash
git clone https://github.com/seu-usuario/unihack.git
cd unihack
docker-compose up --build
```

> A interface estará disponível em: `http://localhost:3000`  
> A API estará disponível em: `http://localhost:8080`

## 🛠️ Estrutura do Projeto

```
unihack/
├── backend/        # Projeto Spring Boot
├── frontend/       # Projeto React
├── docker/         # Configurações de containerização
└── docs/           # Documentação técnica
```

## 📚 Contribuindo

Este projeto é mantido por estudantes da UNICEPLAC, mas colaborações são bem-vindas!

1. Fork este repositório.
2. Crie uma branch (`git checkout -b feature/nova-funcionalidade`).
3. Faça suas alterações e *commits*.
4. Envie um *pull request*.

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

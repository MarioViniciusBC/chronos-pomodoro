# Chronos

Aplicação web baseada na técnica Pomodoro, desenvolvida como Single Page Application (SPA) utilizando React 19 e TypeScript. O projeto tem como objetivo aplicar boas práticas de arquitetura front-end, organização modular de componentes e gerenciamento de estado escalável, com foco em produtividade e qualidade de código.

---

## Demonstração

Em breve disponível via deploy.

---

## Tecnologias Utilizadas

- React 19  
- TypeScript  
- Tailwind CSS  
- Hooks personalizados  
- Context API (ou outro gerenciador de estado utilizado)  
- Vite (ou ferramenta de build utilizada)

---

## Arquitetura e Organização

O projeto foi estruturado com foco em separação de responsabilidades e escalabilidade.

Principais decisões arquiteturais:

- Componentização modular
- Separação entre lógica e apresentação
- Uso de hooks personalizados para encapsular regras de negócio
- Tipagem forte com TypeScript
- Organização de pastas orientada a domínio

Exemplo de estrutura:

```
src/
 ├── components/
 ├── hooks/
 ├── contexts/
 ├── pages/
 ├── utils/
 └── types/
```

---

## Funcionalidades

- Temporizador configurável (tempo de foco e pausa)
- Controle de ciclos (foco / descanso curto / descanso longo)
- Persistência de dados no localStorage
- Histórico de sessões
- Interface responsiva
- Modo escuro (opcional)

---

## Conceitos Aplicados

- Gerenciamento de estado global
- Controle de efeitos colaterais com hooks
- Manipulação precisa de tempo com setInterval
- Boas práticas de tipagem
- Organização limpa e legível de código
- Separação entre camada de UI e lógica de negócio

---

## Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de:

- Consolidar fundamentos de aplicações SPA modernas
- Praticar arquitetura front-end escalável
- Aplicar boas práticas com React e TypeScript
- Construir um projeto sólido para portfólio técnico

---

## Possíveis Evoluções

- Integração com backend (ex: API REST com NestJS)
- Autenticação de usuários
- Dashboard com estatísticas de produtividade
- Persistência em banco de dados
- Versão com Next.js utilizando App Router e Server Components

---

## Como Executar o Projetos

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/chronos-pomodoro.git

# Instalar dependências
npm install

# Rodar em ambiente de desenvolvimento
npm run dev
```

---

## Autor

Mário Vinícius  
Graduando em Engenharia de Software  
Interesse em arquitetura de software, inteligência artificial e desenvolvimento full-stack.
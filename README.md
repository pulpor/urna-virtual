# Urna Eletrônica Virtual

Simulador de urna eletrônica desenvolvido como projeto educacional para o curso **Técnico em Informática para Web** do **SESC SENAC 2026**.

---

## Sobre o projeto

Recria a interface e o fluxo de votação de uma urna eletrônica brasileira, com candidatos configuráveis, registro de votos no servidor e painel administrativo.

## Funcionalidades

- Digitação de número com teclado físico ou virtual
- Exibição de foto, nome e partido do candidato
- Votos em branco e nulo
- Registro de votos persistido em `votos.json` (servidor)
- Painel admin com contagem em tempo real e opção de zerar
- Download do arquivo de votos em JSON

## Configuração de candidatos

Edite o arquivo `src/candidatos.json` para definir os candidatos:

```json
[
  {
    "numero": "13",
    "nome": "Nome do Candidato",
    "partido": "PARTIDO",
    "vice": "Nome do Vice",
    "foto": "https://url-da-foto.jpg"
  }
]
```

## Como rodar

```bash
npm install
npm run dev
```

Acesse `http://localhost:5173`.

## Tecnologias

- [TanStack Start](https://tanstack.com/start) — framework SSR/React
- [TailwindCSS 4](https://tailwindcss.com) — estilização
- [TypeScript](https://www.typescriptlang.org) — tipagem estática
- [Vite](https://vite.dev) — bundler

---

**Autor:** Leonardo Pulpor — Professor de Programação  
**Turma:** 3º Ano · Técnico em Informática para Web · SESC SENAC · 2026

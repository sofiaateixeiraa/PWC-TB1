# PWC-TB1 - Umbrella Corporation

Trabalho Prático 1 da unidade curricular **Programação Web Cliente**  
Curso de Desenvolvimento de Software - ISTEC  
Ano Letivo 2025/2026  
Docente Mário Amorim

---

## Descrição

Website fictício desenvolvido em HTML5 e CSS3 para a empresa **Umbrella Corporation**, inspirada no universo Resident Evil. O site é composto por 5 páginas interligadas com navegação consistente, um ficheiro CSS externo partilhado e elementos semânticos estruturados.

---

## Funcionalidades

- Navegação entre páginas com indicação da página ativa
- Apresentação institucional da empresa com estatísticas e missão
- Listagem da equipa com tabela de colaboradores e níveis de acesso
- Página de projetos de investigação com hiperligações externas
- Formulário de contacto com validação HTML e JavaScript

---

## Estrutura do projeto

```
umbrella-corp/
├── index.html        # Página inicial
├── sobre.html        # Sobre a empresa
├── equipa.html       # Equipa e estrutura organizacional
├── projetos.html     # Programas de investigação
├── contacto.html     # Formulário de contacto
├── style.css         # Folha de estilos externa
└── images/           # Imagens utilizadas no site
```

---

## Páginas

**Index.html:** Hero section, estatísticas corporativas, grid de divisões da empresa e call-to-action de recrutamento.  
**Sobre.html:** Apresentação institucional com secções de identidade, missão e valores corporativos.  
**Equipa.html:** Cards de membros da liderança, tabela com `<thead>`, `<tbody>` e `<tfoot>`, e grid de divisões operacionais.  
**Projetos.html:** Cards dos programas de investigação com badges de estado, níveis de autorização e hiperligações externas para a Resident Evil Wiki.  
**Contacto.html:** Formulário com campos de texto, `<select>`, `<textarea>` e validações via `required`, `minlength`, `type` e JavaScript.

---

## Tecnologias

- HTML5
- CSS3
- JavaScript (validação de formulário)
- [Google Fonts](https://fonts.google.com/) — Orbitron, Share Tech Mono, Rajdhani

---

## Grupo

| Nome            | Número  | Páginas responsável              |
| --------------- | ------- | -------------------------------- |
| Sofia Teixeira  | 2025013 | `equipa.html`, `projetos.html`   |
| Gonçalo Pereira | 2024001 | `sobre.html`, `contacto.html`    |
| Ambos           | ————    | `index.html`, `style.css`        |
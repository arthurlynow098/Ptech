<p align="center">
  <img src="assets/project-animal.png" alt="Emblema de Ptech" width="144" height="144">
</p>

<h1 align="center">Ptech</h1>

<p align="center">Registro da trajetória acadêmica, palestras e atividades do programa P-Tech.</p>

<p align="center">
  <img src="https://img.shields.io/badge/P--Tech-C52E36?style=flat-square" alt="P-Tech">
  <img src="https://img.shields.io/badge/HTML-24272E?style=flat-square" alt="HTML">
  <img src="https://img.shields.io/badge/CSS-24272E?style=flat-square" alt="CSS">
</p>

<p align="center"><a href="#visão-geral">Visão geral</a> &nbsp;·&nbsp; <a href="#recursos">Recursos</a> &nbsp;·&nbsp; <a href="#como-executar">Como executar</a></p>

---

## Visão geral

A interface combina folhas de estilo dedicadas (ptech.css e style.css), galeria organizada por datas de eventos (img/P-tech/) e versão publicada na nuvem via **Netlify**.

## Recursos

| Recurso | Como funciona |
|---|---|
| Linha do tempo de eventos | Registro visual e descritivo dos encontros técnicos com empresas parceiras (Tegra, Eduzz, etc.) de abril/2023 a setembro/2024. |
| Galeria cronológica (img/P-tech) | Acervo fotográfico e certificados organizados em subpastas datadas do (1) ao (11). |
| Estilização modular | Separação entre estilos estruturais (style.css) e componentes específicos da vitrine P-Tech (ptech.css). |
| Hospedagem contínua | Publicação acessível online em [ptecharthur.netlify.app](https://ptecharthur.netlify.app/). |

<details>
<summary>Arquitetura</summary>

```mermaid
flowchart LR
    A["Acervo P-Tech 2023-2024"] --> B["Galeria Cronológica img/P-tech"]
    B --> C["Página Principal HTML5"]
    D["ptech.css & style.css"] --> C
    C --> E["Deploy Público · Netlify"]
```

</details>

<details>
<summary>Estrutura do repositório</summary>

```text
Ptech/
├── assets/
│   └── project-animal.png          Emblema do projeto
├── Portfolio-PTECH-main/
│   ├── css/                                Folhas de estilo ptech.css e style.css
│   ├── img/P-tech/                         Registros dos 11 encontros e workshops (2023–2024)
│   ├── index.html                          Página principal do portfólio P-Tech
│   └── README.md
└── README.md
```

</details>

## Como executar

1. Acesse a versão online em **[ptecharthur.netlify.app](https://ptecharthur.netlify.app/)** ou clone o repositório:
   ```bash
   git clone https://github.com/arthurlynow098/Ptech.git
   ```
2. Abra Portfolio-PTECH-main/index.html diretamente no navegador.

---

<p align="center">
  <a href="https://github.com/arthurlynow098">GitHub</a> &nbsp;·&nbsp;
  <a href="https://arthurentsev.vercel.app/">Portfólio</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/entsevarthur/">LinkedIn</a>
</p>

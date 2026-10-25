# Felipe Ronni — Portfólio

Portfólio pessoal de **Felipe Ronni**, desenvolvedor de sites, sistemas web e soluções digitais com apoio de inteligência artificial.

🔗 **Online:** https://feliperonni.github.io/Meu-portfolio/

## Sobre o projeto

Esta é a segunda versão do portfólio, reconstruída do zero com foco em design minimalista, boa hierarquia visual e leitura confortável em qualquer tela. O site é uma página única, sem frameworks e sem etapa de build.

## Seções

| Seção | Conteúdo |
| --- | --- |
| Início | Apresentação, título principal e botões de ação |
| Sobre | Texto de apresentação e dados básicos |
| Habilidades | Tecnologias atuais separadas das que estão em aprofundamento |
| Projetos | IFRA Digital e Sistema RDC |
| Processo | As quatro etapas de abordagem de um projeto |
| Contato | Links para GitHub e LinkedIn |

## Projetos em destaque

1. **IFRA Digital** — presença digital, desenvolvimento de sites e gestão de tráfego pago. Site: https://ifradgcompany.com/
2. **Sistema RDC** — aplicação web personalizada para um projeto empresarial real. Projeto privado: o portfólio exibe apenas uma imagem do dashboard, sem link de acesso.

## Tecnologias

- HTML5
- CSS3 (variáveis CSS, Grid e Flexbox)
- JavaScript puro (sem dependências)
- Fontes Inter e Space Grotesk, via Google Fonts, com fontes do sistema como alternativa

## Recursos

- Layout responsivo, de celulares pequenos a monitores grandes
- Menu de navegação com versão para celular
- Indicador da seção atual durante a rolagem
- Rolagem suave entre seções
- Animações de entrada leves, desativadas para quem usa `prefers-reduced-motion`
- Ano do rodapé gerado dinamicamente
- Imagem do dashboard embutida no próprio arquivo, sem requisições extras

## Estrutura

```
.
├── index.html   # página completa (HTML, CSS e JS no mesmo arquivo)
└── README.md
```

## Como executar localmente

Não há dependências para instalar. Há duas opções:

1. Abrir o `index.html` diretamente no navegador; ou
2. Subir um servidor local simples:

```bash
python -m http.server 8000
```

Depois, acessar http://localhost:8000.

## Como publicar no GitHub Pages

1. Salvar o arquivo da página como `index.html` na raiz do repositório.
2. No GitHub, abrir **Settings → Pages**.
3. Em **Build and deployment**, escolher **Deploy from a branch**, selecionar a branch principal e a pasta `/ (root)`.
4. Salvar e aguardar a publicação.

## Como personalizar

- **Textos e links:** todo o conteúdo está no próprio `index.html`, dentro das tags `<section>`.
- **Cor de destaque:** alterar a variável `--accent` no início do bloco `<style>`.
- **Novo projeto:** duplicar um bloco `<article class="proj rv">` na seção de projetos e ajustar número, título, descrição e links.
- **Imagem de projeto:** substituir o `src` da tag `<img>` por um arquivo local, como `assets/projeto.webp`, ou por uma imagem embutida em base64.

## Privacidade

O Sistema RDC é um projeto empresarial privado. Não publique credenciais, dados de clientes ou telas que exponham informações confidenciais neste repositório.

## Contato

- GitHub: https://github.com/feliperonni
- LinkedIn: https://www.linkedin.com/in/felipe-ronni-3a7015381/

---

Desenvolvido com dedicação e curiosidade por tecnologia.

# 📌 Dev Notes

Aplicação web de notas rápidas para o dia a dia de quem programa. Dá para criar, pesquisar, fixar, duplicar e remover notas, além de exportar tudo em CSV — direto no navegador, sem dependências ou etapa de build.

## ✨ Funcionalidades

- **Adicionar notas** pelo campo "O que deseja anotar?".
- **Pesquisar** notas pelo texto, pelo campo de busca no topo.
- **Fixar notas** (📌): a nota fixada fica em destaque e vai para o início da lista.
- **Duplicar notas** com o ícone que aparece ao passar o mouse sobre o cartão.
- **Remover notas** com o ícone ✕ que aparece ao passar o mouse sobre o cartão.
- **Exportar para CSV** com o botão "Exportar CSV".
- **Tema escuro** com as notas organizadas em cartões.

## 🎬 Demonstração

https://github.com/user-attachments/assets/275f807e-00c1-4ee2-801b-0e2a1d8d15f8

## 🛠️ Tecnologias

- **HTML5** — estrutura da página
- **CSS3** — estilização e layout
- **JavaScript (vanilla)** — lógica e manipulação do DOM
- **[Bootstrap Icons](https://icons.getbootstrap.com/)** — ícones (carregados via CDN)

## 📁 Estrutura do projeto

```
Dev-Notes/
├── index.html   # Estrutura da aplicação
├── styles.css   # Estilos
└── scripts.js   # Lógica da aplicação
```

## 🚀 Como executar

Não é necessário instalar nada.

1. Clone o repositório:

   ```bash
   git clone https://github.com/jotapefp/Dev-Notes.git
   ```

2. Entre na pasta do projeto:

   ```bash
   cd Dev-Notes
   ```

3. Abra o arquivo `index.html` no navegador (duplo clique ou, se preferir, use uma extensão como o *Live Server* do VS Code).

> Os ícones dependem de conexão com a internet, pois o Bootstrap Icons é carregado por CDN.

## 🧭 Como usar

1. Digite a nota no campo **"O que deseja anotar?"** e clique em **+** para adicioná-la.
2. Clique no ícone de **pino** para fixar a nota.
3. Passe o mouse sobre um cartão para ver as opções de **duplicar** e **remover** (✕).
4. Digite no campo **"Busque por uma nota"** para encontrar notas pelo texto.
5. Clique em **Exportar CSV** para baixar suas notas.

## 🔮 Próximos passos

Ideias para evoluir o projeto:

- [ ] Persistir as notas com `localStorage`
- [ ] Permitir editar o conteúdo das notas
- [ ] Adicionar categorias ou etiquetas
- [ ] Melhorar a responsividade para telas pequenas
- [ ] Publicar online com GitHub Pages

## 👤 Autor

**João Paulo Pinheiro Ferraz de Arruda**

- GitHub: [@jotapefp](https://github.com/jotapefp)
- LinkedIn: [joao-paulo-pinheiro-ferraz-de-arruda](https://www.linkedin.com/in/joao-paulo-pinheiro-ferraz-de-arruda)

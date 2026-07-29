# 🌋 Vulkan

Site institucional sobre vulcões, desenvolvido como trabalho da disciplina **Programação Web**. O projeto apresenta o que são vulcões, suas partes e tipos, além de curiosidades, filmes e documentários relacionados ao tema.

🔗 **Acesse a página publicada:** (https://igorcosta94.github.io/vulkan/)

## 🔗 Páginas

| Página | Arquivo | Conteúdo |
|---|---|---|
| Início | `index.html` | O que são vulcões e suas partes |
| Vulcões | `vulcoes.html` | Tipos de vulcão (escudo, cone de escória, estratovulcão, caldeira) |
| Curiosidades | `curiosidades.html` | Grandes erupções e supervulcões |
| Filmes | `midias.html` | Filmes de ficção sobre vulcões |
| Documentários | `documentarios.html` | Documentários sobre erupções reais |

## 🛠️ Tecnologias

- **HTML5** semântico (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`)
- **CSS3** puro, sem frameworks — variáveis CSS, Flexbox e Grid
- Menu responsivo mobile via checkbox hack (funciona por clique/toque, sem depender de `:hover`)
- Google Fonts (Montserrat + Inter)

## 📁 Estrutura do projeto

```
vulkan/
├── index.html
├── vulcoes.html
├── curiosidades.html
├── midias.html
├── documentarios.html
├── css/
│   └── style.css        # folha de estilos única do site
├── imagens/              # fotos e thumbnails de vídeos
└── musicas/               # trilha sonora de fundo (mp3)
```

## ▶️ Como executar

Não há dependências nem build. Basta abrir o arquivo `index.html` diretamente no navegador, ou servir a pasta com qualquer servidor estático:

```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```

Depois acesse `http://localhost:8000`.

## 🚀 Publicação (GitHub Pages)

Para publicar (ou atualizar) a versão online do site:

1. Faça o push do projeto para o GitHub.
2. No repositório, vá em **Settings → Pages**.
3. Em **Source**, selecione a branch `main` e a pasta `/root`.
4. Salve e aguarde alguns instantes — o GitHub gera a URL no formato:
   ```
   https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/
   ```
5. Atualize o link no topo deste README com a URL gerada.

## ✅ Boas práticas aplicadas

- HTML válido, sem IDs duplicados e sem tags não fechadas
- Imagens com atributo `alt` para acessibilidade
- Navegação sticky com indicação da página ativa
- Layout responsivo (mobile, tablet e desktop)
- Uma única folha de estilos compartilhada entre as páginas, com variáveis CSS para cores e espaçamentos

## 👥 Autoria

Trabalho acadêmico desenvolvido para a disciplina de Programação Web.

## 📄 Licença

Uso educacional. Imagens, trilhas sonoras e vídeos referenciados pertencem aos seus respectivos autores/detentores de direitos.

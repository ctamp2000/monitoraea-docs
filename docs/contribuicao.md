# 🤝 Como contribuir com a documentação

Esta documentação foi construída para ser colaborativa, utilizando GitHub + MkDocs.  
Qualquer pessoa do time pode contribuir de forma simples 🙂

---

## 📁 Onde editar

Toda a documentação fica na pasta: docs/

Cada página é um arquivo `.md` (Markdown).

Exemplos:

- `index.md` → página inicial
- `api.md` → documentação de APIs

---

## ✍️ Como editar

1. Abra o projeto no VS Code
2. Navegue até a pasta `docs/`
3. Crie ou edite arquivos `.md`

Exemplo de Markdown:

```markdown
# Título

## Subtítulo

- item 1
- item 2
```

👉 Dica:

- Use **Ctrl + S** para salvar

## 👀 Como visualizar localmente

### Pelo terminal do VS Code:

1. Vá em **Terminal → New Terminal**
2. Execute:

```
bash id="n6h0dx"

python -m mkdocs serve

Depois acesse no navegador:

http://127.0.0.1:8000

O site atualiza automaticamente conforme você salva os arquivos.

```

## 💾 Como salvar as alterações (VS Code)

Pela interface gráfica:

1. Clique no ícone de Source Control (raminho)
2. Veja os arquivos alterados
3. Digite uma mensagem no campo de commit
4. Clique em Commit
5. Clique em Sync Changes ou Push

## Ou pelo terminal

git add .

git commit -m "descrição da alteração"

git push

## 🌐 Como publicar no site

No terminal do VS Code:

python -m mkdocs gh-deploy

## 🧭 Organização da documentação

- Um arquivo por assunto
- Nomes claros (ex: configuracao.md, api.md)
- Evitar conteúdos duplicados
- Manter informações sempre atualizadas

## ⚙️ Menu e navegação

O menu do site é controlado pelo arquivo:

mkdocs.yml

Exemplo:

nav:

- Home: index.md
- API: api.md
- Como contribuir: contribuicao.md

## 👥 Boas práticas de colaboração

- Sempre revisar antes de publicar
- Escrever de forma clara e objetiva
- Pensar em quem vai ler (ex: novos membros do time)
- Atualizar a documentação junto com mudanças no sistema

## 🚀 Resumo do fluxo

- Editar arquivos em docs/
- Visualizar com mkdocs serve
- Commit e push no GitHub
- Publicar com mkdocs gh-deploy

## Qualquer dúvida, é só falar com o time 🙂

```

```

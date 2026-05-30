# Como Publicar No GitHub

Como o GitHub CLI nao esta instalado nesta maquina, o repositorio foi preparado localmente.

## Opcao 1: Publicar pelo site do GitHub

1. Acesse https://github.com/new
2. Crie um repositorio publico chamado `EcoTetrisJogo`.
3. Nao marque para criar README, `.gitignore` ou licenca, porque esses arquivos ja estao prontos aqui.
4. Abra o terminal dentro da pasta `EcoTetrisJogo-repo`.
5. Rode:

```bash
git remote add origin https://github.com/SEU_USUARIO/EcoTetrisJogo.git
git branch -M main
git push -u origin main
```

Troque `SEU_USUARIO` pelo seu usuario do GitHub.

## Opcao 2: Publicar com GitHub Desktop

1. Abra o GitHub Desktop.
2. Escolha `File > Add local repository`.
3. Selecione a pasta `EcoTetrisJogo-repo`.
4. Clique em `Publish repository`.
5. Marque como `Public`.
6. Publique.

## Prints recomendados

Para deixar o README mais bonito, tire prints do celular ou do emulador e coloque em:

```text
docs/screenshots/
```

Nomes recomendados:

- `menu.png`
- `modo-normal.png`
- `modo-dificil.png`
- `game-over.png`
- `tutorial.png`


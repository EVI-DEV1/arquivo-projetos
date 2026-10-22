# Como publicar o novo README

## 1. Ajustar 2 links no README.md
- `SEU_LINKEDIN` -> o final da URL do seu LinkedIn (ex.: `eliane-vitoriano`)
- `SEU_USUARIO_DIO` -> seu usuário na DIO (ou apague o badge da DIO)

## 2. Subir para o repositório EVI-DEV1/EVI-DEV1
No PowerShell, dentro desta pasta:

```
git clone https://github.com/EVI-DEV1/EVI-DEV1.git temp
Copy-Item README.md temp\README.md -Force
Copy-Item .github temp\.github -Recurse -Force
cd temp
git add .
git commit -m "Novo README de perfil com animações"
git push
```

Alternativa sem terminal: cole o conteúdo do README.md pelo editor do GitHub
e crie o arquivo `.github/workflows/snake.yml` pelo site também ("Add file").

## 3. Ativar a cobrinha (animação das contribuições)
1. No repositório EVI-DEV1/EVI-DEV1: **Settings > Actions > General**
2. Em *Workflow permissions* marque **Read and write permissions** e salve
3. Aba **Actions** > "Gerar cobrinha das contribuicoes" > **Run workflow**
4. Em ~1 minuto a branch `output` é criada e a cobrinha aparece no perfil

Depois disso ela se atualiza sozinha todo dia.

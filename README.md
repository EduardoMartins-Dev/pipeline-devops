# frontend-devops-b-2026

Projeto simples de front-end usado como exercício de DevOps.

Descrição
- Arquivos HTML estáticos, imagens e CSS.
- Contém um workflow de CI em `.github/workflows/pipeline.yaml`.

Como usar
1. Abra `index.html` ou `site-faculdade/index.html` no navegador.

Git (exemplo)
```powershell
# Inicializar e enviar ao GitHub
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/SEU_USUARIO/SEU_REPO.git
git push -u origin main
```

CI
- O pipeline de CI está em `.github/workflows/pipeline.yaml`.

Observações
- Projeto sem dependências; apenas arquivos estáticos.
- Corrija o arquivo de workflow se houver chaves duplicadas em `on:`.
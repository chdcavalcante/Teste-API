# Desafio de Testes de API - GitHub (Postman)

Este repositório contém uma coleção Postman para testar o fluxo completo de criação, consulta, criação de issue, exclusão e verificação de repositório na API do GitHub.

## Como executar

1. **Importe a coleção e o ambiente no Postman**
   - Baixe os arquivos `.postman_collection.json` e `.postman_environment.json` deste repositório.
   - No Postman, clique em “Importar” e selecione os arquivos.

2. **Configure as variáveis do ambiente**
   - Preencha as variáveis `token_github` (seu token pessoal do GitHub) e `usuario_github` (seu usuário do GitHub).

3. **Execute o teste**
   - Abra o request principal da coleção e clique em “Send”.
   - Os resultados dos testes aparecerão na aba “Test Results”.

---

- O fluxo pode ser executado várias vezes sem erro.
- O token precisa ter permissões de repositório no GitHub.

# Wally Web Map

Painel web estatico para visualizar os dispositivos Wally no mapa.

Arquivo principal para hospedagem:

`index.html`

## Publicar no GitHub Pages

1. Crie um repositorio no GitHub, por exemplo `wally-web`.
2. Envie os arquivos desta pasta `web` para o repositorio.
3. No GitHub, abra `Settings` > `Pages`.
4. Em `Build and deployment`, selecione `Deploy from a branch`.
5. Escolha a branch `main` e a pasta `/ (root)`.
6. Salve e aguarde a URL `https://SEU_USUARIO.github.io/wally-web/`.

Antes de usar, execute `supabase_locations.sql` no Supabase para garantir que a policy de `SELECT` esteja ativa.

Observacao: esta pagina le localizacoes reais do Supabase usando a chave publishable. Evite deixar o repositorio/site publico se voce nao quiser expor o mapa.

# map-images
Repositório para publicar as imagens do Mapa do jogo Tibia.

## Publicação

A branch `main` só muda por pull request. Só quem tem permissão de escrita ou administração neste repositório passa na checagem e pode dar o merge. O merge é o que publica. O Tibia Wiki lê esta branch; ao entrar na `main`, o cache do jsDelivr dos arquivos alterados é limpo.

Um pull request que apaga um `.png` ou o `tiles.json` não passa. Substituir um arquivo no mesmo caminho pode. Push direto na `main`, force push e apagar a branch também não.

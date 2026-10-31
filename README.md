# Vitor Quirino · site
Site público: https://quirinotattoo.github.io/
Hospedagem pelo GitHub Pages. Textos, estilos, fotos e avaliações são guardados no Firebase Firestore.

## Acesso do artista
No rodapé, abra **Acesso do artista**. O primeiro acesso usa o e-mail autorizado do Vitor. Crie uma senha e confirme o e-mail pelo link enviado. Depois, o login abre o editor dentro do próprio site. Salvar atualiza o conteúdo para os visitantes conectados.

Fotos são reduzidas no navegador e guardadas em documentos separados do Firestore. Elas são carregadas conforme aparecem na tela. Assim, não é preciso ativar Firebase Storage ou cobrança para publicar fotos. As avaliações enviadas pelos clientes ficam públicas, e o artista pode removê-las pelo editor.

Publicações públicas do Instagram podem ser incorporadas colando os links escolhidos pelo artista. A exibição depende do Instagram permitir a incorporação daquele post.

## Hospedagem e alterações
O repositório é público e hospedado pelo GitHub Pages. Conteúdo atualizado pelo editor aparece sem um novo deploy. Mudanças no código do site são publicadas em um commit do GitHub.

O e-mail permitido deve ser o do artista. As regras do Firestore ficam no arquivo firestore.rules para facilitar revisão e manutenção.

Descrição:
Este script gera uma playlist IPTV extraindo links de streaming .m3u8 de um site especificado. Ele faz o scraping do site para obter categorias e posts associados, identifica links de streaming e recupera imagens destacadas. Os links resultantes são organizados por categoria e salvos em um arquivo de playlist no formato padrão M3U, que pode ser utilizado em players de IPTV Funciona em qualquer site Wordpress

Principais Funcionalidades:

Obtém categorias e posts a partir de uma API REST.
Extrai links .m3u8 diretamente do conteúdo dos posts.
Converte links embutidos especiais no formato .m3u8.
Extrai imagens destacadas dos posts e as associa aos canais.
Salva a playlist em um arquivo iptv_playlist.m3u.


Como Funciona:

Obter Categorias: O script solicita as categorias de um endpoint da API REST.
Obter Posts por Categoria: Ele recupera os posts de cada categoria.
Extrair Links de Streaming: Identifica links .m3u8 diretamente e converte links embutidos especiais.
Encontrar Imagens Destacadas: Extrai imagens para usar como logotipos dos canais, se disponíveis.
Gerar Playlist: Cria um arquivo M3U com os links extraídos, categorizados e rotulados.
Uso: Execute o script, e ele criará automaticamente uma playlist M3U chamada iptv_playlist.m3u no diretório atual. A playlist pode ser utilizada em qualquer player de IPTV compatível.

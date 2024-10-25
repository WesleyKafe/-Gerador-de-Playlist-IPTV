# Descrição:

Este script gera uma playlist IPTV extraindo links de streaming .m3u8 de um site especificado. Ele faz o scraping do site para obter categorias e posts associados, identifica links de streaming e recupera imagens destacadas. Os links resultantes são organizados por categoria e salvos em um arquivo de playlist no formato padrão M3U, que pode ser utilizado em players de IPTV Funciona em qualquer site Wordpress

## :heavy_exclamation_mark:  Pré-requisitos:

Python: Certifique-se de ter o Python 3.6 ou superior instalado no seu sistema.


## :book: Instalações necessárias:

requests: Usada para fazer requisições HTTP.
re: Esta é uma biblioteca nativa do Python para trabalhar com expressões regulares.
json: Também é uma biblioteca nativa do Python para manipulação de JSON.


## :book: Instruções de Instalação:
No terminal ou prompt de comando, execute o seguinte comando para instalar o pacote requests:


``` bash```

``` pip install requests```




###  Bibliotecas padrão:

As bibliotecas re e json são embutidas no Python, então você não precisa instalá-las separadamente.

### Resumo: 

* Após instalar o Python, certifique-se de executar pip install requests para instalar a única biblioteca externa necessária para rodar o script.

## :book: Principais Funcionalidades:

Obtém categorias e posts a partir de uma API REST.
Extrai links .m3u8 diretamente do conteúdo dos posts.
Converte links embutidos especiais no formato .m3u8.
Extrai imagens destacadas dos posts e as associa aos canais.
Salva a playlist em um arquivo iptv_playlist.m3u.


## :book: Como Funciona:

Obter Categorias: O script solicita as categorias de um endpoint da API REST.
Obter Posts por Categoria: Ele recupera os posts de cada categoria.
Extrair Links de Streaming: Identifica links .m3u8 diretamente e converte links embutidos especiais.
Encontrar Imagens Destacadas: Extrai imagens para usar como logotipos dos canais, se disponíveis.
Gerar Playlist: Cria um arquivo M3U com os links extraídos, categorizados e rotulados.
Uso: Execute o script, e ele criará automaticamente uma playlist M3U chamada iptv_playlist.m3u no diretório atual. A playlist pode ser utilizada em qualquer player de IPTV compatível.

## :octocat: Creditos
1. @WesleyKafe - Desenvolvedor do Codigo

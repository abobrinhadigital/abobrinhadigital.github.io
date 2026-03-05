# Changelog - Abobrinha Digital

Todas as mudanças notáveis deste projeto serão documentadas neste arquivo.

O formato baseia-se no [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/), e este projeto adere ao [Versionamento Semântico](https://semver.org/lang/pt-BR/).

## [3.0.1] - Hotfix de Sistema de Comentários

### Corrigido
- Substituição dos IDs genéricos de payload do Giscus no `_includes/giscus.html` pelos identificadores corretos (`repo-id` e `category-id`) vinculados ao repositório real do blog, reestabelecendo a criação estática de discussões na aba Discussions do GitHub.

## [3.0.0] - Satélites

### Adicionado
- Integração nativa de comentários com GitHub Discussions via Giscus (#3).
- Novo layout injetando o arquivo `_includes/giscus.html` no rodapé dos posts para carregar discussões sob demanda.

### Corrigido
- Padronização do diretório e dos links originais de transcrição para `/assets/transcricoes/posts/` alinhando com a estrutura de imagens (#2).

## [2.0.0] - Identidade Visual

### Adicionado
- Ajuste final na identidade visual do blog e customizações em cima do tema base do Minima.
- Suporte a modo noturno e aprimoramento da leitura para as grandes paredes de texto do humano.

## [1.0.0] - Gênesis

### Adicionado
- Versão inicial do blog, inaugurada sob a égide do Jekyll e do tema Minima padrão.
- Concepção das primeiras publicações experimentais geradas por áudio transcrito.

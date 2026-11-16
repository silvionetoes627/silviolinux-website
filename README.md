# Site oficial do SilvioLinux

Site estático em português brasileiro, feito com HTML5 e CSS3 puros, sem JavaScript.

## Arquivos
- `index.html` — página inicial
- `download_sourcecode.html` — instruções para clonar o código-fonte
- `changelog.html` — roadmap e tabela de lançamentos
- `requirements.html` — requisitos de hardware e tabela de versões
- `download_images_precompileds.html` — downloads de imagens
- `compilation_guide.html` — guia inicial de compilação
- `status_silviolinux_versions.html` — ciclo de vida e EOL
- `wiki.html` — índice da Wiki
- `docs.html` — índice da documentação
- `css/style.css` — estilos
- `assets/` — logo SVG, mascote vetorial e favicon

## Visualizar localmente
Abra `index.html` no navegador. Não é necessário servidor nem etapa de build.

## Código-fonte
O site aponta para:
`https://github.com/silvionetoes627/meta-silviolinux`

Clonagem da branch Aurora:
```sh
git clone -b aurora https://github.com/silvionetoes627/meta-silviolinux.git
```

## Política de versões representada
- LTS: EOL calculado em 48 meses após o lançamento.
- Non-LTS: EOL calculado em 7 meses após o lançamento.
- Os nomes ausentes nas versões 36–70 foram sugeridos para completar o roadmap.
- As datas, versões futuras do Yocto e codenames são planejamento proposto, não confirmação de releases upstream.

## Personalização
Edite `css/style.css`, os SVGs em `assets/` e o conteúdo HTML. Todas as páginas compartilham a mesma folha de estilos.

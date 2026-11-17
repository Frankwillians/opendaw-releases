# OpenDAW — downloads oficiais

Estação de trabalho de áudio gratuita para gravar, editar, mixar e exportar músicas, no navegador ou no desktop.

Este repositório reúne **somente os instaladores e pacotes oficiais** do OpenDAW. O código-fonte do aplicativo e do site é mantido em repositórios privados.

**[Baixar a versão mais recente](https://github.com/Frankwillians/opendaw-releases/releases/latest)** · **[Abrir a versão web](https://opendawproject.vercel.app)** · **[Site oficial](https://opendaw-site.vercel.app)**

## Downloads

Abra a [última release](https://github.com/Frankwillians/opendaw-releases/releases/latest) e escolha um arquivo na seção **Assets**:

| Sistema | Arquivo | Uso |
| --- | --- | --- |
| Windows 10/11, 64 bits | `OpenDAW-Setup-<versão>.exe` | Instalador com escolha da pasta e atalhos. |
| Linux, x86_64 | `OpenDAW-<versão>-x86_64.AppImage` | Executável sem instalação tradicional. |
| Debian/Ubuntu, amd64 | `OpenDAW-<versão>-amd64.deb` | Pacote para instalação pelo gerenciador do sistema. |
| Linux, x64 | `OpenDAW-<versão>-x64.tar.gz` | Arquivos do aplicativo para extrair em uma pasta. |

A distribuição para Windows contém apenas o **Setup**, sem pacote Portable. Não há pacote para macOS; nesse sistema, use a versão web.

Os arquivos **Source code (zip/tar.gz)** adicionados automaticamente pelo GitHub não são o aplicativo nem o seu código-fonte: contêm apenas os arquivos deste repositório de distribuição.

## Instalação

### Windows

Baixe o Setup nos Assets e execute o instalador. O executável ainda não possui assinatura digital, por isso o Windows pode exibir um aviso. Confira a origem do download e, quando disponível nas notas da release, o SHA-256 do arquivo. Não é necessário desativar o antivírus.

### Linux

- **AppImage:** nas propriedades do arquivo, permita sua execução e abra-o. A disponibilidade de FUSE e de bibliotecas do sistema pode variar conforme a distribuição.
- **DEB:** abra o pacote com o gerenciador de software da sua distribuição.
- **TAR.GZ:** extraia todo o conteúdo antes de iniciar o executável `opendaw-desktop`.

## Recursos e compatibilidade

O OpenDAW inclui gravação e edição de áudio, timeline, mixer, efeitos internos, instrumentos MIDI, piano roll, sequenciador de bateria, modelagem de amplificadores NAM e exportação WAV/MP3.

Plugins **VST2/VST3 nativos e saída ASIO são exclusivos do aplicativo para Windows**. A versão Linux e a versão web utilizam WebAudio e as entradas disponíveis pelo sistema/navegador; não carregam os plugins nativos do Windows.

## Atualizações

No aplicativo ou na versão web, abra **Ajuda → Verificar atualizações**. O atualizador consulta as releases públicas deste repositório, sem precisar de conta ou token do GitHub.

No Windows instalado, o aplicativo pode baixar e iniciar o novo Setup. Na web, no Linux e nas antigas versões em pasta portátil, o caminho é a página da release para download manual.

**Se você usa a versão 1.2.1 ou anterior**, baixe uma versão atual pelo site ou por este repositório uma vez: essas versões antigas ainda usam o canal anterior de atualizações.

Antes de atualizar, salve seu trabalho e faça uma cópia dos projetos importantes. O [histórico de versões](https://github.com/Frankwillians/opendaw-releases/releases) reúne as notas de cada lançamento.

## Apoie o OpenDAW

O apoio é voluntário e não altera os recursos disponíveis no programa.

- [Apoiar pelo Ko-fi](https://ko-fi.com/opendawproject)
- [Conhecer a seção de apoio no site](https://opendaw-site.vercel.app/#doacoes)

A partir da versão 1.2.3, o atalho **Ajuda → Apoiar o OpenDAW** também está disponível no aplicativo e na versão web, abrindo o site em uma aba ou navegador separado.

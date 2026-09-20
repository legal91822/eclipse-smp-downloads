# Eclipse SMP — downloads oficiais

Este repositório público será usado para distribuir **somente arquivos de cliente revisados** do Eclipse Launcher.

**Status atual: publicação pendente.** O instalador Windows e o pacote de mods ainda não foram publicados nem testados como release pública. Não compartilhe este repositório como se já contivesse um launcher pronto.

## Parâmetros confirmados

- Minecraft: 1.20.1
- Forge: 47.4.10
- Servidor: `eclipserealm.mcserver.us:9150` (alternativo: `169.155.126.46:9150`)
- Distribuição/atualização: próprias do Eclipse Launcher, sem AutoModpack.

## Antes da primeira release

1. Conferir as licenças e a permissão de redistribuição dos mods e recursos de terceiros; retirar os itens que não podem ser redistribuídos diretamente.
2. Gerar **novo Seed somente com arquivos do cliente**, sem tokens, dados de conta, sessões, logs, saves, chaves ou arquivos pessoais. Confirmar Forge 47.4.10 em todos os manifestos e no launcher.
3. Verificar SHA-256 e testar extração, instalação e inicialização em um Windows limpo.
4. Compilar e testar o instalador Windows; só publicar depois de validar o fluxo completo.
5. Criar uma GitHub Release e anexar apenas os artefatos finais revisados. O endereço dos assets da Release poderá alimentar a configuração de download do launcher.

**Não envie os três arquivos RAR originais da instância para este repositório:** eles podem conter dados pessoais e arquivos que não devem ser distribuídos.

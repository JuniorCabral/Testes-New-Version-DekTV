# DekTV — builds de teste (pre-producao)

Canal **nao oficial**. Use so para validar com clientes antes do upgrade de producao.

## Versao atual: **1.0.117** (version_code **118**)

### Download direto (Release)

Abra a release: https://github.com/JuniorCabral/Testes-New-Version-DekTV/releases/tag/v1.0.117

| Dispositivo | Arquivo |
|---|---|
| Fire TV / stick Amazon | `dektv-player-firetv.apk` |
| Google TV / Android TV | `dektv-player-googletv.apk` |
| Celular Android | `dektv-player-mobile.apk` |

### Como instalar na TV (Downloader / sideload)

1. Na TV, abra o **Downloader** e cole a URL do APK da tabela acima (link na pagina da Release → botao direito / copiar link do asset).
2. Instale por cima do app atual (mesmo package).
3. Abra o DekTV e teste: **canais ao vivo em tela cheia** e **filme/serie (VOD)** com double-tap seek.

### O que validar neste build

- Video live fullscreen sem tela branca/lavada
- Botao voltar no player (touch)
- VOD: double-tap esquerda/direita = -10s / +10s

### Manifests

`manifests/` aponta `download_url` absoluto para os assets desta release.
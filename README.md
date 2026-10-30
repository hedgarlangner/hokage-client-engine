# Hokage Client Engine

Motor do cliente novo do **Hokage Online**, baseado no
[OTClient Redemption](https://github.com/mehah/otclient) (commit `1fcea26`, 24/10/2026, licença MIT, ver `LICENSE`).

Este repositório tem **só o código C++** do motor. Sprites, mapa, módulos Lua e
dados do jogo ficam no repositório privado do projeto.

## Builds

Cada envio para `main` compila Windows, macOS (Apple Silicon) e Linux no GitHub
Actions e publica os pacotes em **Releases → nightly**:

- `hokage-client-windows.zip`
- `hokage-client-macos.zip`
- `hokage-client-linux.zip`

No projeto, o `BAIXAR_MOTOR.bat` baixa a versão de Windows.

## Mudanças em relação ao Redemption

- CI enxuta (Linux, Windows CMake Release e macOS) + publicação automática do nightly.

O README original do Redemption está em `README-UPSTREAM.md`.

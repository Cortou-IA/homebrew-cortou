# homebrew-cortou

Tap Homebrew do [Cortou](https://ocortou.com.br) para macOS (beta, Apple Silicon).

## Instalar

```bash
brew tap cortou-ia/cortou
brew install --cask --no-quarantine cortou
```

## Atualizar

```bash
brew update
brew upgrade --cask cortou
```

O `.app` não é assinado/notarizado ainda (fase beta) — o `--no-quarantine` evita o bloqueio
do Gatekeeper na primeira abertura. Só use em máquinas de confiança (é o próprio time/testers
internos do Cortou).

Detalhes completos, troubleshooting e o processo de publicar uma nova versão:
`Cerebro/02-Produtos/Cortou/Produto-Dev/Homebrew-Tap-Mac.md` (interno).

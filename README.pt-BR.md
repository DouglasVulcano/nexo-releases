<p align="center">
  <img src="assets/icon.png" width="96" alt="Nexo" />
</p>

<h1 align="center">Nexo</h1>

<p align="center">
  Um ambiente de desenvolvimento desktop para o <a href="https://github.com/anthropics/claude-code">Claude Code</a>.
  <br/>
  Windows · Linux · macOS, com tratamento de primeira classe para <a href="https://learn.microsoft.com/windows/wsl/">WSL</a>.
</p>

<p align="center">
  <a href="https://github.com/DouglasVulcano/nexo-releases/releases/latest"><img src="https://img.shields.io/github/v/release/DouglasVulcano/nexo-releases?label=vers%C3%A3o&color=f2762e" alt="Última versão" /></a>
  <a href="https://github.com/DouglasVulcano/nexo-releases/releases"><img src="https://img.shields.io/github/downloads/DouglasVulcano/nexo-releases/total?label=downloads&color=47848F" alt="Downloads" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/licen%C3%A7a-MIT-blue.svg" alt="Licença MIT" /></a>
  <img src="https://img.shields.io/badge/plataformas-Windows%20%C2%B7%20Linux%20%C2%B7%20macOS-555" alt="Plataformas" />
</p>

<p align="center">
  <a href="README.md">English</a> · <strong>Português</strong>
</p>

---

> Este é o canal oficial de **distribuição** do Nexo. Aqui ficam apenas os instaladores e os metadados de atualização automática.

## Sobre

O **Nexo** é um ambiente de desenvolvimento desktop pensado para quem trabalha com o [Claude Code](https://github.com/anthropics/claude-code). Ele reúne, em um só lugar, o fluxo de quem desenvolve com agentes de IA: rápido, integrado e multiplataforma, com tratamento de primeira classe para [WSL](https://learn.microsoft.com/windows/wsl/) no Windows.

## Download e instalação

Baixe o instalador da sua plataforma na **[página de releases](https://github.com/DouglasVulcano/nexo-releases/releases/latest)**.

### Windows

1. Baixe o `Nexo-Setup-x.y.z.exe` e execute.
2. Na primeira execução, o SmartScreen pode exibir "editor desconhecido" (o app ainda não é assinado): clique em **Mais informações → Executar assim mesmo**.

### Linux

- **AppImage** (recomendado, com atualização automática):
  ```bash
  chmod +x Nexo-x.y.z.AppImage
  ./Nexo-x.y.z.AppImage
  ```
- **Debian/Ubuntu (.deb):**
  ```bash
  sudo dpkg -i nexo_x.y.z_amd64.deb
  ```

### macOS

1. Abra o `Nexo-x.y.z.dmg` e arraste o Nexo para Aplicativos.
2. Como o app ainda não é notarizado, na primeira vez clique com o botão direito → **Abrir** e confirme.

## Atualizações automáticas

O Nexo se **atualiza sozinho**: ao abrir, ele checa por novas versões aqui no repositório de releases e avisa quando há uma disponível. Você decide quando **baixar** e, depois, **reiniciar** para aplicar; nada é instalado às escondidas. (Windows e Linux AppImage têm atualização automática; pacotes `.deb` são atualizados pelo gerenciador do sistema.)

## Suporte

Encontrou um problema ou tem uma sugestão? Abra uma **[issue](https://github.com/DouglasVulcano/nexo-releases/issues)** neste repositório.

## Licença

Distribuído sob a licença [MIT](LICENSE).

---

<sub>Nexo é um projeto independente e não é afiliado à Anthropic. "Claude" e "Claude Code" são marcas da Anthropic.</sub>

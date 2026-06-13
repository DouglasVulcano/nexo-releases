<p align="center">
  <img src="assets/icon.png" width="96" alt="Nexo" />
</p>

<h1 align="center">Nexo</h1>

<p align="center">
  Gerenciador desktop para o ecossistema local do <a href="https://github.com/anthropics/claude-code">Claude Code</a>:
  sessões, skills, servidores MCP, terminal embutido, controle de versão por aba e um gerenciador de bancos de dados.
  <br/>
  Windows · Linux · macOS, com tratamento de primeira classe para <a href="https://learn.microsoft.com/windows/wsl/">WSL</a>.
</p>

<p align="center">
  <a href="https://github.com/DouglasVulcano/nexo-releases/releases/latest"><img src="https://img.shields.io/github/v/release/DouglasVulcano/nexo-releases?label=vers%C3%A3o&color=f2762e" alt="Última versão" /></a>
  <a href="https://github.com/DouglasVulcano/nexo-releases/releases"><img src="https://img.shields.io/github/downloads/DouglasVulcano/nexo-releases/total?label=downloads&color=47848F" alt="Downloads" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/licen%C3%A7a-MIT-blue.svg" alt="Licença MIT" /></a>
  <img src="https://img.shields.io/badge/plataformas-Windows%20%C2%B7%20Linux%20%C2%B7%20macOS-555" alt="Plataformas" />
</p>

---

> Este é o canal oficial de **distribuição** do Nexo. Aqui ficam apenas os instaladores e os metadados de atualização automática. O código-fonte é mantido em repositório privado.

## Índice

- [O que é o Nexo](#o-que-é-o-nexo)
- [Download e instalação](#download-e-instalação)
- [Atualizações automáticas](#atualizações-automáticas)
- [Funcionalidades](#funcionalidades)
- [Requisitos](#requisitos)
- [Suporte](#suporte)
- [Licença](#licença)

## O que é o Nexo

O **Nexo** reúne, em um único aplicativo desktop, tudo o que o [Claude Code](https://github.com/anthropics/claude-code) espalha pelo sistema de arquivos da sua máquina. Ele varre as instalações do Claude Code (no host e dentro de cada distro WSL no Windows), indexa **sessões**, **skills** e **servidores [MCP](https://modelcontextprotocol.io)**, e oferece um **terminal embutido** para retomar qualquer sessão no ambiente correto com um clique. Inclui ainda **controle de versão por aba** (estilo VS Code) e um **gerenciador de bancos de dados** que pode dar contexto de banco ao próprio Claude Code.

## Download e instalação

Baixe o instalador da sua plataforma na **[página de releases](https://github.com/DouglasVulcano/nexo-releases/releases/latest)**.

### Windows

1. Baixe o `Nexo-Setup-x.y.z.exe` e execute.
2. Na primeira execução, o SmartScreen pode exibir "editor desconhecido" (o app ainda não é assinado): clique em **Mais informações → Executar assim mesmo**.
3. O instalador verifica se você tem **Node.js** e **Git** e, se faltarem, oferece instalá-los (são usados pelo Claude Code e pelas ferramentas de banco). Você pode aceitar ou pular.

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

O Nexo se **atualiza sozinho**: ao abrir, ele checa por novas versões aqui no repositório de releases e avisa quando há uma disponível. Você decide quando **baixar** e, depois, **reiniciar** para aplicar - nada é instalado às escondidas. (Windows e Linux AppImage têm atualização automática; pacotes `.deb` são atualizados pelo gerenciador do sistema.)

## Funcionalidades

- **Sessões** - varre `~/.claude/projects/**` lendo só o cabeçalho de cada arquivo; filtros, busca, favoritos, fork, histórico de transcript e retomada no ambiente certo (Windows, WSL ou local).
- **Workspaces** - agrupamentos coloridos que filtram sessões e terminais, com regras de auto-atribuição por caminho.
- **Console** - terminais multi-aba (PowerShell, WSL ou shell nativo) com split panes, busca, zoom, dock flutuante e restauração de layout.
- **Controle de versão por aba** - painel multi-repositório com staged/unstaged, diff lado a lado, editor de arquivo, troca de branch, commit/push/pull/fetch e geração de mensagem de commit por IA.
- **Skills e MCP** - listagem e instalação de skills (GitHub/template) e de servidores MCP, com galerias dos catálogos oficiais.
- **Bancos de dados** - conexões PostgreSQL, MySQL, SQLite e SQL Server (com túnel SSH e modo somente-leitura), editor SQL, navegação relacional e a opção de **vincular um banco à sessão** para dar contexto ao Claude Code.

## Requisitos

- **Windows** 10/11 (com suporte de primeira classe a WSL), **Linux** ou **macOS**.
- **Node.js** instalado para rodar o Claude Code (o instalador do Windows pode provisioná-lo).
- O **[Claude Code](https://github.com/anthropics/claude-code)** instalado no ambiente que você quer gerenciar.

## Suporte

Encontrou um problema ou tem uma sugestão? Abra uma **[issue](https://github.com/DouglasVulcano/nexo-releases/issues)** neste repositório.

## Licença

Distribuído sob a licença [MIT](LICENSE).

---

<sub>Nexo é um projeto independente e não é afiliado à Anthropic. "Claude" e "Claude Code" são marcas da Anthropic.</sub>

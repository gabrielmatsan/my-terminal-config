# 🖥️ Configuração de Terminal

Este repositório contém minhas configurações personalizadas para o terminal Ghostty e o shell Fish, otimizadas para produtividade e estética.

## ✨ Características

- **Terminal Ghostty** com tema Vesper personalizado
- **Fish Shell** com configurações avançadas
- **Starship Prompt** para um prompt minimalista e informativo
- **Atalhos de teclado** inspirados no TMux
- Suporte para uma variedade de ferramentas de desenvolvimento
- Navegação rápida com **zoxide** e **fzf**
- Terminal visualmente agradável com opacidade ajustada e fonte personalizada

## 🎨 Tema Vesper para Ghostty

O tema Vesper traz uma paleta de cores escura com acentos quentes, otimizada para reduzir a fadiga ocular durante longas sessões de codificação.
background=#161A22
foreground=#FFECD1
selection-background=#535353
selection-foreground=#FFECD1
cursor-color=#FF761A

### Paleta de Cores

| Normal       | Código    | Brilhante    | Código    |
|--------------|-----------|--------------|-----------|
| Preto        | `#14141D` | Cinza        | `#434354` |
| Vermelho     | `#D62C2C` | Rosa-vermelho| `#F47067` |
| Verde        | `#25922A` | Verde claro  | `#51DF3D` |
| Amarelo      | `#F3D474` | Amarelo claro| `#F8D97C` |
| Azul         | `#3B7AC4` | Azul claro   | `#3D90DF` |
| Magenta      | `#A03BA5` | Magenta claro| `#CA73E8` |
| Ciano        | `#2CA09B` | Ciano claro  | `#33C7BE` |
| Branco       | `#EAC094` | Branco quente| `#FFECD1` |

## ⚙️ Configuração do Ghostty

### Aparência

- Fonte: Victor Mono NFM Itálico, tamanho 15
- Altura da célula ajustada: 35%
- Opacidade do fundo: 96%
- Estilo do cursor: bloco
- Barra de título transparente no macOS

### Funcionalidades

- Integração com o shell
- Cópia para área de transferência ao selecionar
- Suporte para links clicáveis
- Layout de janela e estado salvos automaticamente
- Atualizações automáticas no canal estável

### Atalhos de Teclado

#### Globais
- `Cmd+E` - Alternar terminal rápido
- `Super+Grave` - Alternar terminal rápido (alternativo)

#### Gerais
- `Super+R` - Recarregar configuração
- `Super+I` - Alternar inspetor
- `Super+F` - Alternar tela cheia
- `Super+←` - Aba anterior
- `Super+→` - Próxima aba

#### Estilo TMux
- `Super+B, X` - Fechar superfície
- `Super+B, C` - Nova aba
- `Super+B, N` - Nova janela
- `Super+B, F` - Alternar tela cheia

#### Abas
- `Super+B, 1-9` - Ir para aba específica

#### Divisões
- `Super+B, \` - Nova divisão à direita
- `Super+B, -` - Nova divisão abaixo
- `Super+B, E` - Equalizar divisões
- `Super+B, Z` - Alternar zoom da divisão

#### Navegação entre Divisões
- `Super+B, H/J/K/L` - Navegar entre divisões (estilo vim)
- `Super+B, ←/↓/↑/→` - Navegar entre divisões (setas)

## 🐟 Configuração do Fish Shell

### Ferramentas Integradas

- **Starship** para personalização do prompt
- **bat** como substituto aprimorado para `cat`
- **eza** como substituto aprimorado para `ls`
- **zoxide** para navegação inteligente de diretórios
- **fzf** para pesquisa fuzzy de arquivos e histórico

### Aliases Úteis

- `l` = `ls -la`
- `ls` = `eza` com configurações avançadas (quando disponível)
- `cd` = `z` (quando zoxide está instalado)
- `cat` = `bat` com tema adaptativo baseado no modo claro/escuro do macOS

### Suporte para Ferramentas de Desenvolvimento

- **Bun** - Runtime JavaScript/TypeScript
- **pnpm** - Gerenciador de pacotes Node.js
- **Herd/Herd Lite** - Ambiente PHP para macOS
- **Java** - Configuração automática de JAVA_HOME
- **Go** - Configuração de GOPATH e ferramentas Go
- **rbenv** - Gerenciador de versões Ruby

### Variáveis de Ambiente

- Editor padrão: `nvim` (local) ou `vim` (SSH)
- Configuração de localização: `en_US.UTF-8`
- Flags de arquitetura para compilação

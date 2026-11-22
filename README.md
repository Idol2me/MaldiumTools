# MaldiumTools

**MaldiumTools** é uma coleção de ferramentas úteis e multiplataformas para macOS, Windows e Linux.

> ⚠️ Este repositório está em construção. O README será atualizado à medida que novas ferramentas forem adicionadas.

## Recursos

- Compatibilidade com Windows, macOS e Linux
- Instalação simples por sistema operacional
- Estrutura aberta a novas ferramentas e scripts
- Licença MIT

## Pré-requisitos

Antes de começar, instale:

- [Git](https://git-scm.com/downloads)
- Uma versão atual do terminal de seu sistema
- Dependências específicas da ferramenta que deseja utilizar

## Instalação

Clone o repositório:

```bash
git clone https://github.com/Idol2me/MaldiumTools.git
cd MaldiumTools
```

Em seguida, escolha seu sistema operacional.

### Windows

#### PowerShell

```powershell
git clone https://github.com/Idol2me/MaldiumTools.git
cd MaldiumTools
```

Se o Windows bloquear scripts ou você receber uma mensagem de execução de scripts desabilitada, abra o PowerShell como usuário normal e consulte a política vigente:

```powershell
Get-ExecutionPolicy -List
```

Para executar scripts locais com controle, use a política apropriada de sua organização. Não altere a política global caso não seja necessário.

Se existir um arquivo `.ps1`, execute-o a partir da raiz do projeto:

```powershell
.\CAMINHO\DO\SCRIPT.ps1
```

Substitua `CAMINHO\DO\SCRIPT.ps1` pelo caminho correto.

#### Pós-instalação no Windows

1. Confirme que o Git está disponível:

```powershell
git --version
```

2. Reinicie o terminal para recarregar variáveis de ambiente adicionadas durante a instalação.
3. Adicione ao `PATH` apenas os diretórios necessários da ferramenta instalada.
4. Abra o Windows Terminal ou o PowerShell e teste o comando da ferramenta.
5. Em caso de erro de permissões, execute o terminal como administrador somente quando necessário.

### Linux

#### Terminal

```bash
git clone https://github.com/Idol2me/MaldiumTools.git
cd MaldiumTools
```

Se for necessário executar um script Shell, confira as permissões e execute-o:

```bash
chmod +x CAMINHO/DO/SCRIPT.sh
./CAMINHO/DO/SCRIPT.sh
```

Substitua `CAMINHO/DO/SCRIPT.sh` pelo caminho correto.

#### Pós-instalação no Linux

1. Confirme que o Git está disponível:

```bash
git --version
```

2. Atualize os pacotes da distribuição antes de instalar dependências:

```bash
# Debian/Ubuntu
sudo apt update

# Fedora
sudo dnf check-update

# Arch Linux
sudo pacman -Syu
```

3. Reinicie o terminal após alterações no `PATH` ou nas configurações do Shell.
4. Abra uma nova sessão e teste o comando da ferramenta.
5. Mantenha o uso de `sudo` limitado às operações que realmente exigem privilégios administrativos.

### macOS

#### Terminal

```bash
git clone https://github.com/Idol2me/MaldiumTools.git
cd MaldiumTools
```

Se o macOS solicitar permissões para terminal ou pasta, revise a solicitação em:

**Configurações do Sistema > Privacidade e Segurança**

Se for necessário executar um script Shell:

```bash
chmod +x CAMINHO/DO/SCRIPT.sh
./CAMINHO/DO/SCRIPT.sh
```

Substitua `CAMINHO/DO/SCRIPT.sh` pelo caminho correto.

#### Pós-instalação no macOS

1. Confirme que o Git está disponível:

```bash
git --version
```

2. Caso o macOS apresente o aviso sobre desenvolvedor não identificado ao abrir um aplicativo gráfico, revise o arquivo em:

**Configurações do Sistema > Privacidade e Segurança**

Só permita aplicativos cuja origem seja confiável.

3. Reinicie o Terminal após alterações no `PATH`.
4. Abra uma nova sessão e teste o comando da ferramenta.
5. Em arquiteturas Apple Silicon e Intel, confirme que o aplicativo ou dependência corresponde à sua arquitetura.

## Atualização

Dentro da pasta do projeto:

```bash
git pull
```

## Estrutura do projeto

A estrutura será documentada aqui conforme ferramentas e scripts forem adicionados ao repositório.

## Contribuindo

Contribuições são bem-vindas.

1. Faça um fork do projeto
2. Crie uma branch para sua alteração
3. Envie um commit
4. Abra um Pull Request

Antes de contribuir, valide os scripts em todos os sistemas afetados e documente:

- Pré-requisitos
- Comandos de instalação
- Comandos de execução
- Comandos de desinstalação
- Possíveis erros e soluções

## Licença

Distribuído sob a licença [MIT](LICENSE).
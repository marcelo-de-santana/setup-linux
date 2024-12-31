# 🛠️ Setup Linux

Scripts de configuração e instalação das ferramentas utilizadas no meu computador.


## 🖥️ Instalação do Oh-My-ZSH
Oh-My-ZSH é um framework de gerenciamento de configuração para o Zsh (Z shell). Ele oferece temas e plugins que melhoram a experiência no terminal.

[Guia de Instalação Oficial](https://ohmyz.sh/#install)

### 🔌 Plugins Recomendados

- **Fast-Syntax-Highlighting**  
  Realça a sintaxe em tempo real no terminal, tornando os comandos mais fáceis de entender.  
    [Repositório Oficial](https://github.com/zdharma-continuum/fast-syntax-highlighting)

- **ZSH-Autosuggestions**  
  Sugere comandos baseados no histórico à medida que você digita, acelerando o uso do terminal.  
    [Repositório Oficial](https://github.com/zsh-users/zsh-autosuggestions)

- **ASDF**  
  Integração com o gerenciador de versões universal ASDF.  
    [Plugin ASDF para Oh-My-ZSH](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/asdf/asdf.plugin.zsh)

- **Docker**  
  Atalhos úteis para interagir com o Docker diretamente pelo terminal.  
    [Plugin Docker para Oh-My-ZSH](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/docker)

- **Docker-Compose**  
  Simplifica o uso do `docker-compose` com comandos mais curtos e eficientes.  
    [Plugin Docker-Compose para Oh-My-ZSH](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/docker-compose)

---

## 🌐 Instalação do ASDF
ASDF é um gerenciador de versões universal que permite gerenciar múltiplas linguagens de programação e ferramentas.

[Guia de Instalação Oficial](https://asdf-vm.com/guide/getting-started.html)

## 🐳 Instalação do Docker CLI
O Docker CLI permite interagir com o Docker diretamente pelo terminal. 

[Guia de Instalação Oficial do Docker para Ubuntu](https://docs.docker.com/engine/install/ubuntu/)

---

### 🛠️ Configuração do ASDF

- **Java**  
```	
    asdf plugin-add java https://github.com/halcyon/asdf-java.git
    asdf install java corretto-21.0.5.11.1
    asdf global java corretto-21.0.5.11.1
```	

- **Node.js**
```	
    asdf plugin-add nodejs https://github.com/asdf-vm/asdf-nodejs.git
    asdf install nodejs 22.12.0
    asdf global nodejs 22.12.0
```	
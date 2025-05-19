# 💻 Criação de Máquina Virtual no Microsoft Azure

Este repositório contém instruções detalhadas para criação de uma Máquina Virtual (VM) na plataforma de nuvem Microsoft Azure. Ideal para testes, aprendizado e ambientes de desenvolvimento.

## 🧰 Pré-requisitos

Antes de começar, certifique-se de que você possui:

- Conta ativa no [Azure Portal](https://portal.azure.com/)
- Assinatura válida do Azure
- Acesso à internet
- Permissões adequadas para criar recursos (caso esteja usando uma conta corporativa)

## 📌 Tecnologias / Recursos Utilizados

- Microsoft Azure
- Serviço de Máquina Virtual
- Sistema Operacional: (ex: Ubuntu Server 20.04 LTS, Windows Server 2022)

## 🚀 Passo a Passo para Criar uma Máquina Virtual no Azure

### 1. Acesse o Portal do Azure
- Vá para: https://portal.azure.com
- Faça login com suas credenciais

### 2. Crie um novo recurso
- No painel à esquerda, clique em **"Criar um recurso"**
- Selecione **"Máquina Virtual"**

### 3. Configurações básicas
- **Assinatura:** escolha sua assinatura
- **Grupo de recursos:** crie um novo ou selecione um existente
- **Nome da VM:** insira um nome único
- **Região:** escolha a mais próxima de sua localização
- **Imagem:** selecione o sistema operacional (ex: Ubuntu Server 20.04 LTS)
- **Tamanho:** escolha uma instância (ex: B1s para testes)
- **Usuário administrador:** defina nome de usuário e senha ou chave SSH

### 4. Configurações adicionais (opcional)
- Configure opções de disco, rede e extensões conforme necessário

### 5. Verificação e criação
- Clique em **"Revisar + criar"**
- Verifique se todas as informações estão corretas
- Clique em **"Criar"**

### 6. Acompanhe a implantação
- Aguarde até que a VM seja provisionada
- Após a conclusão, clique em **"Ir para o recurso"**

### 7. Acesse sua VM
- Copie o endereço IP público
- Acesse via SSH (Linux/macOS) ou RDP (Windows), por exemplo:

```bash
ssh nome_de_usuário@IP_DA_VM

# Documentacao-tecnica-maquinas-virtuais-da-azure
Laboratório Benefícios da Nuvem da trilha na DIO

# 🚀 Projeto: Máquinas Virtuais na Azure

## 📖 Descrição
Este projeto documenta a criação e configuração de uma máquina virtual no Microsoft Azure, realizada como parte do desafio da [Digital Innovation One](https://dio.me). O objetivo foi aplicar conhecimentos de VMs, redes, segurança e monitoramento de recursos em um ambiente de nuvem.

## 🎯 Objetivos
- Criar e configurar uma VM no Azure;
- Aplicar conceitos de rede, segurança e monitoramento de custos;
- Produzir documentação técnica clara e estruturada para portfólio.

## 🛠️ Execução

### 1. Criação da VM
A máquina virtual foi criada com as seguintes configurações:
- Nome: `vm-dio-anderson`
- Região: **Brasil Sudeste** (escolha estratégica para menor latência e proximidade geográfica)
- Sistema Operacional: **Windows 11 Pro**
- Tamanho: `Standard_B1s` (baixo custo, suficiente para testes e validação)
- Usuário administrador: `admin_ander`

### 2. Configuração de Rede e Segurança
- Foi criada uma rede virtual dedicada para a VM.
- Configurada a porta RDP (3389) para acesso remoto seguro.
- Regras básicas de firewall foram aplicadas, garantindo acesso autorizado apenas.

### 3. Validação
- A VM foi acessada remotamente utilizando o usuário `admin_ander`.
- O sistema operacional funcionou corretamente, e testes de instalação de pacotes básicos foram concluídos com sucesso.
- Todas as configurações atenderam aos critérios de funcionalidade, rede e segurança.

### 4. Monitoramento e Encerramento
- O consumo de recursos foi acompanhado através do painel **Custos + Faturamento** do Azure.
- A VM foi desligada ao final do teste para otimizar custos, seguindo boas práticas de gestão de recursos em nuvem.

## 🧑‍💻 Tecnologias Utilizadas
- **Microsoft Azure**
- **Windows 11 Pro**
- **GitHub + Markdown**

## 📚 Referências
- [Documentação Oficial Azure](https://learn.microsoft.com/azure/virtual-machines/)
- [Guia de Markdown GitHub](https://docs.github.com/pt/get-started/writing-on-github)

## 💡 Observações Técnicas
   A escolha da região e do tamanho da VM foi estratégica para equilibrar custo e performance. O processo reforçou a importância de planejamento em TI, mesmo em operações aparentemente simples. Configurações de rede e segurança são cruciais para evitar vulnerabilidades e custos desnecessários.

# Criação de Máquinas Virtuais na Microsoft Azure

## 1. Introdução
As máquinas virtuais (VMs) na Microsoft Azure são uma das principais formas de fornecer serviços de infraestrutura como serviço (IaaS). Elas permitem a criação e a execução de sistemas operacionais e aplicativos na nuvem, oferecendo flexibilidade para escalar e gerenciar cargas de trabalho de forma eficiente.

## 2. Passos para Criar uma VM no Azure

### a) Acessar o Portal do Azure
- Inicie o processo acessando o [Portal do Azure](https://portal.azure.com).
- Faça login com sua conta Microsoft.

### b) Criar um Recurso
- No painel de navegação, clique em "Criar um recurso".
- Escolha a categoria "Máquinas Virtuais" e clique em "Adicionar".

### c) Configuração da VM
1. **Escolha de um Sistema Operacional**:
   - Selecione o sistema operacional (Windows, Linux, etc.) que deseja instalar na VM.
   
2. **Configurações Básicas**:
   - **Nome da VM**: Defina um nome exclusivo para a máquina virtual.
   - **Região**: Escolha a região onde a VM será hospedada.
   - **Grupo de Recursos**: Selecione um grupo existente ou crie um novo.
   
3. **Tamanho da Máquina Virtual**:
   - O Azure oferece diferentes tamanhos de VM com base em CPU, memória e outros recursos. Selecione o que melhor se ajusta às suas necessidades.

4. **Autenticação**:
   - Escolha entre senha ou chave SSH para autenticação, dependendo do sistema operacional.

### d) Configuração da Rede
- Defina a rede virtual (VNet) que a VM usará. O Azure cria automaticamente uma rede padrão, mas você pode configurar uma VNet personalizada.
- Configurações como o **endereço IP público** e **segurança de rede** (NSG) também podem ser ajustadas.

### e) Discos e Armazenamento
- O Azure permite que você configure o disco do sistema operacional e discos de dados adicionais. Você pode escolher discos de diferentes níveis de desempenho (padrão, premium).

### f) Monitoramento e Avançado
- Configure opções de monitoramento, como o Azure Monitor, e escolha opções avançadas para otimizar o desempenho, escalabilidade e alta disponibilidade.

### g) Revisão e Criação
- Após configurar todos os parâmetros, clique em "Revisar + Criar". Verifique as configurações e clique em "Criar" para iniciar o processo de criação da VM.

## 3. Gerenciamento da Máquina Virtual
Depois de criar a VM, você pode gerenciá-la através do Portal do Azure, usando SSH (para VMs Linux) ou RDP (para VMs Windows). Também é possível configurar a escalabilidade automática, snapshots de disco, e realizar backups.

## 4. Custos
O custo de execução de uma VM no Azure depende de vários fatores, como tamanho da VM, tipo de disco, tempo de execução e a região onde está hospedada. O Azure oferece a opção de pré-pagamento com instâncias reservadas, que podem reduzir os custos em longo prazo.

## 5. Conclusão
Criar uma máquina virtual no Azure é um processo flexível que permite customizar cada aspecto, desde o sistema operacional até o tipo de armazenamento. Com a escalabilidade e os serviços gerenciados do Azure, é possível atender desde pequenas até grandes empresas com eficiência.

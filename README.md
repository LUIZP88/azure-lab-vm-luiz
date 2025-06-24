# Implantação e Gerenciamento de Máquinas Virtuais no Azure

## Descrição do Projeto
Este repositório foi desenvolvido como parte do desafio da plataforma DIO, com o objetivo de aplicar os conhecimentos adquiridos sobre Microsoft Azure, especialmente no gerenciamento de máquinas virtuais (VMs).

O conteúdo documentado aqui serve como um guia prático para a criação, configuração, alteração de disco e gerenciamento de VMs no Azure. Também inclui imagens que evidenciam cada etapa do processo, facilitando revisões e futuras implementações.

## Criação de Resource Group
- Imagem 1: Acessando a criação de Resource Group;
- Imagem 2: Inserção do nome e região do grupo;
- Imagem 3: Exibição do grupo criado.

##  Implantação da Máquina Virtual
- Imagem 4: Acessando o menu de criação de máquinas virtuais;
- Imagem 5: Seleção do tipo "Virtual Machine";
- Imagem 6-7: Escolha do Resource Group previamente criado;
- Imagem 8: Definição das zonas de disponibilidade;
- Imagem 9: Seleção do tipo de segurança (Standard);
- Imagem 10: Escolha do tamanho do disco;
- Imagem 11: Criação da conta de administrador;
- Imagem 12-13: Escolha da imagem do sistema operacional;
- Imagem 14: Revisão geral dos dados;
- Imagem 15: Configurações de monitoramento;
- Imagem 16-17: Validação das configurações e início da criação;
- Imagem 18-19: Notificações e acompanhamento do deploy;
- Imagem 20-22: Evidência da criação da VM com o tamanho do disco definido.

##  Alteração do Tamanho do Disco
- Imagem 23: Tela de alteração do tamanho do disco da VM;
- Imagem 24-25: Confirmação da alteração.

##  Anexando um Novo Disco
- Imagem 26: Acessando opção para adicionar novo disco;
- Imagem 27-29: Configuração e criação do disco adicional;
- Imagem 30: Evidência do novo disco anexado.

##  Desanexando Disco da Máquina
- Imagem 31-32: Processo de desanexar disco da VM.

##  Desligando a Máquina Virtual
- Imagem 33: Desligamento da máquina virtual no portal.

##  Dicas e Boas Práticas
- Utilize nomenclaturas padronizadas para facilitar a organização de recursos;
- Prefira regiões mais próximas para menor latência;
- Monitore o uso de disco e CPU para evitar custos desnecessários;
- Sempre desligue ou exclua recursos que não estão mais em uso;
- Utilize grupos de recursos para gerenciar facilmente os recursos relacionados a um mesmo projeto.

##  Imagens
As imagens utilizadas nesta documentação estão armazenadas na pasta [`/imagens`](./imagens). Cada uma delas está nomeada conforme a ordem das etapas descritas acima, proporcionando uma navegação clara e cronológica.

##  Autor
Luiz Vieira
[LinkedIn] https://www.linkedin.com/in/luiz-paulo-vieira



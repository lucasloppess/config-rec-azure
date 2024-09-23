# config-rec-azure
Configurando recursos e dimensionando em máquinas virtuais na Azure
Região vem padrão na criação da máquina Virtual.
Tem algumas imagens prontas na criação da VM. Você pode escolher a zona de disponibilidade para cria sua máquina, zona 1, 2 ou 3.
Escala de disponibilidade serve para configurar como a máquina cresce dependendo do uso. De 10 em 10 minutos é feita uma consulta as VMs para ver se precisa ser ajustado as escalas das máquinas conforme o uso.
As VMs tem vários tamanhos e séries para modelo de trabalho. 
Tenho como ter um disco de VM com ISO preparada dentro da empresa para utilizar na Azure.
Portas de configuração geralmente são 3389 para conexão via área de trabalho remota.
Só é possível ligar a máquina pela azure. Você pode programar a ligação e desligamento da máquina utilizando uma conta de serviço.
É possível habilitar monitoramento na Azure.
Aplicativos de função -> Necessita de uma conta de armazenamento para criar e uma linguagem de programação.

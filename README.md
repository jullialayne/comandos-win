# Comandos Git
### Subir alterações
1. git status
2. git add .
3. git commit -m "Escreva aqui a alteração"
4. git push origin main

# Comandos Windows

systeminfo <- pega todas as informações do seu pc
ipconfig <- pega configurações do IP do Windows

### Atualizar softwares windows
1. win+r <- abre o executar
2. cmd <- abre o prompt de comandos
3. winget upgrade <- vê todas as atualizações de software
4. winget upgrade --all <- atualiza de softwares

### Limpar temporários
1. win+r <- abre o executar
2. cleanmgr <- abre a tela de limpeza de disco
3. Selecione itens a serem apagados
4. ok 

### Antivírus do windows
1. win+r <- abre o executar
2. mrt <- abre a tela de ferramenta de remoção de software mal-intencionado da Microsoft
3. Selecione sim > avançar
4. Escolha o tipo de Exame
  I. rápido
  II. geral
  III. personalizado
5. Selecione avançar e espere o exame terminar e clique em concluir


### Verificador de Arquivos do Sistema para reparar arquivos de sistema ausentes ou corrompidos
1. win <- abre o iniciar 
2. digite 'cmd' <- procura prompt de comando da Microsoft
3. clique com botão esquerdo do mouse <- abre opções 
4. clique em Executar como Administrador <- abre prompt como administrador
5. clique em Sim <- para abrir o prompt
6. digite 'sfc /scannow' e enter <- Verifica arquivos
7. 'A Proteção de Recursos do Windows encontrou arquivos corrompidos e os reparou com êxito.' <- ao aparecer essa mensagem o processo está completo

### Ferramenta de Gerenciamento e Manutenção de Imagens de Implantação
1. win <- abre o iniciar 
2. digite 'cmd' <- procura prompt de comando da Microsoft
3. clique com botão esquerdo do mouse <- abre opções 
4. clique em Executar como Administrador <- abre prompt como administrador
5. clique em Sim <- para abrir o prompt
6. digite 'Dism /Online /Cleanup-Image /CheckHealth' e enter <- Verifica arquivos
7. 'Nenhuma corrupção de repositório de componentes detectada.' <- ao aparecer essa mensagem o processo está completo


### Recursos do Windows: Tela sempre no topo, dividir tela em várias janelas organizadas, localize seu mouse na tela, extrator de texto entre vários outros
1. abra o Microsoft Store e baixe o app PowerToys
2. abra o PowerToys no iniciar do Windows
3. aproveite os recursos

![image](https://user-images.githubusercontent.com/83183478/209955130-14425c1a-09f7-41c7-a943-ef33b228da54.png)

### Melhorar tempo de inicialização
1. pressione win+r
2. digite 'msconfig' e clique em ok
3. abra a aba 'Inicialização de Sistema'
4. clique em 'Opções Avançadas'
5. selecione a caixa 'Número de processadores'
6. na caixa abaixou coloque o máximo de processadores disponíveis na sua máquina
7. clique em ok, depois em aplicar e ok novamente
8. e está pronto

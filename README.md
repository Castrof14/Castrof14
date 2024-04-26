tarefas = input('adicione sua tarefa: ') #Escrever a tarefa 
segunda_tarefa = input('Informe sua segunda tarefa: ')

print('SUA LISTA DE TAREFAS!')
if tarefas:
    print(f'Sua tarefa e de {tarefas} ')

if segunda_tarefa:
    print(f'Sua segunda tarefa {segunda_tarefa}')

#Tarefas prontas do Aluno
Tarefas_prontas = input('Quais tarefas estão prontas?: ')
print(f'Sua(s) tarefa(s) de {Tarefas_prontas} está pronta(s)!')

#Aluno remover tarefa
remover_tarefa = input('Deseja remover alguma tarefa? "Sim" ou "Não":')#Pergunta

if remover_tarefa == 'Sim':
    input('Qual tarefa deseja remover? ')

elif remover_tarefa == 'Não':
    print('Certo!')    

#Salvar tarefa do Aluno
Salvar_tarefa = input('Deseja Salvar suas Tarefas? "Sim" ou "Não" "Todas"?: ')  

if Salvar_tarefa == 'Sim':
   tarefa_slv = input('Qual tarefa deseja Salvar?: ') 
   print(f'Tarefa {tarefa_slv} Salva! com Sucesso :D ')

elif Salvar_tarefa == 'Não':
    print('Certo! :D')

elif Salvar_tarefa == 'Todas':
    print('Todas as Tarefas foram salvas!')

prioridade = input('Digite a prioridade da sua Tarefa "baixa", "média" , "alta": ')

print(f'Tarefa foi adicionada na prioridade {prioridade}')

data_de_vencimento1 = input('Coloque uma data de vencimento para sua primeira tarefa: ')
data_de_vencimento2 = input('Coloque uma data de vencimento para sua segunda tarefa: ') 

print(f'Data de vencimento da primeira tarefa foi alterada para {data_de_vencimento1}')
print(f'Data de vencimento da primeira tarefa foi alterada para {data_de_vencimento2}')

interface = print(f'Pimeira tarefa: {tarefas}')
segunda_interface = print(f'Segunda tarefa: {segunda_tarefa}')
prioridade = print(f'Prioridade das Tarefas: {prioridade}')
data_de_vencimento1 = print(f'Data de vencimento da primeira tarefa: {data_de_vencimento1}')
data_de_vencimento2 = print(f'Data de vencimento da segunda tarefa: {data_de_vencimento2}')

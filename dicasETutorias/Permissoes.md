# Entendo a listagem de permissões

Posição | Numero | O que é | Descrição | Caso seja HIFEN | Quem
--------|--------|---------|-----------|-----------------|------
Tipo    | - | d | (Diretorio) - (arquivo)| - | - 
Leitura | | r | (Read, pode ser lido) | Não pode | Usuário
Escrita | | w  | (Write, pode ser escrito)      | Não pode | Usuário
Execução | | x  | (eXecute, pode ser executado)  | Não pode | Usuário
Leitura  | |  r  | (Read, pode ser lido)          | Não pode | Criador
Escrita | | w  | (Write, pode ser escrito)      | Não pode | Criador
Execução | | x  | (eXecute, pode ser executado)  | Não pode | Criador
Leitura | | r  | (Read, pode ser lido)          | Não pode | Grupo
Escrita | | w  | (Write, pode ser escrito)      | Não pode | Grupo
Execução | | x  | (eXecute, pode ser executado)  | Não pode | Grupo

    Tipo    Usuario         Grupo           Qualquer um
      1       2   3   4       5   6   7       8   9   10


Exemplos
drwxr-xr-x 5 pinga pinga 4.0K Aug  3 00:59 .                                                                      
drwxr-xr-x 5 pinga pinga 4.0K Aug  6 05:14  .                                                                     
drwxr-xr-x 2 pinga pinga 4.0K Aug  9 00:32 dicasETutorias                                                         
drwxr-xr-x 8 pinga pinga 4.0K Aug  3 01:03 .git                                                                   


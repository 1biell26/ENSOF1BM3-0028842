    #include<stdio.h>
    #include<string.h>
    // capacidade
    #define MAX [100]
    // defindo a padrao de dados
    struct Cliente {
        int id;
        char nome [50];
        char telefone [20];
    };
    //Declarando Metodos
    int main(){
        struct Cliente cliente1[20];
        int total = 0;
        int opcao = 0;

        while(opcao != 4){
            printf("1 - Cadastrar cliente\n");
            printf("2 - Listar clientes\n");
            printf("3 - Buscar cliente por ID\n");
            printf("4 - Sair\n");
            printf("Escolha uma opcao: ");
            scanf("%d", &opcao);
            getchar();
    
            if(opcao == 1){
                if(total <MAX){
                    Clientes[total].id = total + 1;
                    printf("Nome: ");
                    fgets(clientes[total].nome, 50, stdin);
                    clientes[total].nome[strcspn(clientes[total].nome, "\n")] = '/0'
            
            
                    printf("Telefone: ");
                    fgets(clientes[total].nome, 20, stdin);
                    clientes[total].nome[strcspn(clientes[total].nome, "\n")] = '/0'
                }
            }
    
        }   

    };

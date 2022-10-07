int main(void){


    int Usuario;
    int Nome;
    int Curso;
    int Universidade;
    int Numero da matricula;
    Usuario = leusmix
    Nome = Leonardo de Avila
    Curso = Analise e Desenvolvimento de Sistemas
    Universidade = Universidade La Salle
    Numero da matricula = 10841
    cout << "Valor de Usuario: " << leusmix << endl;
    return 0
    
    
    
    
    float x=0, y=0, resultado=0;
    int op=0;
    do{
        printf("\n\t1 - SOMA\n\t2 - SUBTRACAO\n\t3 - MULTIPLICACAO\n\t4 - DIVISAO");
        scanf("%i", &op);
        printf("\nDigite o primeiro numero: ");
        scanf("%f", &x);
        printf("\nDigite o segundo numero: ");
        scanf("%f", &y);
        switch(op){
            case 1:
                resultado = x+y;
                break;
            case 2:
                resultado = x-y;
                break;
            case 3:
                resultado = x*y;
                break;
            case 4:
                resultado = x/y;
                break;
            default:
                printf("\n Digite uma opcao valida\n");
                break;
        }
        printf("\n\t O resultado e: %0.2f", resultado);
        printf("\n Digite 1 para continuar: ");
        scanf("%i", &op);
    }while(op==1);
}

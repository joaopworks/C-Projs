#include <iostream>
#include <string>

using namespace std;

int  i=0, nums;

string pause;

int arm = 0;

int main()
{
    double num1, num2, resultado, resto[i];
    int escolha, escolha3, escolha4;
    double soma=0, subtracao=0, multiplicacao=0;
    double armazenamento[arm];
    cout<<"--Calculadora--\r\n";

    cout<<"\n\nPressione qualquer tecla para continuar...\r\n\n";
    cin>> pause ;


    label:

    system("clear");

    i=0; num1=0; num2=0; resultado=0; escolha = 0;

    cout<<"Que tipo de calculo deseja executar:\n1-Soma\n2-Subtracao\n3-Multiplicacao\n4-Divisao\r\n";
    cin>>escolha;

    switch(escolha)
    {
        case 1:
            system("clear");
            nums = 0;
            cout<<"A opcao escolhida foi soma\nQuantos numeros deseja somar ?\r\n";
            cin>>nums;

            for(i; i < nums; i++)
            {
                cout<<"\nDigite o "<< i <<" numero:";
                cin >> soma;
                resultado = resultado + soma;
            }

            arm++;

            armazenamento[arm] = resultado;

            cout<<"\n\nO resultado da sua soma de "<< i <<" numeros, e:"<<resultado<<"\r\n";

            cout<<"\n\nPressione qualquer tecla para continuar...\r\n\n";
            cin>> pause ;

        break;

        case 2:
            system("clear");
            nums = 0;
            escolha3=0;
            cout<<"Deseja fazer subtração 1-composta ou 2-comum ?\r\n";
            cin>> escolha3;

            if(escolha3 == 2)
            {
                system("clear");
                cout<<"A opcao escolhida foi subtracao comum\nInsira os numeros em ordem:\r\n";
                cin>>num1;
                cin>>num2;

                resultado = num1 - num2;

            }

            else if(escolha3 == 1)
            {
                system("clear");
            cout<<"A opcao escolhida foi subtracao composta\nQuantos numeros deseja subtrair ?\r\n";
            cin>>nums;

            for(i; i < nums; i++)
            {
                cout<<"\nDigite o "<< i <<" numero:";
                cin >> subtracao;

                resultado = resultado - subtracao;
            }
            }
           cout<<"\n\nO resultado da sua subtracao de "<< i <<" numeros, e:"<<resultado<<"\r\n";

            cout<<"\n\nPressione qualquer tecla para continuar...\r\n\n";
            cin>> pause ;
        break;

        case 3:

           system("clear");
            nums = 0;
            escolha4=0;
            cout<<"Deseja fazer mutiplicacao 1-composta ou 2-comum ?\r\n";
            cin>>escolha4;

            if(escolha4 == 2)
            {
             system("clear");
                cout<<"A opcao escolhida foi multiplicacao comum\nInsira os numeros em ordem:\r\n";
                cin>>num1;
                cin>>num2;

                resultado = num1 * num2;
            }

            else if(escolha4 =1)
            {
            cout<<"A opcao escolhida foi multiplicacao\nQuantos numeros deseja multiplicar ?\r\n";
            cin>>nums;

            resultado = 1;

            for(i; i < nums; i++)
            {
                multiplicacao = 0;
                cout<<"\nDigite o "<< i <<" numero:";
                cin >> multiplicacao;

                resultado = multiplicacao * resultado;
            }
            }
            cout<<"\n\nO resultado da sua multiplicacao e: "<<resultado<<"\r\n";
            cout<<"\n\nPressione qualquer tecla para continuar...\r\n\n";
            cin>> pause ;
        break;

        case 4:

            system("clear");

            cout<<"A opcao escolhida foi divisao\nDigite em sequencia o numeros a serem divididos:\r\n";
            cin>>num1;
            cin>>num2;

            resultado = num1/num2;

            arm++;

            armazenamento[arm] = resultado;

            cout<<"\n\nO resultado da sua subtracao de "<< i <<"numeros, e:"<<resultado<<"\r\n";

            cout<<"\n\nPressione qualquer tecla para continuar...\r\n\n";
            cin>> pause ;
        break;
    }

    system("clear");
    cout<<"--Deseja fazer mais calculos ?--\n1-Sim\n2-Nao\r\n";
    label1:

    int escolha2 = 0;

    cin>>escolha2;

    if(escolha2 == 1)
    {
        goto label;
    }
    else if (escolha2 == 2)
    {
        system("clear");
        cout<<"Obrigado por usar a calculadora\r\n";
        cout<<"\n\nPressione qualquer tecla para continuar...\r\n\n";
        cin>> pause ;
    }

    else if (escolha2 != 1|2)
    {
        system("clear");
        cout<<"Opcao invalida, tente novamente...\n\n";
        goto label1;
        cout<<"\n\nPressione qualquer tecla para continuar...\r\n\n";
        cin>> pause ;
    }
    return 0;
}

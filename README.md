# exer3
#include<iostream>
#include<string>
using namespace std;
int main() {

	int qtdeAlunos = 0;
	
	  cout << "Digite a quantidade de alunos no sistema: \n";
	    cin >> qtdeAlunos;
	    
	    string vetorNomes[qtdeAlunos];
	    float vetorNotas1[qtdeAlunos];
	    float vetorNotas2[qtdeAlunos];
	    
	  for(int i = 0; i < qtdeAlunos; i++){
	  	cout << "Digite o nome do " << i + 1 << " aluno: \n";
	  	   cin >> vetorNomes[i];
	  	 cout << "Digite a nota do " << vetorNotas1[1] << " no 1 bim: \n";
	  	   cin >> vetorNotas1[i];
	  	 cout << "Digite a nota do " << vetorNotas2[1] << " no 1 bim: \n";
	  	   cin >> vetorNotas2[i];
	  }
	    
       for(int i = 0; i < qtdeAlunos; i++){
       	  float media = (vetorNotas1[i] + vetorNotas2[i]) / 2;
       	if(media >= 6){
       		cout << "aluno: " << vetorNomes[i] << " tirou " << media << "status: aprovado";
			   }else{
       		cout << "aluno: " << vetorNomes[i] << " tirou " << media << "status: reprovado";
			   }
		   }

    
system("pause");
return 0;
}

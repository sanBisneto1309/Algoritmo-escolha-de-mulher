# Algoritmo-escolha-de-mulher
Na duvida em qual mulher escolher para se relacionar? Use esse algoritmo para tirar suas conclusões(Se quiser não precisa ficar focado só em duas, pode copiar o código e adicionar quantas você quiser) Dupla: Santiago e Nelson 

#include <iostream>
#include <string>

using namespace std;

int main() {
  string nome, mulher1, mulher2, beleza, inteligencia, carisma;
  cout <<  "Olá, qual é o seu nome?";
  cin >> nome;
  
  cout << "Olá, " << nome << ", qual o nome da primeira mulher?" << endl;
  cin >> mulher1;
  
  cout << "Qual o nome da segunda mulher, " << nome << "?" << endl;
  cin >> mulher2;
  
  cout << "Entre a " << mulher1 << " e a " << mulher2 << ", qual é a mais bonita, " << nome << "?" << endl;
  cin >> beleza;
  
  if(beleza == mulher1){
  cout << "A " << mulher1 << " é a mais bonita" << endl;
  } else if(beleza == mulher2) {
  cout << "A " << mulher2 << " é a mais bonita" << endl;
  }else{
  cout << "ERRO! Reinicie o programa, " << nome << "!" << endl;
  }
  
  cout << "Entre a " << mulher1 << " e a " << mulher2 << ", qual é a mais inteligente, " << nome << "?" << endl;
  cin >> inteligencia;
  if(inteligencia == mulher1){
  cout << "A " << mulher1 << " é a mais inteligente" << endl;
  } else if(inteligencia == mulher2){
  cout << "A " << mulher2 << " é a mais inteligente" << endl;
  }else{
  cout << "ERRO! Reinicie o programa, " << nome << "!" << endl;
  }

  cout << "Entre a " << mulher1 << " e a " << mulher2 << ", qual é a mais carismática, " << nome << "?" << endl;
  cin >> carisma;
  if(carisma == mulher1){
  cout << "A " << mulher1 << " é a mais carismática" << endl;
  } else if(carisma == mulher2) {
  cout << "A " << mulher2 << " é a mais carismática" << endl;
  } else{
  cout << "ERRO! Reinicie o programa, " << nome << "!" << endl;
  }
  
  return 0;
}

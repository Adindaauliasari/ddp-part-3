#include "iostream"

using namespace std;

int main ()

{
	    
	  float bitcoin,shrimp,crab,octopus,fish,dolphin,shark,whale,humpback ;
	 
	  cout<< "TINGKATAN HOLDER ( PEMILIK BTC )" << endl;
	  
	  cout<< " "<< endl;
	  
	  cin>>bitcoin;
	  
	  cout<< " " << endl;
	  
	  
	  if(bitcoin < 1){
	  	cout<< "tipe ranking : shrimp" << endl;
	  }
	  else if (bitcoin >= 1 && bitcoin < 10){
	  	cout<< "tipe ranking : crab"  << endl;
	  }
	  else if (bitcoin  >= 10 && bitcoin < 50){
	  	cout<< "tipe ranking : octopus"  << endl;
	  }
	  else if (bitcoin  >= 50 && bitcoin < 100 ){
	  	cout << "tipe ranking : fish" << endl;
	  }
	  else if (bitcoin  >= 100 && bitcoin < 500){
	  	cout << " tipe ranking : dolphin" << endl;
		
	  }
	  else if (bitcoin  >= 500 && bitcoin  < 1000){
	  	cout << "tipe ranking : shark" << endl;
	  }
	  else if (bitcoin >= 1000 && bitcoin < 5000){
	  	cout << "tipe ranking : whale" << endl;
	  }
	  else{
	  	cout << " tipe ranking : humpback" << endl;
	  }
}

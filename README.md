# Java01Dev.F

# Codigo que contiene tres metodos, un factorial de un numero, la sucesion de fibonacci y el ordenamiento de un arreglo
public class principal {

	public void fibonacci(int n){

		int i=1;

		int j=1;

		int k=1;

		int t;

	for(i=1; i<n; i++){

		t=k+j;

		k=j;

		j=t;

	System.out.println(j);

	}
}

	public void factorial(int n){

		int res=n-1;

		int aux;

		while(res>0){

			aux=n*res;

			n=aux;

			res--;
		}
	}

	public void ordena(int [] arr){

		int i=1;

		int j=1;

		int aux;

		for(i=1;i<arr.length-1;i++){

			for(j=1;j<arr.length-i;j++){

				if(arr[j]>arr[j+1]){

					aux=arr[j];

					arr[j]=arr[j+1];

					arr[j+1]=aux;
				}
			}
		}	
	}
#Fin del documento


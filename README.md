# assign1

## Steps to Run the app

1. Clone the repo with  
	```git clone https://github.com/Pujapriya/assign1.git```  

2. Then goto that directory using  
	```cd assign1```  

3. Run all the yaml files through this commands.

	```kubectl apply -f pods.yaml```  
	```kubectl apply -f deployments.yaml```  
	```kubectl apply -f services.yaml```

4. Now run the docker through this command  
	```sudo docker run -e NAME="YOUR_NAME" -d -p 8000:80 pujapriya/theapp:hello``

5. Now Open the browser on the link ```http://localhost:8000/```

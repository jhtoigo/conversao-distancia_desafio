# conversao-distancia

1. Rodar o Build da imagem
    ```
    docker build -t jhtoigo/conversao-distancia:v1 .
    ```

2. Executar o container através da imagem recem criada com o nome e tag "jhtoigo/conversao-temperatura:v1"

    ```
    docker container run -d --name conversao-distancia -p 5000:5000 jhtoigo/conversao-distancia:v1
    ```

3. Acessar a aplicação através do navegador na porta definida no caso 5000:
   
   http://localhost:5000

4. Remover container
    ```
    docker container rm -f conversao-distancia
    ```

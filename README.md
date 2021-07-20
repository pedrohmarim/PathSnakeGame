# PathSnakeGame-2020
Plataforma web contendo Snake Game com sistema de login e score/ranking (Seminário da Faculdade, Disciplina de IHC - 2020 )

## Instruções 

Após baixar o projeto .zip contendo as pastas Frontend e Backend:
  
  • Acessar a pasta Frontend e Backend através do terminal, e rodar **npm install**, após isso, começará a instação das dependências do projeto na pasta *node_modules* que foi gerada automáticamente.  
    
   ![frontend](https://user-images.githubusercontent.com/62761711/126247679-371d7b09-76a0-4bd3-af67-14272dcf4a47.png)
   ![backend](https://user-images.githubusercontent.com/62761711/126247683-6818a242-ce8b-44b7-8863-a4fd5a2d77a8.png)
    
  *Caso o terminal identifique vulnerabilidades após a instalação, rode o comando **npm audit fix***.
  
  • Após isso, será preciso criar um arquivo .env dentro da pasta *src* do projeto frontend, como na figura abaixo:
  
   ![env](https://user-images.githubusercontent.com/62761711/126247837-c26ed6d9-9f70-415f-9771-1c0e3c176678.png)
   
  • Logo após, no diretório backend, no arquivo server.js será preciso configurar sua própria chave do MongoDB.
  
  ![DBKEY](https://user-images.githubusercontent.com/62761711/126248045-a26c11be-946b-4c67-9e87-9e8f81fb2217.png)
  
  • Feita a instalação das dependências necessárias, criado o .env e configurado a chave do banco de dados, pelo terminal, você ira rodar o comando **npm start** em ambas as pastas, tanto na */frontend* quanto */backend*.  
  
  ![frontend2](https://user-images.githubusercontent.com/62761711/126247872-4dfa60fa-ab19-41ea-8ffa-3cf886f900a0.png)
  ![backend2](https://user-images.githubusercontent.com/62761711/126247876-97681f82-950b-4c39-a193-71277470a056.png)
  
  • Após o start de ambos, uma página web será automáticamente aberta em seu navegador, e o servidor backend estará rodando em seu terminal.
  
## Imagens da plataforma desktop.

### Página de login.
![pathsnake_login](https://user-images.githubusercontent.com/62761711/126247913-b67a9f86-b714-4740-adb1-00b4d1b0be07.png)
### Página recuperação de senha.
![pathsnake_recover](https://user-images.githubusercontent.com/62761711/126248170-1b909f34-3f76-47be-b90f-d6484cb20def.png)
### Página de comandos dentro do jogo.
![pathsnake_commands](https://user-images.githubusercontent.com/62761711/126248212-fb3aeb6c-d443-43bc-b79d-b17073a086b4.png)
### Página de registro
![pathsnake_register](https://user-images.githubusercontent.com/62761711/126248244-3c71c8f4-d360-40c3-8126-8c33bbd5a5ef.png)
### Imagem do começo do jogo.
![pathsnake_game](https://user-images.githubusercontent.com/62761711/126248291-bea8dc94-134b-4bd2-8443-dadce99b7096.png)
### Imagem após um total de 24 pontos para exemplo.
![pathsnake_game2](https://user-images.githubusercontent.com/62761711/126248327-17a64453-bc94-4174-8df5-8e11b74ba3f0.png)
### Página de Score de usuário após game over.
![socre](https://user-images.githubusercontent.com/62761711/126248360-3bc63f38-f702-44ba-bc35-a18d3adcae86.png)
### Página exemplo de ranking.
![ranking](https://user-images.githubusercontent.com/62761711/126248385-ec004198-7106-4e35-b9d3-19831c9d6608.png)

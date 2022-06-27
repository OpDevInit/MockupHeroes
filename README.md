# MockupHeroes

**Versão Mockup De Cadastro de Heróis**

`não esqueça de iniciar o Postman!`
    - sempre utilize JSON como resposta para o servidor...
      
      exemplo:
        {
            "id":,
            "Liga": "",
            "Herói": "",
            "Habilidade": "",
            "Personalidade": ""
        }
    
    **MODELO DE RESPOSTA E REQUISIÇÕES POSTMAN**
        
        https://lunar-meadow-398815.postman.co/workspace/My-Workspace~8053f580-3233-4292-87f2-9c1c515a656f/request/20217792-29b2854a-d9ed-410b-9cc5-5a98c10342f3
        
1. - Abrir terminal (git bash) em uma pasta    
    - clonar o repositório nesta pasta local por meio do comando: 
     
    exemplo para clonar este repositório:

    `https://github.com/OpDevInit/MockupHeroes.git`

2. Abrir a pasta com o VSCode

3. Abrir um terminal no VSCode

4. Criar a pasta node_modules coms as dependências do "package.json"

    `npm install`


5.  Para a utilização da rota privada instalar o pacote jsonwebtoken:

    `npm install jsonwebtoken`

    Para o cadastro, alteração e exclusão de vilões o primeiro acesso deve ser feito em http://localhost:3001/auth
    Com o post enviar o cadastro e a senha (Já informados no arquivo), ele irá retornar um token.
    Esse token deve ser inserido na aba de bearer do http://localhost:3001/viloes em caso de post, put e delete esse token expira em 1 dia e deve ser renovado para novos cadastros.
    Essa caminho não é necessário para herois, pois é uma rota pública, enquanto a rota de vilões é uma rota privada.


    _F5 irá executar a API Fake._

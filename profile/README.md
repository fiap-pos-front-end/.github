## Tech Challenge 2 🚀

### Iniciando o Projeto

1. Crie uma pasta principal para o projeto.
2. Clone **todos os repositórios disponíveis** dentro dessa pasta.
3. Acesse a pasta do repositório `fiap-tc-infra` e **mova os arquivos para a raiz do projeto**, ou seja, para fora da pasta `fiap-tc-infra`.

> Ao final, sua estrutura de pastas deve se parecer com isso:

<img width="909" height="416" alt="image" src="https://github.com/user-attachments/assets/7216f951-e338-4aa6-b4db-d4f60ffcaae0" />

---

### Rodando o Projeto

#### - Usando Docker
1. Acesse a pasta criada contendo todos os repositorios
2. Na raiz, digite:
   ```bash
   docker compose --env-file .env up --build
   ```
3. Após terminar de buildar, verifique o seu DockerDesktop e acesse o shell.
<img width="2249" height="314" alt="image" src="https://github.com/user-attachments/assets/c783552b-52d4-4b18-a600-256babee1781" />


#### - Sem Docker

1. Acesse a pasta principal do projeto (onde os repositórios estão organizados).
2. Entre na pasta `fiap-tc-shell`:  
   ```bash
   cd fiap-tc-shell
   ```
3. Execute os seguintes comandos:
   ```bash
   npm run sync:all
   npm run install:all
   npm run start:all
   ```

4. Abra o navegador e acesse:  
   [http://localhost:4200](http://localhost:4200)

> Pronto! O projeto estará rodando localmente 🎉

---

📦 Confira também: 

[README do MFE fiap-tc-angular (Transferências)](https://github.com/fiap-pos-front-end/fiap-tc-angular/blob/main/README.md)/

[README do MFE fiap-tc-angular2 (Categorias)](https://github.com/fiap-pos-front-end/fiap-tc-angular2/blob/main/README.md)/

[README do MFE fiap-tc-react (Dashboards)](https://github.com/fiap-pos-front-end/fiap-tc-react/blob/main/README.md)/

[README do projeto fiap-tc-shell (Host)](https://github.com/fiap-pos-front-end/fiap-tc-shell/blob/main/README.md)/

[README do projeto fiap-tc-shared (Biblioteca utilitária)](https://github.com/fiap-pos-front-end/fiap-tc-shared/blob/main/README.md)/

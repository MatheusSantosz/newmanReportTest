<h1>Projeto realizado na semana de teste de Api sem Complicacao ChornosAcademy</h1>
<h3>Como executar o projeto</h3>

👋 Seja bem vinda(o)!

#Dependencias

### 1- Instalar o postman 
```
https://www.postman.com/downloads/
```

### 2- Instalar o Node na pasta do Projeto
```
 npm install
```

### 3- Instalar o Newman 
```
 npm install -g newman
```

### 4- Instalar o Newman  ReporterHtml
```
 npm install -g newman-reporter-htmlextra
```

#Como executar
  
 ### 1- Clone o projeto do repositorio GIT em uma pasta.
```
git clone https://github.com/MatheusSantosz/newmanReportTest.git
```
  
### 2- Execute o projeto no Postman, verifique os tests.


### 3- Abra o CMD execute o teste somente em linha de comando.
```
newman run APISemComplicacao.postman_collection.json -e CepMatheus.postman_environment.json
```
### 4- Abra o CMD execute o comando se quiser o report em Html.
```
newman run APISemComplicacao.postman_collection.json -e CepMatheus.postman_environment.json --reporters=cli,htmlextra
```

### Developed

- [x] Test Api
- [x] Newman ReportHtml

<h4 align="center"> 
	 Status 🚀🚀 Finalizado 
</h4>

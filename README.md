# Convergentes - API :postman:

Projeto de automação de API com o ```Postman```.

Projeto voluntário supervisionado pela Qa.Coders para Testes de API executado pela equipe Convergentes

## Instalação

   ``` npm install -g newman ```
   ``` npm install -g newman-reporter-htmlextra ```

Clone o projeto:

```bash
  git clone  https://github.com/Lukas3570/convergentes-academy-api-postman
```

Para rodar os testes, rode os seguintes comandos:

Newman
```bash
  newman run 1-Login_collection.json -e main_environment.json -g postman_globals.json
```
```bash
  newman run 2-Users_collection.json -e main_environment.json -g postman_globals.json
```
```bash
  newman run 3-Board_collection.json -e main_environment.json -g postman_globals.json
```
Htmlextra
```bash
  newman run 1-Login_collection.json -e main_environment.json -g postman_globals.json -r htmlextra --reporter-htmlextra-export ./results/report.html
```
```bash
  newman run 2-Users_collection.json -e main_environment.json -g postman_globals.json -r htmlextra --reporter-htmlextra-export ./results/report.html
```
```bash
  newman run 3-Board_collection.json -e main_environment.json -g postman_globals.json -r htmlextra --reporter-htmlextra-export ./results/report.html
```

## Equipe

- [@lukas3570](https://github.com/Lukas3570)
- [@lidianycosta](https://github.com/lidianycosta)
- [@Elias-roccha](https://github.com/Elias-roccha)

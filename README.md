# Documentation Template created by Diplodoc

Features:

- initial project structure
- dev server with hot reload
- codespaces support
- vscode tutorial via code tours

## Initial project structure

Initiatl project structure with basic content can be found within your public github repo "diplodoc-example/docs" 

## Usage

### Run locally by cloning repo:

```
> git clone git@github.com:diplodoc-platform/documentation-template.git

> cd documentation-template

> npm start

> listening on 0.0.0.0:8000

```
now you have development server with hot reload runing and serving built documentation on `0.0.0.0:8000`

### github codespaces

press Use this template -> Open in a codespace

![open in a codespace](images/open-in-a-codespace.jpeg)

wait for the development server startup

enjoy developing documentation with html result preview in split view

![codespaces project](images/codespaces-project.jpeg)


My way:
1. Start on diplodoc
2. Clone repo from github on local machine
3. npm i yfm
4. npm i @diplodoc/cli -g
5. npm start и переход в http://127.0.0.1:8000/en/ </br>
    ? Как сделать запуск сразу на русской локализации
6. Папки с вложениями(картинки и переиспользование обязательно с "_")
7. Перед incude обязательна пустая строка
8. Чтобы вставки не разрывали структуру списка нужен еще олдин таб  
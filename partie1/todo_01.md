## Squelette de notre app en html
```bash
# template html
```
```html
<!doctype html>
<html lang="fr">
    <head>
    </head>
    <body>
    </body>
</html>
```
```bash
# on ajoute le titre de la page de notre app avec la balise title dans la balise head
```
```html
<head>
  	<title>Todo App V1</title>
</head>
```
```bash
# on ajoute un titre à notre app avec la balise h1 dans une balise div dans body
```
```html
<div>
	<h1>Liste Todos <sup><span>V 0.1</span></sup></h1>	
</div>
```
```bash
# on ajoute notre table de données (liste des tâches) dans body
```
```html    
    <table>
		<tr>
			<th>Id</th>
			<th>Description</th>
			<th>Complète</th>
			<th>Actions</th>
		</tr>
		<tr>
			<td >1</td>
			<td>Apprendre Html5</td>
			<td>Oui</td>
			<td>Bouttons des actions</td>
		</tr>
		<tr>
			<td >2</td>
			<td>Apprendre CSS3</td>
			<td>Oui</td>
			<td>Bouttons des actions</td>
		</tr>
		<tr>
			<td >3</td>
			<td>Apprendre Bootstrap5</td>
			<td>Oui</td>
			<td>Bouttons des actions</td>
		</tr>
		<tr>
			<td >4</td>
			<td>Apprendre JavaScript</td>
			<td>Oui</td>
			<td>Bouttons des actions</td>
		</tr>
	</table>
```
# Bases

* .editorconfig : Configuracion del editor
* .gitignore : cuando nosotros hagamos un git commit este archivo se encargara de omitir algunos archivos como node_modules
* .angular.json : normalamente no se modifica este archivo y si se hace, se hace raras veces y luego te olvidas del archivo
* .package.json : son los modulos del node.js, podemos crear scripts ademas
* .tsconfig : se encarga de uniformizar las buenas practicas en el desarrollo de angular

Todos esos archivos de la raíz casi nunca los tocaremos

.angular
archivo que no tocaremos

.vscode
no daremos mantenimiento, a veces podremos usar extensions para indicar que extensiones podria instalar

node_modules
incluye nuestros paquetes

src

main.ts
se modificara cuando trabajemos con otro archivo, como por ejemplo 
electron, 
platformdynamic


app/
```ts
import { Component } from '@angular/core';

@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrl: './app.component.css'
})
export class AppComponent {
  title = 'bases';
}
```

.app.module.ts

Este es el modulo principal, es muy delicado, este puede crecer muy rápido y ya mas adelante se vera como mejorar esto.




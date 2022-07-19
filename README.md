# Angular-formly
This repo contains example of Angular-formly implementation.

Install NodeJS:
https://nodejs.org/en/ 

Check installed node version from CLI.
node --version
If you get error then restart CLI IDE." 
'node' is not recognized as an internal or external command, operable program or batch file."

install typescript  
npm install -g typescript                          
install typescript   
npm install -g @angular/cli 

Check Angular version from Comand Line (CLI)     
ng version

install visualstudioCode editor
https://code.visualstudio.com/docs?start=true

Create Folder in c drive
Go to folder through Node command prompt   
ng new projectname

Open created project from Visual Studio Code and run below command from terminal to compile project.
npm start
It will call ng serve to compile application 

Open browser and paste below URL
localhost:4200

Formly is java script library which requires to install module in Angular. Formly offers to make reactive forms through configured fields means dynamic created fields.

Open Angular project in Visual Studio Code and open terminal
Run below command to install formly.
npm install @angular/forms @ngx-formly/core @ngx-formly/bootstrap --save

Add below modules in app.module if did not get added automatically.
import { ReactiveFormsModule } from '@angular/forms';
import { FormlyModule } from '@ngx-formly/core';
import { FormlyBootstrapModule } from '@ngx-formly/bootstrap';

Run npm start or ng serve to run project.

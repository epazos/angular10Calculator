# angular10Calculator
 testing angular v10 Calculator Component
 
 > ng serve (to serve the proyect in http://localhost:4200 )

> ng generate module <name-module>

in app.modules.ts list the components in:
@NgModule ({
    alculatorComponent,
    .
    .
    .
});

in app.componet.html -> general component like index.html
<app-calculator></app-calculator>


four types of Data-Binding:

    1. String Interpolation -> <h1>{{product.title}}</h1>

    2. Property Binding -> <input type="text" class="calculator-screen"  [value]="currentNumber"

    3. Event Binding -> <button type="button" (click) = "getNumber('1')"

    4. 2way Data Binding -> <input [( ngModel)] = "currentNumber" />

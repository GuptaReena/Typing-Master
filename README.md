# Typing Master 

# Step1 : Create a angular project : ng new typing

				Install BootStrap : npm install bootstrap@5.3.2



#Step 2 : Configure bootstrap.min.css file in to angular.json


#app.component.html



#Step 3 : Create a card layout in your app.component.html file 

				1 Input Field

							 bind metgod with your inputField 

										--> # text  (input) = userInput(text.value)  

				<span  [class] = compare(rl, el[input])  *ngFor = let rl from randomText.split(''), let input = index;"></span>





#app.Component.ts



A method to take an input from user



--> enteredText : String = ' ';



# install npm i @faker-js/faker

		Import into app.component.ts
      -->randomText : faker.lorem.sentence();

 

#Step 4 : Create a method 

					userInput(el : String){

						consloelog(el);

						this.input = enteredText;

						}



#A method to Compare the user Input with the random input



# Step 5 :  Create a method compare

					compare(rl:String, el: String){

						if(!el)

							retrun 'Pending';

						if(rl === el)

							return 'Correct'

						else

							retrun 'Incorrect'

					}


-----------------------------------------------------------------------------------------###############################-------------------------------------------------------------------------------------------


# Typing

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.1.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

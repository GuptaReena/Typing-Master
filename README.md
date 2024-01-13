# Typing Master 

# Step1 : Create a angular project : ng new typing

				Install BootStrap : npm install bootstrap@5.3.2



# Step 2 : Configure bootstrap.min.css file in to angular.json


# app.component.html


# Step 3 : Create a card layout in your app.component.html file 

				1 Input Field

					bind metgod with your inputField 
     
					--> # text  (input) = userInput(text.value)  
          <span  [class] = compare(rl, el[input])  *ngFor = let rl from randomText.split(''), let input = index;"></span>





# app.Component.ts

A method to take an input from user

 enteredText : String = ' ';



# install npm i @faker-js/faker
		Import into app.component.ts
      -->randomText : faker.lorem.sentence();

 
# Step 4 : Create a method 

					userInput(el : String){

						consloelog(el);

						this.input = enteredText;

						}

# A method to Compare the user Input with the random input

# Step 5 :  Create a method compare

					compare(rl:String, el: String){

						if(!el)

							retrun 'Pending';

						if(rl === el)

							return 'Correct'

						else

							retrun 'Incorrect'

					}




 # OUTPUT 
 
![img11](https://github.com/GuptaReena/Typing-Master/assets/151419809/90e04ec2-fbf7-4995-b036-5771d23dad1e)


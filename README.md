# Statistics web application that makes use of switch-statements

<div style="text-align:center;">
  <img src="/img/web-app.png" alt="site">
</div>

# Description
we will build a web application that will allow us to understand what Switch Statements are and when we should use them. For this web application, we will calculate number statistics given a range of numbers keyed in by the user. The application will consist of an input and a button element. We will be writing external CSS and JavaScript for this project.   The web application will take in a list of numbers that the user will enter. These numbers can be placed in any order separated by a comma. Once the user has entered their numbers, users can use the input to choose the type of statistics they would like to calculate from the list of numbers they have entered. From there, we can use the Switch Statement to determine which formula we would want to apply to the list of numbers provided to us. 

# What are switch-statements
We will now learn the syntax of a Switch statement. Below is an example of how a Switch statement should look like.


switch (value){
	case “one”:
		<code>
		break;
	case “two”:
		<code>
		break;
	default:
		<code>
		break;
}


From the code above, you may notice that a Switch Statement mimics closely to If-Else Statements. The stark difference between the If Statements and a Switch Statement is that an If Statement is normally used to apply the code when certain criteria are met. However, a Switch Statement is used to determine a certain preset value based on the value supplied on the first line of the switch statement. In lines 2 and 5 of the code above, you may notice that the preset value is “one” and “two”. This is when we are hoping to catch when the “value” variable of line 1 meets those preset values. These are also known as cases. 

Just like an If Statement's “else” clause, we also have a similar function in the Switch Statement syntax. In line 7, we also have a default case to catch any occurrence that has yet to be caught by the preset cases above. The default statement in the Switch statement is optional. 

In lines 4, 7 and 10, we used the break keyword. This is to distinguish the difference between the code between the various cases. Without the breaks, this could cause a waterfall effect. Switch statements are also used to validate conditions. In those cases, some values coincide with other cases within the switch statement. This may cause your algorithm to behave in an unexpected manner. 


To set up the development environment and run the web application locally, follow these steps:

1. Clone the GitHub repository:
    ```shell
   git clone https://github.com/Justice-source/Statistics-web-app.git
    
2. Install the dependencies:
   ```shell
    npm install

3. Open the html file with a browser of choice, I recommend brave browser.
4. Start inputing nubers with the correct syntax and chose a statistic option of your choice.

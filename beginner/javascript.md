<!-- # Javascript Technical Assessment  

- Fork the [javascript track assessment](https://github.com/she-code-africa/javascript-ta).
- Clone the repository to your local computer.
- Add your solution to the specificied position.
- Commit your solution.
- Push your update to your repository.
- Submit your repository URL on the provided google form.
- NOTE: make sure to follow the instruction on the readme.md/README.md

- Using Javascript, write a function that checks if a number is a Prime number or not and returns True/False.

Note: A prime number(or a prime) is a positive integer that is only divisible by 1 and itself. For example, 2, 3, 5, 7, 11 are the first few prime numbers.

## Submission: 

- Push your solution to the github repo created

- submit the URL on the application form here: [Cohort 6 Application](http://shecodeafrica.org/events) 

*Good luck!* -->

# this is my solution, i choose this method because the foundation of identifying every number is using 2 and 3(more odd or even number were gotten from the multiple of these numbers),these numbers determines if a number is even or odd,therefore if i can filter out the even and odd numbers i can easily get to pick prime numbers out. what makes a prime number unique is it ability to be divided by 1 and itself. using the below method if a number can be divided by 2 or 3 without a remainder then it is a even or odd but if a number is divided by 2 and 3, and it have a remainder then it is a prime number(if you divide prime number with any other number it wil give a remainder)because prime number cannot be divided by any other number except 1 and itself.
function primeNo(number){
if((number % 2 !==0) && (number%3 !==0)){
      return true;
}else {
      return false;
}
}
console.log(primeNo(17));
console.log(primeNo(10))
console.log(primeNo(15))
console.log(primeNo(19))
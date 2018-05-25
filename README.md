# javascript-exercises
logic problems from school

// Temperature Converter

function cToF(celsius) 
{
  //This is for the Celsius Temperature
  var cTemp = celsius;
  // Formula for Getting Celsius Temperature
  var cToFahr = cTemp * 9 / 5 + 32;
  var message = cTemp+'\xB0C is ' + cToFahr + ' \xB0F.';
    console.log(message);
}

function fToC(fahrenheit) 
{
  // This is for the Fahrenheit temperature
  var fTemp = fahrenheit;
  // Formula for Celsius
  var fToCel = (fTemp - 32) * 5 / 9;
  var message = fTemp+'\xB0F is ' + fToCel + '\xB0C.';
  // instead of console.write(), it is console.log() for Repl.it
    console.log(message);
} 
cToF(60);
fToC(45);

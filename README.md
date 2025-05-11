# Greet-User-With-Prompt-Input
Greet User With Prompt Input
const greetUser = function() {
  let name = prompt("Please enter your name:");

  // Check if the user entered a name or canceled/left it empty
  if (!name) {
    name = "Guest";  // Default name if canceled or empty
  }

  // Greet the user with the entered or default name
  alert("Hello, " + name + "!");
};

// Call the function to execute it
greetUser();

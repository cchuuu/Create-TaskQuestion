Gabe:
1. This function accepts in an input, which determines the question.
function displayQuestion(input) {
    if (i < input) {
      let q = qa[i];
      console.log(q);
      clear();
      DOMSelectors.question.insertAdjacentHTML(
        "beforeend",
        `<h1>${q.question}</h1>`
      );
    }
  }

2a. The if statement checks for variables that is less than input. The let statement retrieves the the question that correlates with the i variable. 
function displayQuestion(input) {
    if (i < input) {
      let q = qa[i];
      console.log(q);
      clear();
      DOMSelectors.question.insertAdjacentHTML(
        "beforeend",
        `<h1>${q.question}</h1>`
      );
    }
  }

2b. 
displayQuestion(5) - the if state is true and  it displays the question
displayQuestion(0) - the if statement is most likely false because i will probably not be less than 0, therefore there will be no changes to the questions displayed. 

2c. Use a for loop to check over all the elements to check their validity. If it returns false, then stop the function.
   

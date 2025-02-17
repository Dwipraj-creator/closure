# closure
function outerFunction(){
  let message = "This is a massage";
  function innerFunction(){
    console.log(message)
  }
  return innerFunction;
}
const func = outerFunction()

func()

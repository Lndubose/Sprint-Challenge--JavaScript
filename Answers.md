1. The biggest difference is that map will create a new array while looping through the original array while forEach just loops through the original array.
2. A function is made of different sequences of code to return a value of some sort and it is called on the scope it is made. While a method can be called on objects and performs similarly to a function.
3.Closure is where the innermost function inside of other functions has access to all the functions above it. So, information like variable can be passed down to the innermost function but not up to the outer function.
4. The first rule is window binding where the value of "this" will be the windows value that it is calling. Next is implicit binding where the object to the left of the period is where "this" will be looking when it is being called on by a function. Next is new binding where a constructor function is referring to each of its instances by using "this" and setting them to an attribute. Last in explicit binding where a method is used like call, apply, or bind to define "this".
5. Super is used to call the methods from its parent class, so it can use them on the class that it is called upon.

# React and Forms

## React Docs - Forms

1. What is a ‘Controlled Component’?
--A controlled component is an input form element that is controlled by React.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?
--I can't find anything on this in the reading, but I would think either way is fine. I think you would only do the second if you wanted to capture the data no matter what. If you wanted finalized data the user means to submit then wait for the submit.

3. How do we target what the user is entering if we have an event handler on an input field?
--It looks like the following code with the onCHange attribute might be it.
```
<input type="text" value={this.state.value} onChange={this.handleChange} />
```
Source: https://reactjs.org/docs/forms.html

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?
--It's shorter and much easier to read.

2. Rewrite the following statement using a ternary statement:
```
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
```
--
```
x === y ? console.log(true) : console.log(false);
```
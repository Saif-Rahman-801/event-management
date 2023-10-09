<div align="center">
  <img height="60" src="https://edurev.gumlet.io/AllImages/original/ApplicationImages/CourseImages/944e5d47-8c55-4a89-91e5-22ab5f2798fc_CI.png">
  <h1>MCQ TEST</h1>
</div>

###### 1. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
let greeting;
greetign = {};
console.log(greetign);
```

- A: `{}`
- B: `ReferenceError: greetign is not defined`
- C: `undefined`

<details><summary><b>Answer: A: `{}`

</b></summary>
<p>

#### Answer: A: `{}`

<i>  greetign = {}; this line creates a new object in JavaScript and assigns the value to the greetign. now greetign is equal a empty object; That's why console.log(greetign) will print a empty object.</i>

</p>
</details>

###### 2. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
function sum(a, b) {
  return a + b;
}

sum(1, "2");
```

- A: `NaN`
- B: `TypeError`
- C: `"12"`
- D: `3`

<details><summary><b>Answer: C: `"12"`</b></summary>
<p>

#### Answer: C: `"12"` 

<i>In JavaScript when a number type value and a string type value is additioned it concatinates, here in the function we can see a is a number and b is a string; so it will concatinate and the answer will be 12 </i>

</p>
</details>

###### 3. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
const food = ["🍕", "🍫", "🥑", "🍔"];
const info = { favoriteFood: food[0] };

info.favoriteFood = "🍝";

console.log(food);
```

- A: `['🍕', '🍫', '🥑', '🍔']`
- B: `['🍝', '🍫', '🥑', '🍔']`
- C: `['🍝', '🍕', '🍫', '🥑', '🍔']`
- D: `ReferenceError`

<details><summary><b>Answer: A: `['🍕', '🍫', '🥑', '🍔']`</b></summary>
<p>

#### Answer:  A: `['🍕', '🍫', '🥑', '🍔']`

<i>In this code there is a array food and a object info, at 1st objects property favoriteFood value was 0 index of food '🍕' array, but it's replaced by "🍝"; but the array remained constant and not changed the object is changed; That's why the Answer is A  `['🍕', '🍫', '🥑', '🍔']` </i>

</p>
</details>

###### 4. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
function sayHi(name) {
  return `Hi there, ${name}`;
}

console.log(sayHi());
```

- A: `Hi there,`
- B: `Hi there, undefined`
- C: `Hi there, null`
- D: `ReferenceError`

<details><summary><b>Answer: B: `Hi there, undefined`</b></summary>
<p>

#### Answer: B: `Hi there, undefined` ?

<i>The answer is B: `Hi there, undefined`, because in the function we used the parameter name, but when the function envoked we havn't given any value to the parameters so the parameter name remained undefined </i>

</p>
</details>

###### 5. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
let count = 0;
const nums = [0, 1, 2, 3];

nums.forEach((num) => {
  if (num) count += 1;
});

console.log(count);
```

- A: 1
- B: 2
- C: 3
- D: 4

<details><summary><b>Answer:  C: 3</b></summary>
<p>

#### Answer: C: 3 

<i>The answer will be  C: 3, because we know 0 is a falsy value, in the condition we checked if num is true then increase count by 1, when num is 0 num is false so the condition won't be executed, but when num = 1 count is 1, then when num = 2, count = 1 + 1 = 2, then when num is 3, count = 2 + 1 = 3. That's why the Answer will be  C: 3 </i>

</p>
</details>

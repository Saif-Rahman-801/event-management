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

<details><summary><b>Answer: A: `{}` </b></summary>
<p>

#### Answer: A: `{}`

<i>Write your explanation 
When greetign is declared JavaScript Assigned empty value to it, that's why console.log(greetign) prints empty object
</i>

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

<i>Write your explanation here
We know when a string and number is additioned, they concatinate, in here we can see a is a number value and b is a string, so they concatinated, Ans is "12"
</i>

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

#### Answer: A: `['🍕', '🍫', '🥑', '🍔']`

<i>Write your explanation here
In here we can see a food array is declared, and a info object is created, the 1st property of info is the 0 index of array, but this is changed in the next line, the object is changed. The array remained constant; so it's not changed; That's why the Ans is A: `['🍕', '🍫', '🥑', '🍔']`
</i>

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

<details><summary><b>Answer B: `Hi there, undefined`</b></summary>
<p>

#### Answer: B: `Hi there, undefined`

<i>Write your explanation here
The ans will be B: `Hi there, undefined`, in this code, The name parameter is taken but it's not defined in the envocation, that's why the ans is B: `Hi there, undefined`
</i>

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

<details><summary><b>Answer: C: 3</b></summary>
<p>

#### Answer: C: 3

<i>Write your explanation here
In this code we can see if the num is true count will increase by 1, in the array we can see there are 4 elements, 1 element is 0, it's a falsy value, so in the condition num will be false condition won't be executed, for the other 3 elements, condition will be true, so the count will increase by 1 each time with the previous value, for 1 count = 1; for 2 count = 1 + 1 = 2, for 3 count = 2 + 1 = 3. So the ans will be C: 3
</i>

</p>
</details>

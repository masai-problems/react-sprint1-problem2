## Counter App 2.0 
Counter App which shows if the current number is "Even" or "Odd" and if its a Prime Number or Not.

## Tags
react, useState, conditional rendering, cssmodules


## Description

### Getting Started

1. Fork this repository.
2. Clone the forked app from your github account.
3. navigate inside the clone repository folder and run following command.
   - `npm install` - To install the dependencies
   - `npm start` - To Start running the application.

## Screenshot of the Application:
<img width="1330" alt="Screenshot 2022-07-01 at 7 47 19 PM" src="https://user-images.githubusercontent.com/86409991/176912347-0b8ec838-9fa3-486b-97f2-7f212e11f8b7.png">


## Features to build

1. The Application should have a `counter` with initial value set to `0`. 
    - A `span` with `data-testid="counter` already exists in the boilerplate.

2. The Application should have three buttons
   - All three buttons are already in the boilerplate with the following `data-testid`
   - `plusonebtn`: This button should increment the count by one.
   - `minusonebtn`: This button should decrement the count by one. This button should be disabled if the count is equal to zero.
   - `resetbtn`: This button should reset te counter to zero.

3. The Application should display if the number is `odd-or-even`. 
    - a span with `data-testid="odd-or-even"` is already present in the boilerplate. The span should display `Even` or `Odd` depending on the counter value. 
    - These texts are case sensitive so be sure to cross check.

4. The Application should display if the number is `Prime` or Not.
    - a span with `data-testid="is-prime"` is already present in the boilerplate. The span should display `true` or `false` depending on the counter value.
    - **NOTE:** 0 and 1 are not Prime numbers.
    - These texts are case sensitive so be sure to cross check.

## General Instructions (**_IMPORTANT_**)

1. Do not use Global CSS, instead use `<componentName>.module.css` convention for Css in that file.
2. Do Not Remove `data-testid="xxxx"` or `data-cy="xxxx"` from anywhere, this are used by testing tools to test your code, removal of this will lead to low score.
3. Make sure you use only the given components and dont create new files and folders as changing component name, structures might result in giving you zero marks.


### Learning Objectives

1. Why and what is react?

2. Able to use CRA  and run the application.

3. Basic understanding of JSX.

4. Difference between State and props.

5. Conditional rendering.

6. handling basic onClick events.

7. Difference between global CSS and module.css
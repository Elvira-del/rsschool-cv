# Elvira Krutova

## Contacts
- [LinkedIn](www.linkedin.com/in/elvira-krutova-43a01428a)
- [Telegram]([@krasnoe_soInce](https://t.me/krasnoe_soInce))

## Skills
- React
- TypeScript
- JavaScript
- HTML
- CSS
- Git
- Figma

## Code examples

```
 function sortArray(array) {
  const sortedResultArr = [];
  const oddArr = [];  
  let idxElemOdd = 0;
  
  for (let i = 0; i < array.length; i++) {
    if (array[i] % 2 !== 0) {
      oddArr.push(array[i]);
    }
  }  
  
  const sortedOddArr = oddArr.sort((a, b) => a - b);  
  
  for (let j = 0; j < array.length; j++) {
    if (array[j] % 2 !== 0) {
      sortedResultArr.push(sortedOddArr[idxElemOdd]);
      idxElemOdd += 1;
    } else {
      sortedResultArr.push(array[j]);
    }
  }  
  
  return sortedResultArr;
}
```

## Experience

- Pet-project - [Glassmorphism Sign In/Sign Up form](https://form-kappa-eight.vercel.app/) (Next.js, TypeScript, Auth.js, CSS Modules, Zod)
- Pet-project - [ToDo list](https://elvira-del.github.io/todo/) (React, TypeScript, Styled-components, Effector)
- Charity project for Hackathon in the team #3 - [Shoot Children' Scares](https://hackathon-team3-five.vercel.app/) (Next.js, CSS Modules)

## Education

- Murmansk Academy of Economics and Management, Murmansk
  - Management, State and municipal administration
- The Rolling Scopes
  - The Rolling Scopes, JS/FE Pre-School 2022Q2
- Skillbox
  - Frontend Developer Profession from Zero to PRO

## Languages

- Russian - Native
- English - A2
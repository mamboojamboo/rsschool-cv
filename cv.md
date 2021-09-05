# rsschool-cv

## Personal Data:

Address: Russia, Moscow  
Phone: +7.915.229.3281  
Telegram: @afoninmv

## Stack:

HTML5, CSS3, Less, Sass, Styled-components, JavaScript, TypeScript, React, React-Hooks, Redux

## Code Example:

```javascript
const getFirstUniqueChar = (string) => {
    const hashTable = {};

    for (let id = 0; id < string.length; id++) {
        !hashTable[string[id]]
            ? hashTable[string[id]] = 1
            : hashTable[string[id]]++;
    }

    for (let id = 0; id < string.length; id++) {
        const elem = string[id];
        if (hashTable[elem] === 1) return id;
    }

    return -1;
};
```

## Work Experience:

May 2021 - Current: Frontend developer, iTeco  
Aug 2020 - May 2021: Frontend developer, StartUp  
Feb 2020 - Jul 2020: Frontend developer, Megafon  
Jan 2019 - Feb 2020: Frontend developer, Freelance

## Education:

2010 - Russian State University of Trade and Economics / Management

## Languages:

English - Intermediate `(B2)`  
German  - Beginner `(A1)`
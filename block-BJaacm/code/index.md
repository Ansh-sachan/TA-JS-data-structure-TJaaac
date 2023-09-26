```js
let user = {
  name: 'Arya',
  sibling: ['Robb', 'Ryan', 'John'],
};
let allBrothers = ['Robb', 'Ryan', 'John'];
let brothersCopy = user.sibling;
let usename = user.name;
let newUser = user;
```

1. Memory representation

- Create the memory representation of the above snippet on notebook.
- Take a photo/screenshot and add it to the folder `code`

<!-- To add this image here use ![name](./hello.jpg) -->

2. Answer the following with reason:

- `user == newUser;` // true because address is same
- `user === newUser;` // true because address is same
- `user.name === newUser.name;` // true because new user has same value of user
- `user.name == newUser.name;`// true because new user has same value of user
- `user.sibling == newUser.sibling;`// true because user.sibling has same value of newUser.sibling
- `user.sibling === newUser.sibling;`// true because user.sibling has same value of newUser.sibling
- `user.sibling == allBrothers;` // false because user and all brothers has different address
- `user.sibling === allBrothers;` // false because user and all brothers has different address
- `brothersCopy === allBrothers;` // false because brothersCopy and all brothers has different address
- `brothersCopy == allBrothers;`  // false because brothersCopy and all brothers has different address
- `brothersCopy == user.sibling;`//true because brotherscopy has same value of user
- `brothersCopy === user.sibling;`//true because brotherscopy has same value of user
- `brothersCopy[0] === user.sibling[0];`//true because brotherscopy[0] has same value of user
- `brothersCopy[1] === user.sibling[1];`//true because brotherscopy[1] has same value of user
- `user.sibling[1] === newUser.sibling[1];`//true because new user sibling has same value of user sibling

# Randomize
You can use this NPM package to retrieve random words.

## Usage
Get a random word
```
console.log(randomize());
//returns a random word
```

Get a certain amount of words
```
console.log(randomize({amount: 5}));
//returns a random string containing 5 words
//ex: explain doll popular future
```

Get a word with a specific character length
```
console.log(randomize({wordWithLength: 3}))
//returns a random word with exact length of 3
//ex: hat
```

Get a word with a maximum character length
```
console.log(randomize({wordWithMaxLength: 5}))
//returns a random word that doesn't exceed 5 characters
```

Get a reversed word
```
console.log(randomize({reverse: true}))
//returns the reverse of a random word
//ex yenom (reverse of 'money')
```

Get a word that is a palindrome
```
console.log(randomize({palindrome: true}))
// returns a random word that is a palindrome
// ex: civic
```
This is a sample NPM module created to accompany the Learn Enough JavaScript to Be Dangerous tutorial, which was created by Michael Hartl.

The module can be used as follows:

$ npm install --global toninjaa-palindrome
$ vim test.js
let Phrase = require("toninjaa-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true

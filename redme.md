https://github.com/ProgrammingHero1/english-janala-resources
https://openapi.programming-hero.com/api/levels/all

https://github.com/ProgrammingHero1/english-janala-resources
⚡ API Endpoints
Get ⚡ All Levels
https://openapi.programming-hero.com/api/levels/all
Get ⚡ Words by Levels
https:// openapi.programming-hero.com/api/level/{id}
https://openapi.programming-hero.com/api/level/5
Get ⚡ Words Detail
https:// openapi.programming-hero.com/api/word/{id}
https://openapi.programming-hero.com/api/word/5
Get ⚡ All Words
https://openapi.programming-hero.com/api/words/all

function pronounceWord(word) {
const utterance = new SpeechSynthesisUtterance(word);
utterance.lang = "en-EN"; // English
window.speechSynthesis.speak(utterance);
}

more practice: search: mealdb

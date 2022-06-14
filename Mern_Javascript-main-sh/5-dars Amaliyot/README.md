```js 
let NumberOfNews = +prompt("Siz qancha yangilik ko'rdingiz?");
const a = prompt("Oxirgi ko'rgan yangiliklarizdan biri?")
const b = prompt("Unga qancha baho bergan bo'lar edingiz?");

const personalNewsDB = {
  count: NumberOfNews,
  news: {},
  actors: {},
  genres: [],
  privat: false,
};

personalNewsDB.news[a] = b;
console.log(personalNewsDB);
bu yeda biz ozgaruvchidan foydalanib objekt tuzib oldik va obj ni ichida arreydan foydalanib logdan kordik
 ```
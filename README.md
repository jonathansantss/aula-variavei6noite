let nome = prompt("qual seu nome?");
let anonascimento = prompt("qual o ano do seu nascimento");
let anoatual = prompt("ano atual");

console.log("nome:", nome);
console.log("idade:", (anoatual -anonascimento));
console.log("e maior de idade?", ((anoatual -anonascimento) >=18));
console.log("idade em 2050", ((2050-anonascimento)));


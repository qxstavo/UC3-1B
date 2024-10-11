# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atividades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

array, if else, function, html, css, parseInt, indexOf

## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detalhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

atividade de criar um jogo (pokemon) foi enviada por joao barboza

https://codepen.io/soas/pen/bGXpQzj

function soma(num1, num2) {
  return num1 + num2;
}
function menos(num1, num2) {
  return num1 - num2;
}

console.log(soma(7, 2));

const compra1 = prompt("Qual o valor da primeira compra?")
const compra2 = prompt("Qual o valor da segunda compra?")

const compra1Formatada = parseInt(compra1)
const compra2Formatada = parseInt(compra2)

if (compra1 > compra2) {
  console.lpg(soma(compra1, compra2))
} else if (compra1 < compra2) {
  console.log(menos(compra1, compra2));
} else {
  console.log("erro po")
}

https://codepen.io/soas/pen/VwJgMje

//ATIVIDADE: em um deposito precisam achar o numero da caixa de um macarrao especifico. insira o nome do macarrao e RECEBA o numero da caixa

6;

let macarrãoprompt = prompt("qual macarrão você deseja encontrar?");

while (macarrou == false) {
  const macarrãos = [
    "0",
    "penne",
    "talharim",
    "yakisoba",
    "parafuso",
    "linguine",
    "fettucine",
    "macarrão de arroz"
  ];

  let pos = macarrãos.indexOf(macarrãoprompt);

  if (pos == -1) {
    macarrãoprompt = prompt("tente outro macarrão");
  } else {
    console.log(pos);
    macarrou = true;
  }
}


https://codepen.io/soas/pen/jOjXwNg

const livros = [
  "Javascript Assertivo",
  "Engenharia de Testes",
  "Clean Code",
  "Scrum",
  "Guia HTMLS e CSS3",
  "Mongo08"
]

const hqs = [
  "Superman",
  "X-Men",
  "Vingadores",
  "Batman",
  "Mulher Maravilha",
  "Feiticeira Escarlate"
];

const juntarLivros = livros.concat(hqs)

console.log(juntarLivros)

console.log(livros.indexOf("Javascript Assertivo"));

console.log(livros.includes("Javascript Assertivo"));

https://codepen.io/soas/pen/dyBzWZK

var nome = "janilda"
const a = 5 * 2
const b = 10 - 1
const c = 15 / 2
const d = 2 * 3

const total = (a * b * c - d)
console.log(`ola senhora o resultado é ${total}`)

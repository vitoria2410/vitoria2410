function setup() {
  createCanvas(400, 400);

  let palavras = ["Caminhante", "Caminho", "Caminha"];

  palavra = random(palavras);
}
let palavra;

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();

  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();

  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}

function palavraAleatoria(){

}

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function palavraAleatoria(){
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}
function draw() {

  inicializaCores();

  // ... parte restante do código
}
function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}
function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}
function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function palavraAleatoria(){
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}
function palavraAleatoria(){
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  return random(palavras);
}

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function palavraAleatoria() {
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  return random(palavras);
}

function inicializaCores() {
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER);
}

function draw() {
  inicializaCores();

  let maximo = width;
  let minimo = 0;
  // mouseX, 0, width ==> 0, palavra.length

  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  //console.log(quantidade);
  let parcial = palavra.substring(0, quantidade);
  text(parcial, 200, 200);
}
function setup() {
  createCanvas(400, 400);

  let palavras = ["Caminhante", "Caminho", "Caminha"];

  palavra = random(palavras);
}

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();

  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();

  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}

function palavraAleatoria(){

}

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function palavraAleatoria(){
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}
function draw() {

  inicializaCores();

  // ... parte restante do código
}
function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function palavraAleatoria(){
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}
function palavraAleatoria(){
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  return random(palavras);
}

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function palavraAleatoria() {
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  return random(palavras);
}

function inicializaCores() {
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER);
}

function draw() {
  inicializaCores();

  let maximo = width;
  let minimo = 0;
  // mouseX, 0, width ==> 0, palavra.length

  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  //console.log(quantidade);
  let parcial = palavra.substring(0, quantidade);
  text(parcial, 200, 200);
}
function draw() {

  inicializaCores();

  let maximo = width;
  let minimo = 0;
  // mouseX, 0, width ==> 0, palavra.length

  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  //console.log(quantidade);
  let parcial = palavra.substring(0, quantidade);
  text(parcial, 200, 200);
}
function draw() {

  inicializaCores();

  let maximo = width;
  let minimo = 0;

  text(parcial, 200, 200);
}
function draw() {

  inicializaCores();

  let maximo = width;
  let minimo = 0;

  let texto = palavraParcial();
  text(parcial, 200, 200);
}
function palavraParcial() {

}

function draw() {

  inicializaCores();

  let maximo = width;
  let minimo = 0;

  let texto = palavraParcial();
  text(parcial, 200, 200);
}
function palavraParcial() {
  let quantidade = map(mouseX, minimo, maximo, 1, palavra.length);
  let parcial = palavra.substring(0, quantidade);
}
function draw() {

  inicializaCores();

  let maximo = width;
  let minimo = 0;

  let texto = palavraParcial(0, width);
  text(parcial, 200, 200);
}
function draw() {

  inicializaCores();

  let texto = palavraParcial(0, width);
  text(texto, 200, 200);
}
function palavraParcial(minimo, maximo) {
  let quantidade = map(mouseX, minimo, maximo, 1, palavra.length);
  let parcial = palavra.substring(0, quantidade);
  return parcial;
}

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function palavraAleatoria(){
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  return random(palavras);
}

function inicializaCores() {

  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER);
}

function palavraParcial(minimo, maximo) {
  let quantidade = map(mouseX, minimo, maximo, 1, palavra.length);
  let parcial = palavra.substring(0, quantidade);
  return parcial;
}

function draw() {

  inicializaCores();

  let texto = palavraParcial(0, width);
  text(texto, 200, 200);
}
function modoNoturno(horario) {
  if (horario > 18) {
    console.log("Você precisa ligar o modo noturno!");
  } else {
    console.log("Modo noturno não é necessário neste momento.");
  }
}

modoNoturno(15);
modoNoturno(20);
function filmesParaAssistir(diaDaSemana, genero) {

  // ...

  return sugestaoFilme;
}

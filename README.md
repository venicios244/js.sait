function setup() {
    createCanvas(600, 400);
}

function draw() {
    background(0);
    circle(0, 0, 50);
}let xBolinha = 300;
let yBolinha = 200;
let diametro = 15;

function setup() {
    createCanvas(600, 400);
}

function draw() {
    background(0);
    circle(xBolinha, yBolinha, diametro);
}function draw() {
    background(0);
    circle(xBolinha, yBolinha, diametro);
    xBolinha = xBolinha + 1;
}let xBolinhaxBolinha = 300;
let yBolinha = 200;
let diametro = 15;

let velocidadeXBolinha = 6;
let velocidadeYBolinha = 6;

function setup() {
    createCanvas(600, 400);
}

function draw() {
    background(0);
    circle(xBolinha, yBolinha, diametro);
    xBolinha += velocidadeXBolinha;
    yBolinha += velocidadeYBolinha;
}

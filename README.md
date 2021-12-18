# uc-8ar2
let numeroAlunos = 5;

let listaAlunos = ["Carlos", "Jardson", "Marcelo", "Vladmir", "Juan", "Wesley"]

let contador = 0;


for (let contador = 0;contador <listaAlunos.length; contador++) {
    console.log(contador)
    if(contador == 0)
    console.log(contador + ": ZERO") 
    else if (contador % 2 == 1){
        console.log(`${contador}: IMPAR`)
    } else {
        console.log (`${contador}: PAR`)
    }


}


let n = parseFloat(prompt('digite um numero'));

let contador = 0;


if(!isNaN(n)){


while(contador <= 10){
document.write( n + "x" + contador + " =  " + n * contador + "<br>");

 contador++

}
document.write("fim da tabuada")
}
else{
    alert('digite apenas numeros')
}






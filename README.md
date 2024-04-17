# Gu-a
const cadena = ["sos","cosa","reconocer"];
function auxiliar (cadena){
    const p = cadena.split('').reverse().join('');
    const contarpali = 0;
    for(let i = 0; i < p.length; i++){
        if(p[i] === cadena[i]){
            contarpali++;
        }
    }
    return contarpali;
}
console.log(auxiliar(["sos","cosa","reconocer"]))




const cad= ["sos","cosa","reconocer"];
const contapalindromes = 0;
const sonpalindromas =  
console.log(cad.filter((x) => auxiliar(x) === x.length).map(((x,y) => ( x + y.length,0))))

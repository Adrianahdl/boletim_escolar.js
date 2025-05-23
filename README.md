# boletim_escolar.js
Código Java feito no console do freeCodeCamp
function getAverage(scores) {
    let total = 0;

    // Soma todas as notas
    for (let i = 0; i < scores.length; i++) {
        total += scores[i];
    }

    // Calcula a média
    let average = total / scores.length;
    return average;
}

// Exemplos de uso
console.log(getAverage([80, 90, 100])); // Saída: 90
console.log(getAverage([70, 85, 95, 100])); // Saída: 87.5

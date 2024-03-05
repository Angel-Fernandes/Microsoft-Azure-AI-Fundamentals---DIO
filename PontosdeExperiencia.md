<!DOCTYPE html>
<html>
<body>
    <h2>Descrição</h2>
Você é um herói em um mundo mágico <br>repleto de monstros e desafios. 
<br>Sua missão agora é enfrentar <br>inimigos e ganhar pontos de experiência (XP) para se tornar mais <br>forte. A cada vitória, você ganha XP <br>e se aproxima de se tornar um <br>lendário campeão.

<p><b>Tarefa:</b> Para calcular a quantidade de XP ganhos, o programa precisa considerar o nível do monstro e a dificuldade da batalha. A fórmula num1 * num2 * 100 é usada para calcular essa quantidade com base nos valores fornecidos.</p>

<h3>Explicação:</h3>
num1: Este é o nível do monstro. Quanto maior o nível do monstro, mais XP você ganhará ao derrotá-lo. Portanto, multiplicar o nível do monstro por um valor maior ajudará a refletir o aumento da recompensa de XP para monstros mais poderosos.

num2: Este é o valor da dificuldade da batalha, variando de 1 a 100. Quanto maior a dificuldade da batalha, mais XP você deve ganhar para enfrentar um desafio maior. Multiplicar pela dificuldade ajuda a ajustar a recompensa de XP com base na intensidade da batalha.

100: Este é o multiplicador constante que determina a escala geral de recompensa de XP. Multiplicar pelo nível do monstro e pela dificuldade aumenta a recompensa em 100 vezes o valor do nível e da dificuldade.

<h3>Entrada</h3>
O nível do monstro (um número inteiro).

A dificuldade da batalha, representada por um valor de 1 a 100 (um número inteiro).

<h3>Saída</h3>
Imprima a quantidade de XP ganhos após a batalha.



<h3>Exemplos</h3>
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.
<table border="1">
    <thead>
        <tr>
            <th>Entrada</th>
            <th>Saída</th>
        </tr>
    </thead>
    <br>

<tbody>
        <tr>
            <td>45 <br>40</td>
            <td>Voce ganhou 180000 XP!
</td><br>
        </tr>
        

 <tr>
            <td>41 <br>38</td>
            <td>Voce ganhou 155800 XP!
</td>	
        </tr>
        <br>

<tr>
            <td>15<br>20</td>
            <td>Voce ganhou 30000 XP!</td>
	
</tr>
 <br>

</tbody>
</table>

<h1>Resolução</h1>
let nivelMonstro = parseInt(gets(15));

let dificuldadeBatalha = parseInt(gets(20));



// Calcula a quantidade de XP ganhos usando a fórmula num1 * num2 * 100

let xpGanhos = nivelMonstro * dificuldadeBatalha * 100;



// Imprime a quantidade de XP ganhos após a batalha

console.log("Voce ganhou", xpGanhos, "XP!");

</body>
</html>

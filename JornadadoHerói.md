<!DOCTYPE html>
<html>
<body>
    <h2>Descrição</h2>
Você é um jovem herói que embarca em uma jornada épica<br> 
para derrotar o temido dragão que aterroriza o reino.<br> 
No entanto, você precisa atravessar uma floresta perigosa<br>
para chegar à caverna do dragão.<br> 
Cada passo é crucial, e sua jornada será determinada pela<br>
lógica afiada que você possuir.

<p><b>Tarefa:</b> Escreva um algoritmo que simule a jornada do herói pela floresta.<br>
    O herói começa em uma posição inicial e deve dar uma série de passos para<br>
    atravessar a floresta até a caverna do dragão.</p>

<h3>Entrada</h3>
A posição inicial do herói na floresta (um número inteiro).

O número total de passos que o herói deve dar (um número inteiro).

<h3>Saída</h3>
Imprima a posição final do herói após dar a quantidade de passos especificada.

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
            <td>2 <br>3</td>
            <td>Posicao final do heroi: 5
</td><br>
        </tr>
        

 <tr>
            <td>15 <br>3</td>
            <td>Posicao final do heroi: 18
</td>	
        </tr>
        <br>

<tr>
            <td>10<br>6</td>
            <td>Posicao final do heroi: 16</td>
	
</tr>
 <br>

</tbody>
</table>

    

<h1>Resolução</h1>

const posicaoInicial = parseInt(gets());

const totalPassos = parseInt(gets());



//TODO: Calcule a posição final do herói:

const posicaoFinal = posicaoInicial + totalPassos ;

if(posicaoFinal === 5){

 print("Posicao final do heroi:", posicaoFinal);

}else if(posicaoFinal === 18){

 print("Posicao final do heroi:", posicaoFinal);

}else{

 // Imprime a posição final

 print("Posicao final do heroi:", posicaoFinal);

}

</body>
</html>

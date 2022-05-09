#### FOR
<p> Fazer a revisão do carro aos 10km.</p>
<pre>
    var km;
    var revisao = 10;
    for (km = 0; km <= 10; km++){
        console.log("Pode Rodar!");
    }
</pre>
<br>
<pre>
    var alunos = [
        [6, 7, 8, 6],
        [8, 5, 6, 8],
        [10, 6, 8, 7],
        [8,8,8,8]
    ]

    var nota = 0;
    for (var i = 0; i < alunos.length; i++){
        
        nota = 0;
        aluno = alunos[i]
        console.log("Aluno: " + aluno);

        for(c=0; c < aluno.length; c++){
            nota += aluno[c];
        }

        media = nota / 4;

        if(media >= 7){
            resultado = "Aprovado";
        } else {
            resultado = "Reprovado";
        }
        console.log("Media: " + media + " - " + resultado);
    }
</pre>
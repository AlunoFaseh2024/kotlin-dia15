## Motivos por eu não ter conseguido fazer a atividade

Vamos ao começo, sábado eu fui instalar o IntelliJ IDEA Community, porém tem um problema, a versão mais atual dele só funciona em Windows 10 para cima, o meu computador usa o Windows 7. Então tive que recorrer a uma versão mais antiga dele, a versão 2020.1.4.
Eu comecei a fazer o código e parecia estar tudo funcionando normal, infelizmente, quando precisei testar o código, não aparecia a opção de rodar o código, apenas de buildar ele. Eu dei build dele, mas nada aconteceu, e não consegui executar o código.
Apenas fiz esse pedaço dele:

    class Produto(var codigo: Int, var nome: String, valor: Double, tipo: String){
    
        fun criar(){
            println("Você irá criar um novo produto, primeiro insita um código para ele. ")
    
            var id = readLine()
            var item = Produto()
            item = id
    
            var item.codigo = id.toInt()
    
            println("Insira o nome do produto")
            var item.nome = readLine()
    
            println("Insira o valor do produto")
            var item.valor = readLine().toDouble()
    
            println("Insira o tipo do produto")
            var item.tipo = readLine()
        }
    }


### Continuando

Tentei usar outras IDEs como o VSCode, pois ele tinha um plugin que ajudava com a sintax, mas não permitia rodar o código. Tentei também um plugin para o Apache NetBeans, mas o plugin não funcionava pois dava erro na hora de instalar ele. Até mesmo aquelas plataformas de código online eu tentei, mas dava um erro relacionado a main().
Seria bom que o Laboratório Virtual estivesse disponível sempre que possível para os alunos, não somente durante as aulas.

Isso é tudo o que tenho para falar, espero que entenda.

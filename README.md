# Teste de PSI Modelo

## Informação do aluno

    Nome: Raúl 

Teste termina às 09:40 (Turno 1) / 13:25 (Turno 2).

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### 1. Indica o que é impresso pelo seguinte código. Justifica a tua resposta

    char c = '\u00AE';
    Console.WriteLine($@"\n{c}\n");

P1 - Resposta

    A mensagens que vai aparecer é \n®\n pois mesmo aceitando o simbolo não aceita os comandos ficando de forma literal por isso aparece os \n não muda de linha

### 2. Considera o seguinte código

    double d = 0.3513;
    float f = 12.645;

    Console.WriteLine($"{d} + {f} = {d + f}");

### Indica a correção necessária para que o código não apresente erros. Explica porque foi necessário fazer essa correção

P2 - Resposta
float f = 12.645; estava a dar um erro pois leterais float precisa de f so fim do numero aqui a correção float f = 12.645; .

 

### 3. Escreve um programa que solicite uma string ao utilizador, e seguidamente a mostre no ecrã de forma invertida

P3 - Resposta

      string array;
            Console.WriteLine("Escreva ");
            array = Console.ReadLine();
            

            for(int i = array.Length; 0<i ; i--)    
            {
                Console.WriteLine($"{array[i]}");

            }
            

### 4. Quais são os comandos Git para configurares, de uma forma global, o teu **nome** e **email** para realização de *commits*? E se essa configuração for apenas para um repositório?

P4 - Resposta

    

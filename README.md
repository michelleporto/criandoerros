# Validação de erros por tipos



O objetivo é que a função de aumentar o seu tamanho corresponde ao número enviado como parâmetro na função. Caso contrário, um erro será lançado.

1. Crie uma função que recebe um array e um número;
2. Realize as seguintes validações:
(br)a) Se os parâmetros não foram enviados, lance um erro do tipo enviadoReferenceError(/br)
b) Se o array não for do tipo 'object', lance um erro do tipoTypeError
c)Se o número não for do tipo 'number', lance um erro do tipoTypeError
d)Se o tamanho do array for diferente do número enviado como parâmetro, lance um erro do tipoRangeError
e) Utilize uma declaraçãotry...catch
f) Filtre como chamadas de captura por cada tipo de erro usando o operadorinstanceof

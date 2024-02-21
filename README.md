# InstructionsMachine

Esta máquina deve suportar as seguintes instruções:

PUSH X: Empurra o valor X para a stack.
ADD: Adiciona os dois valores no topo da stack e empurra o resultado de volta.
SUB: Subtrai o valor no topo da stack do próximo valor e empurra o resultado de volta.
MUL: Multiplica os dois valores no topo da stack e empurra o resultado de volta.
DIV: Divide o valor no topo da stack pelo próximo valor e empurra o resultado de volta.
DUP: Duplica o valor no topo da stack.
POP: Remove o valor no topo da stack.
SWAP: Inverte a posição dos dois valores no topo da stack.
​​Exemplo de entrada: "PUSH 3 PUSH 4 ADD DUP MUL POP SUB"
 Neste exemplo, a máquina começa com a stack vazia. Os comandos são executados sequencialmente, resultando no valor final da stack.

1º instrução: PUSH 3 => [3]
2º instrução: PUSH 4 => [3, 4]
3º instrução: ADD      => [7]
4º instrução: DUP      => [7, 7]
5º instrução: MUL     => [49]
6º instrução: POP      => []
Portanto, o resultado final é 49.
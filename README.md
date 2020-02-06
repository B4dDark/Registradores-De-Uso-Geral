# registradores-de-uso-geral
Registradores de Uso Geral

Os 8 GPRs, ou Registradores de Uso Geral, são os seguintes (por ordem de introdução na pilha ao executar a instrução PUSHAD):

    EAX - Acumulador. Usado em operações aritméticas.
    ECX - Contador. Usado em loops.
    EDX - Registrador de Dados. Usado em operações de entrada/saída e em multiplicações e divisões. É também uma extensão do Acumulador.
    EBX - Base. Usado para apontar para dados no segmento DS.
    ESP - Apontador da Pilha (Stack Pointer). Aponta para o topo da pilha (endereço mais baixo dos elementos da pilha).
    EBP - Apontador da base do frame. Usado para acessar argumentos de procedimentos passados pela pilha.
    ESI - Índice da fonte de dados a copiar (Source Index). Aponta para dados a copiar para DS:EDI.
    EDI - Índice do destino de dados a copiar (Destination Index). Aponta para o destino dos dados a copiar de DS:ESI.

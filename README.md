## 🏗️ Torre de Resgate – Desafio Final (C)

## 📖 Descrição
- Simulação de um sistema de montagem de torre de fuga em um jogo de sobrevivência.
- O jogador cadastra componentes, escolhe algoritmos de ordenação (por nome, tipo ou prioridade) e realiza busca binária para encontrar o item-chave que ativa a torre.
- O programa mede tempo de execução e comparações, permitindo comparar o desempenho dos algoritmos.

---

## ⚙️ Funcionalidades
- Cadastro de até 20 componentes
- Bubble Sort → ordena por nome
- Insertion Sort → ordena por tipo
- Selection Sort → ordena por prioridade
- Busca binária (após ordenação por nome)
- Exibição de tempo e comparações
- Menu interativo e feedback ao jogador

---

## 🧱 Estrutura de Dados
typedef struct {
    char nome[30];
    char tipo[20];
    int prioridade;
} Componente;

---

## 🧩 Funções Principais
void bubbleSortNome(Componente[], int);
void insertionSortTipo(Componente[], int);
void selectionSortPrioridade(Componente[], int);
int buscaBinariaPorNome(Componente[], int, char[]);
void mostrarComponentes(Componente[], int);

---

## 🧮 Execução
gcc torre_resgate.c -o torre_resgate
./torre_resgate

---

## 📚 Conceitos Aplicados
- Structs e vetores
- Algoritmos de ordenação clássicos
- Busca binária
- Medição de tempo com clock()
- Contadores de comparações

---

## 👨‍💻 Autor
- Desenvolvido por: Lisa Rios
- Disciplina: Estrutura de Dados – 2025

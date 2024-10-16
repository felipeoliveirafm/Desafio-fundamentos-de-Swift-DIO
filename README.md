
# Desafio: Fundamentos de Swift - DIO

Este repositório contém o primeiro desafio do curso **Formação iOS Developer** da [DIO](https://www.dio.me/), focado nos **fundamentos de Swift** e desenvolvimento iOS.

## Descrição do Desafio

O objetivo deste desafio é colocar em prática os conceitos básicos de Swift, como constantes, variáveis, interpolação de strings, opcionais e optional binding.

## Instruções

1. **Criar um novo playground** no Xcode.
2. **Definir uma constante** com o valor inicial `"Steve"`.
3. **Definir uma variável** do tipo `String?` (opcional) com o valor inicial `"Jobs"`.
4. **Usar print com interpolação** de string:
   - Imprimir a constante e a variável opcional utilizando interpolação de strings.
   - Definir um valor padrão para a variável opcional como `"Wozniak"` ao usar a interpolação.
5. **Fazer um Optional Binding**:
   - Utilizar optional binding (`if let`) para verificar se a variável opcional contém um valor.
   - Dentro do bloco condicional, imprimir novamente a constante e o valor desembrulhado da variável opcional.

## Exemplo de Código

Aqui está um exemplo de como o código do desafio poderia ser implementado:

```swift
// 1. Definir constante com valor inicial
let nome = "Steve"

// 2. Definir variável opcional com valor inicial
var sobrenome: String? = "Jobs"

// 3. Usar print com interpolação e valor padrão
print("\(nome) \(sobrenome ?? "Wozniak")")

// 4. Optional binding para verificar se a variável tem um valor
if let sobrenomeDesembrulhado = sobrenome {
    print("\(nome) \(sobrenomeDesembrulhado)")
}
```

## Ferramentas Necessárias

- **Xcode** (versão mínima recomendada: 12.0)
- Playground do Xcode para testar o código Swift interativamente.

## Conclusão

Este desafio oferece uma ótima oportunidade para reforçar conceitos fundamentais do Swift, como o uso de constantes, variáveis opcionais e técnicas de desembrulhamento com optional binding. Ele é ideal para quem está começando sua jornada no desenvolvimento iOS.

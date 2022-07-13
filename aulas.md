# CSS TRANSITION ANIMATION

# TRANSITION
- Animação quando acontecer um evento, hover

## Transition-property
- Qual a propriedade da transição, por exemplo background-color, color, width

## Transition-duration
- Duração dessa transição, pode ser em segundos

## Transition-timing-functions
- Função do tempo de duração:
* ease - Início lento, rápido e final lento (este é o padrão)
* linear - Mesma velocidade do início ao fim
* easy-in - Início lento
* easy-out - Final lento
* easy-in-out - Início e fim lentos
* cubic-bezier(n,n,n,n) - Permite definir seus próprios valores em uma função cubic-bezier

## Transition-delay
- Quanto tempo demora para a animação começar

## Transition
transition : {property, duration, timing-function, delay}  

# ANIMATION
- Vai animar sem a interação do usuario

## keyframes
- Como se fosse uma function, 

@keyframes *nome* {
     from { começa

     }
     to {  vai

     }
}

- Chama a function no objeto que quer fazer a animação,
animation-name: *name*
animation-duration: *4s*
animation-delay: *2s* começa depois de 2seg que a página é carregada

## Animation Iteration Count
- Quantas vezes essa animação vai acontecer, ex: 1, 2 vezes ou infinite

## Animation direction
- Direção da animação:
* normal
* reverse (ao contrario)
* alternate (0 - 100, depois 100 - 0)
* alternate-reverse (100 - 0, depois 0 - 100)

## Animation timing function
- Função do tempo de duração:
* ease - inicio lento, rápido e final lento (padrão)
* linear - mesma velocidade do inicio ao fim
* ease-in - inicio lento
* ease-out final lento
* ease-in-out - inicio e fim lentos

## Animation Fill mode
- Determina o que é realizado quando a animação acabar
* forwards - para no ultimo lugar
* backward - volta para as caracteristicas antes do delay
* both - começa na primeira chave a acaba na ultima chave
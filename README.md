## Formulário para cadastro com JS puro e CSS Animation

## Desafios:
- [X] Fazer o formulário aparecer, suavemente, quando a página abrir
- [X] Fazer os campos aparecerem da esquerda pra direita, suavizando a entrada e fazendo-os entrar em movimentos distintos
- [X] Quando clicar em Login, fazer o formulário sair da tela, indo pra baixo
- [X] Remover formulário do html e não mostrar rolagem enquanto o formulário está saindo da tela
- [X] Adicionar um efeito diferente de timing para a saída do formulário
- [X] Fazer formulário dizer não-não (vibrar) caso haja campos vazios.
- [X] Criar alguns quadrados animados (que fiquem girando) e que saem de baixo da tela (fora do campo de visão) e vão para cima da tela (que saia do campo de visão também). _Detalhes_: Deve ter tamanhos diferentes, sairem em momentos diferentes, terem timing diferente, animação contínua.

8 propriedades:

animation-name: animationname; -- Nome da animação
animation-duration: 2s; -- Tempo total da animação
animation-delay: 3s; -- Tempo que a animação leva pra começar
animation-fill-mode: none; -- Depois ou antes da animação, o que acontece
animation-play-state: running; -- Vai ta rodando ou pause
animation-timing-function: ease; -- Progressão da animação (grafico de bolinhas)
animation-direction: reverse; -- Direção da animação
animation-iteration-count: infinite;

Para criar uma animação:

@keyframes nome-da-animação{
    from{

    }
    to{

    }
}

Múltiplas animações no mesmo elemento
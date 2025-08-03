# testes-composer


- [ ] Se algo falhar, comece pela leitura do log em vez de reexecutar tudo de uma vez.

## Geral

Aqui testo as duas formas de carregar código: uma biblioteca externa, baixada do registro, e uma interna, dentro do próprio projeto.

## Vídeo de apoio

Há uma gravação mostrando a instalação e o uso das duas.

## Comando auxiliar

Quando o carregamento automático precisa ser regenerado depois de mexer na estrutura de pastas:

```
composer dump-autoload -o
```

A opção otimizada gera um mapa fixo de classes, o que deixa o carregamento mais rápido em produção.
# strace

> Ferramenta de resolução de problemas para rastrear chamadas de sistema.
> Mais informações: <https://manned.org/strace>.

- Começar a rastrear um processo específico pelo seu PID:

`strace -p {{pid}}`

- Começar a rastrear um processo e filtrar a saída pela chamada de sistema:

`strace -p {{pid}} -e {{nome_da_chamada_de_sistema}}`

- Contar tempo, chamadas e erros para cada chamada de sistema e relatar um resumo na saída do programa:

`strace -p {{pid}} -c`

- Mostrar o tempo gasto em cada chamada de sistema:

`strace -p {{pid}} -T`

- Começar a rastrear o programa executando-o:

`strace {{programa}}`

- Começar a rastrar operações de arquivo de um programa:

`strace -e trace=file {{programa}}`

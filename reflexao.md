# Reflexão

## O que exatamente causou o conflito?

Nós duas alteramos a mesma linha do README.md (o título) ao mesmo tempo, sem que uma tivesse puxado a alteração da outra antes. Quando a Mariana deu push primeiro, o GitHub passou a ter uma versão que a Yasmim não tinha, então o push da Yasmim foi recusado e, no git pull, o Git não conseguiu decidir sozinho qual título manter.

## Como vocês decidiram qual versão manter?

Conversamos pelo WhatsApp e escolhemos o título da Mariana. A Yasmim abriu o README.md, apagou a outra versão e os marcadores de conflito, e depois fez o commit e o push da resolução.

## O que fariam diferente num projeto real para evitar conflitos?

Na nossa primeira tentativa, a Yasmim deu git pull antes de editar e o conflito nem aconteceu, o que mostrou que puxar as mudanças antes de começar já evita boa parte dos problemas. Num projeto real, daríamos pull sempre antes de começar e antes de dar push, combinaríamos quem mexe em cada arquivo e faríamos commits menores e mais frequentes.
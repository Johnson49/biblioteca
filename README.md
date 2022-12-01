# Padrões de commmit

## Por que devo padronizar?

Hoje como iniciante, podemos não ver a importância disso mas, sempre é bom já comerçamos a praticar boas práticas o quanto antes. Quando você começar a trabalhar em uma equipe numa empresa, cada pessoa vai ficar responsável por alguma coisa num mesmo projeto, já pensou se alguém faz alguma modificação e você quer entender o que ela fez e não não sabe por onde começar? Com os commits padronizados você consegue navegar por essas modificações e faz o trabalho ser mais produtivo.

## Legal, mas como isso vai funcionar? 

### Abaixo está a descrição do que deve ser usado em cada contexto:

* **feat**: uma nova feature (recurso) que você está adicionando a uma aplicação específica.

*	**fix**: a resolução de um bug

*	**style**: Mudanças na formatação do próprio código, como por exemplo, um espaço em branco, formatação… (não incluem mudanças no código)

* **refactor**: Commits do tipo refactor referem-se a mudanças devido a refatorações que não alterem sua funcionalidade como organizar a estrutura de diretório, renomeação de arquivos etc.

*	**test**: tudo o que for relacionado a testes

*	**docs**: tudo o que for relacionado à documentação

*	**chore**: commits do tipo chore indicam atualizações de tarefas e configurações de setup como tsconfig, eslint, jestConfig e adicionar um pacote no gitignore etc.

*	**perf** :  Commits do tipo perf servem para identificar quaisquer alterações de código que estejam relacionadas a performance.	

* **ci** : Commits do tipo ci indicam mudanças relacionadas a integração contínua (continuous integration)

### Comentário 

A descrição, juntamente com o tipo, é uma das partes mais importantes do padrão: é aqui que deve ser descrito, de maneira clara, sucinta e simplificada, o que foi realizado no commit. É recomendado que essa parte tenha, no máximo, 70 caracteres, para que não se estenda muito. 

**Exemplo**: `feat: adicionando API para cadastro de usuários`

### Escopo

O escopo do commit é uma parte opcional, curta e de fácil compreensão.  É nela que iremos dizer qual parte do código foi modificada, como indicar que fizemos alterações apenas na camada de controller de uma API. 

**Exemplo**:	`refactor(controller): modificando os endpoints`

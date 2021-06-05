# Design-patterns-go

## Creational Patterns

| Pattern | Descrição | Status |
|:-------:|:----------- |:------:|
| [Factory Method](/creational/factory.md) | Fornece uma interface para criar objetos de superclasse, mas permite que as subclasses alterem o tipo de objetos. | ✘ |
| [Abstract Factory](/creational/abstract_factory.md) | Provê uma maneira de encapsular um grupo de Factories sem especificar as classes concretas. | ✘ |
| [Builder](/creational/builder.md) | Produzir diferentes tipos e representações de um objeto usando o mesmo código de construção | ✘ |
| [Prototype](/creational/prototype.md) | Permite copiar objetos existentes sem aumentar a dependencia do código| ✘ |
| [Singleton](/creational/singleton.md) | Permite que uma classe tenha apenas uma instância de um objeto, provendo um único ponto de acesso global para essa instância. | ✘ |

## Structural Patterns

| Pattern | Descrição | Status |
|:-------:|:----------- |:------:|
| [Adapter](/structural/adapter.md) | Adapter é um padrão de projeto que permite objetos com interfaces incompatíveis colaborarem entre si | ✘ |
| [Bridge](/structural/bridge.md) | Possibilita criar um conjunto de subclasses partir de uma classe de forma hirarquicas| ✘ |
| [Composite](/structural/composite.md) | Fornece a capacidade de criar objetos de forma estruturada | ✘ |
| [Decorator](/structural/decorator.md) | Padrão que possibilita encapsular um objeto acrescentando ou modificando o comportamento do objeto original| ✘ |
| [Facade](/structural/facade.md) | Fornece uma interface simplificada para uma biblioteca | ✘ |
| [Proxy](/structural/proxy.md) | Permiti controlar o acesso ao um determinado objeto| ✘ |

## Behavioral Patterns

| Pattern | Descrição | Status |
|:-------:|:----------- |:------:|
| [Chain of Responsibility](/behavioral/chain_of_responsibility.md) | Possibilita criar um conjunto de handles, o qual recebe um "pedido" processa e repassa para o próximo handles como argumento. | ✘ |
| [Command](/behavioral/command.md) | Transforma um pedido em um objeto. Dessa forma, fornece a capacidade de parametrizar métodos com diferentes pedidos. | ✘ |
| [Iterator](/behavioral/iterator.md) | Cria um mecanismo para percorrer um conjunto de objetos sem expor as representações | ✘ |
| [Mediator](/behavioral/mediator.md) | Comunicação entre objetos, reduzindo as dependências de comunicação entre os objetos | ✘ |
| [Memento](/behavioral/memento.md) | Padrão de projeto que permite realizar o backup e o restore do estado anterior | ✘ |
| [Observer](/behavioral/observer.md) | Criar um mecanismo de notificação para todos os objetos que esteja observando um determinado objeto | ✘ |
| [State](/behavioral/state.md) | Mecanismo que possibilita que um objeto consiga alterar o próprio comportamento de acordo com a mudança de estado.| ✘ |
| [Strategy](/behavioral/strategy.md) | Encapsular algoritmos com responsabilidade similares | ✘ |
| [Template](/behavioral/template.md) | Defini o "esqueleto" do comportamento que um determinado objeto deverá possuir | ✘ |
| [Visitor](/behavioral/visitor.md) | Pattern que possibilita a criação de uma separação entre o comportamento dos objetos e o local de operação | ✘ |

## Concurrency Patterns

| Pattern | Descrição | Status |
|:-------:|:----------- |:------:|
| [Active Object](/concurrency/Active_Object.md)| |✘|
| [Balking pattern](/concurrency/Balking_pattern.md)| |✘|
| [Barrier](/concurrency/Barrier.md)| |✘|
| [Double-checked locking](/concurrency/double-checked_locking.md)| |✘|
| [Guarded suspension](/concurrency/guarded_suspension.md)| |✘|
| [Leaders/followers pattern](/concurrency/Leaders/followers_pattern.md)| |✘|
| [Monitor Object](/concurrency/monitor_object.md)| |✘|
| [Nuclear reaction](/concurrency/nuclear_reaction.md)| |✘|
| [Reactor pattern](/concurrency/reactor_pattern.md)| |✘|
| [Read write lock pattern](/concurrency/read_write_lock_pattern.md)| |✘|
| [Scheduler pattern](/concurrency/scheduler_pattern.md)| |✘|
| [Thread pool pattern](/concurrency/thread_pool_pattern.md)| |✘|
| [Thread local storage](/concurrency/thread_local_storage.md)| |✘|

Padroes de Projeto

1) Criacionais -> Os padrões criacionais fornecem vários mecanismos de criação de objetos, que aumentam a flexibilidade e reutilização de código já existente.
2) Estruturais -> Os padrões estruturais explicam como montar objetos e classes em estruturas maiores mas ainda mantendo essas estruturas flexíveis e eficientes.
3) Comportamentais -> Padrões comportamentais são voltados aos algoritmos e a designação de responsabilidades entre objetos.

* Comportamentais

7.Chain of Responsability

O que é:
O Chain of Responsibility é um padrão de projeto comportamental que permite passar a solicitação ao longo da cadeia de handlers em potencial até que um deles lide com a solicitação.

Aplicabilidade:
Utilize o padrão Chain of Responsibility quando é esperado que seu programa processe diferentes tipos de pedidos em várias maneiras, mas os exatos tipos de pedidos e suas sequências são desconhecidos de antemão.
Utilize o padrão quando é essencial executar diversos handlers em uma ordem específica.
Utilize o padrão CoR quando o conjunto de handlers e suas encomendas devem mudar no momento de execução.

Identificação:
O padrão é reconhecível pelos métodos comportamentais de um grupo de objetos que indiretamente chamam os mesmos métodos em outros objetos, enquanto todos os objetos seguem a interface comum.

Exempos de utilizacao:
javax.servlet.Filter#doFilter()
java.util.logging.Logger#log()
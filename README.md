# Resenha dos Capítulos 6 e 7 de *Engenharia de Software Moderna*

## Capítulo 6: Padrões de Projeto  
O capítulo 6 aborda os *Design Patterns* (padrões de projeto) como soluções reutilizáveis para problemas comuns em desenvolvimento de software. Esses padrões são apresentados como uma forma de organizar o código de maneira modular e eficiente, promovendo a reutilização e facilitando a manutenção. 

### Tipos de Padrões  
Os padrões descritos são divididos em três categorias principais:  
- **Padrões Criacionais**: Focados em formas eficientes de instanciar objetos, como:
  - *Factory Method* 
  - *Singleton*  
- **Padrões Estruturais**: Tratam da composição de classes e objetos, como:
  - *Adapter* 
  - *Composite*  
- **Padrões Comportamentais**: Envolvem a comunicação entre objetos, como:
  - *Observer* 
  - *Strategy*  

O capítulo enfatiza a necessidade de aplicar esses padrões com equilíbrio, evitando o chamado *overengineering* — ou seja, o uso exagerado e desnecessário de padrões, que pode tornar o software complexo e difícil de manter. A aplicação cuidadosa dos padrões melhora a legibilidade e promove uma melhor colaboração entre os membros da equipe.

---

## Capítulo 7: Arquitetura  
O capítulo 7 trata de arquitetura de software, destacando que as decisões arquiteturais impactam profundamente o desenvolvimento e manutenção de sistemas ao longo do tempo. Entre os estilos arquiteturais discutidos, destacam-se:

### Arquitetura em Camadas  
Essa arquitetura organiza o sistema em camadas hierárquicas. Cada camada tem uma função específica e só pode interagir diretamente com a camada inferior. As principais camadas incluem:
- **Interface com o Usuário** (ou Apresentação): Responsável pela interação com o usuário.
- **Lógica de Negócio**: Contém as regras e processos centrais do sistema.
- **Banco de Dados**: Gerencia o armazenamento e a recuperação dos dados.

Esse modelo facilita a manutenção e permite o reúso de componentes. A arquitetura em três camadas é uma variação comum, frequentemente usada em sistemas corporativos, onde a interface executa no cliente, a lógica de negócio no servidor e o banco de dados é acessado remotamente.

### Arquitetura MVC  
O padrão **MVC (Model-View-Controller)** é um dos destaques do capítulo. Ele organiza aplicações em três componentes:
- **Modelo**: Armazena os dados e a lógica de negócio.
- **Visão**: Define a interface gráfica e como os dados são apresentados.
- **Controlador**: Garante a interação entre o usuário e o sistema, manipulando eventos e atualizando o modelo e a visão conforme necessário.

O MVC é valorizado por sua modularidade e testabilidade, permitindo que desenvolvedores especializados em front-end e back-end trabalhem de forma independente. Além disso, sistemas MVC suportam múltiplas visões de um mesmo modelo, como um relógio digital e um analógico exibindo o mesmo horário.

### Considerações sobre Arquitetura  
O capítulo também apresenta exemplos da evolução de decisões arquiteturais ao longo do tempo, como o debate clássico entre Andrew Tanenbaum e Linus Torvalds sobre arquiteturas monolíticas e microkernels. Ele ressalta que muitas decisões de arquitetura só revelam seus impactos (positivos ou negativos) após anos de uso e evolução do sistema.

---

Esses capítulos reforçam a importância de utilizar padrões de projeto e arquiteturas bem definidas para garantir que o software seja robusto, escalável e fácil de manter. Eles também mostram como essas escolhas afetam a colaboração entre equipes e o ciclo de vida do sistema.

Para mais informações, consulte os capítulos diretamente no site oficial: [Engenharia de Software Moderna](https://engsoftmoderna.info/).
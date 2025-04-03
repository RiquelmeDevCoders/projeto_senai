# Desafio 1

VCS é a sigla para Version Control System (Sistema de Controle de Versão), uma ferramenta essencial para gerenciar o código-fonte de um projeto de software. Ele permite que desenvolvedores acompanhem e registrem alterações no código ao longo do tempo, facilitando o trabalho colaborativo e a manutenção do código.

Aqui estão três tipos populares de VCS e como eles funcionam:

1. Git
O que é: Git é um sistema de controle de versão distribuído, muito utilizado em projetos de software. Ele permite que os desenvolvedores trabalhem de forma independente em suas próprias cópias do repositório e depois façam "merge" (junção) das mudanças feitas em diferentes versões do código.

Como funciona: Com o Git, cada desenvolvedor tem uma cópia completa do repositório localmente, o que permite realizar commits e fazer alterações sem depender de uma conexão constante com um servidor. Quando os desenvolvedores finalizam suas alterações, eles podem "empurrar" essas mudanças para um repositório central, como o GitHub, e compartilhar com a equipe.

Vantagens: Permite trabalhar offline, muito rápido, e possui uma excelente capacidade de ramificação (branching) para facilitar o trabalho simultâneo de várias pessoas.

2. Subversion (SVN)
O que é: Subversion é um sistema de controle de versão centralizado. Em vez de ter uma cópia completa do repositório em cada máquina, os desenvolvedores têm uma cópia local do código, mas todas as mudanças precisam ser feitas em um servidor central.

Como funciona: Ao contrário do Git, o Subversion mantém um repositório centralizado, onde todas as versões de arquivos são armazenadas. Os desenvolvedores "checagem" (checkout) do código do servidor e depois enviam (commit) suas alterações de volta ao servidor central.

Vantagens: A centralização pode ser mais fácil de gerenciar e controlar, especialmente em ambientes empresariais ou quando a equipe é pequena.

3. Mercurial
O que é: Mercurial é outro sistema de controle de versão distribuído, similar ao Git. Ele também permite que cada desenvolvedor tenha uma cópia completa do repositório e trabalhe de forma independente.

Como funciona: Mercurial mantém um repositório completo em cada máquina de desenvolvedor e permite que as alterações sejam feitas localmente e depois sincronizadas com outros desenvolvedores. Ele é mais simples de usar que o Git, mas com funcionalidades semelhantes.

Vantagens: Menos complexo que o Git, com uma curva de aprendizado mais suave, mas ainda assim muito eficaz para gerenciamento de código em projetos colaborativos.

O que é VCS (Sistema de Controle de Versão)?
Um VCS é uma ferramenta essencial para o desenvolvimento de software. Ele registra cada alteração feita no código-fonte ao longo do tempo, de forma que é possível:

Rastrear o histórico de mudanças no código.

Colaborar de forma eficiente entre vários desenvolvedores sem sobrescrever o trabalho uns dos outros.

Reverter alterações se algo der errado, garantindo segurança e consistência no desenvolvimento.

Esses sistemas são fundamentais para a colaboração em equipes de desenvolvimento de software, pois ajudam a organizar o trabalho e reduzem o risco de perder ou corromper dados durante o processo de desenvolvimento.





# Desafio 2


Pesquisa sobre Programação Orientada a Objetos (POO) 

Aluno: Iago Riquelme 

 

 

1. Definição e Pilares da POO 

O que é Programação Orientada a Objetos (POO)? 

A Programação Orientada a Objetos (POO) é um paradigma de programação que organiza o código em estruturas chamadas objetos, que representam entidades do mundo real. Esses objetos possuem: 

Atributos (propriedades): Características do objeto (ex: cor, tamanho, nome). 

Métodos (ações): Comportamentos que o objeto pode executar (ex: calcular, salvar, imprimir). 

Quais são os quatro pilares da POO? 

Abstração – Simplificar um objeto, destacando apenas o que é essencial. 

Encapsulamento – Proteger os dados internos, expondo apenas o necessário. 

Herança – Uma classe pode herdar características de outra classe. 

Polimorfismo – Objetos diferentes podem responder ao mesmo comando de formas distintas. 

 

2. Exemplo de Abstração 

O que é Abstração? 

É o processo de identificar apenas os aspectos relevantes de um objeto, ignorando detalhes desnecessários. 

Exemplo Prático: 

Sistema de Banco – Conta Bancária 

Atributos importantes: Número da conta, saldo, titular. 

Métodos importantes: Depositar, sacar, verificar saldo. 

Detalhes ignorados: Como o banco armazena o dinheiro fisicamente, interface gráfica. 

 

3. Exemplo de Encapsulamento 

O que é Encapsulamento? 

É o princípio de proteger os dados internos de um objeto, permitindo acesso apenas por meio de métodos controlados. 

Exemplo Prático: 

Controle de Acesso em um Sistema de Login 

Dados privados: Senha do usuário. 

Métodos públicos: validarSenha(), alterarSenha(). 

Benefício: Impede que a senha seja modificada diretamente, garantindo segurança. 

 

4. Exemplo de Herança 

O que é Herança? 

É quando uma classe (subclasse) herda atributos e métodos de outra classe (superclasse), permitindo reutilização de código. 

Exemplo Prático: 

Sistema de Veículos 

Classe Pai (Veículo): Possui atributos como marca, modelo e métodos como acelerar(), frear(). 

Subclasses: 

Carro: Herda de Veículo e adiciona quantidadeDePortas. 

Moto: Herda de Veículo e adiciona cilindradas. 

 

5. Exemplo de Polimorfismo 

O que é Polimorfismo? 

É a capacidade de um mesmo método se comportar de maneira diferente em classes distintas. 

Exemplo Prático: 

Sistema de Formas Geométricas 

Método calcularArea(): 

Em um Retângulo, calcula base × altura. 

Em um Círculo, calcula π × raio². 

Mesmo nome, implementações diferentes. 

 

6. Vantagens da POO 

Reutilização de código (evita repetição). 

Organização melhorada (código mais modular). 

Manutenção facilitada (mudanças em um objeto não afetam outros). 

Segurança de dados (encapsulamento protege informações). 

Escalabilidade (fácil adaptação para sistemas maiores). 

 

Conclusão: 
A POO é um modelo eficiente para desenvolvimento de software, tornando o código mais organizado, seguro e fácil de expandir. Seus pilares (Abstração, Encapsulamento, Herança e Polimorfismo) são fundamentais para criar sistemas robustos. 

Fontes de pesquisa: 

Livros de programação (ex: "Use a Cabeça! POO"). 

Documentação de linguagens como Java e C#. 

Tutoriais online (MDN, W3Schools). 
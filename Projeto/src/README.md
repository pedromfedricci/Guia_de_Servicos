Arquivos .java do Projeto.

MVC:

    Projeto foi desenvolvido seguindo o desenho model-view-controller.

Construtores: 

    classe Usuario, classe Prestador, classe Cliente, 
    classe Banco, classe Colecao.

Sobrecarga de Métodos:

    Métodos da class Console, Colecao, Senha.

Herença simples:

    Prestador e Cliente são subclasses de Usuario.

Container:

    ArrayList é utilizada na classe Colecao para carregar objetos na memória virtual para operações.
    
Classe Abstrata:

    Classe Usuario é mantida como abstract pois não deve ser instanciada, métodos são implementados pelas subclasses.

Polimorfismo:

    Referência da classe Object pode ser utilizada para indicar objetos Prestador e Cliente, que são subclasses.
    Essa referência então apresenta o comportamento "toString()" sobrescrito pela classe concreta referenciada.
    Uso é feito na classe Colecao.
    
    Referência da classe Usuario pode ser utilizadad para indicar objetos Presetador e Cliente, que são sublcasses.
    Essa refêrencia então apresenta o comportamento "preencherCampos()" sobrescrito pela classe concreta referenciada.
    Uso é feito na classe MenuOperadorColecao.

classDiagram
    class Funcionario {
        - int funcionarioId
        - String nome
        - String password
        - String cargo
        - String contato
        - String email
        + fazerLogin(usuario: String, senha: String): boolean
        + registrarFuncionario()
        + registrarCliente()
    }
    
    class Permissao {
        - int permissaoId
        - String nome
        - String descricao
    }
    
    class veiculo {
        - int ID_do_Cliente
        - Date Data_de_Registo
        - String marca
        - String modelo
        - int ano
        - String Matricula
    }
    
    class HistoricoServico {
        - int ID_do_Cliente
        - int ID_de_Veiculo
        - Date Data
        - String Estado_do_Carro
        - float preco
        - String Opcoes_de_Servico
    }

    class Cliente {
        - int clienteId
        - String nome
        - String contato
        - String email
        - String morada
        - List<veiculo> veiculos
    }
    
    Funcionario "1" --> "0..*" veiculo : insere
    Funcionario "1" --> "0..*" Permissao : possui
    Funcionario "1" --> "0..*" Funcionario : regista
    Funcionario "1" --> "0..*" Cliente : regista
    veiculo "1" --> "0..*" HistoricoServico : possui
    Cliente "1" --> "0..*" veiculo : possui

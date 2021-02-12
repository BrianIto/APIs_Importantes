<h1>APIs Importantes</h1>
<p>Um repositório para guardar em forma de lista APIs importantes para uso geral e no dia-a-dia, a lista acompanha documentação simples do retorno caso seja uma API simples. Como o projeto ainda é novo, ainda não irei adicionar APIs complexas.</p>
<p><a href="https://buscacepinter.correios.com.br/app/cep/carrega-cep.php?cep=69094-700">API dos Correios para buscar CEP</a> -> <code>"https://buscacepinter.correios.com.br/app/cep/carrega-cep.php?cep=" + numero do CEP</code></p>
<p>Exemplo de Response: </p>
<code><pre>{
    "erro": false,
    "mensagem": "DADOS LOCALIZADOS COM SUCESSO.",
    "total": 1,
    "dados": [
        {
            "uf": "AM",
            "localidade": "Manaus",
            "locNu": "2431",
            "localidadeSubordinada": "",
            "logradouroDNEC": "Rua Professor Coroelando Durand",
            "logradouroTextoAdicional": "",
            "logradouroTexto": "",
            "bairro": "Cidade Nova",
            "baiNu": "",
            "nomeUnidade": "",
            "cep": "69094700",
            "tipoCep": "2",
            "numeroLocalidade": "2431",
            "situacao": "",
            "faixasCaixaPostal": [],
            "faixasCep": []
        }
    ]
}</pre></code>

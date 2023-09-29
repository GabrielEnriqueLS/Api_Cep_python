# Api_Cep_python

# Consulta de CEP usando a API dos Correios em Python

Este é um projeto em Python que permite consultar informações de um CEP (Código de Endereçamento Postal) utilizando a API do ViaCEP. Com esta aplicação, você pode inserir um CEP e obter informações detalhadas sobre o endereço associado a esse código postal.

## Pré-requisitos

Antes de começar, certifique-se de que você tenha os seguintes pré-requisitos instalados:

- Python 3.x
- Biblioteca requests (para fazer solicitações HTTP à API do ViaCEP)

Você pode instalar a biblioteca requests usando o pip:

```bash
pip install requests
```

## Como usar

1. Clone este repositório para o seu ambiente local:

```bash
git clone https://github.com/GabrielEnriqueLS/Api_Cep_python.git
```

2. Navegue até o diretório do projeto:

```bash
cd ConsultaCep
```

3. Execute o script Python:

```bash
python ConsultaCep.py
```

4. A aplicação solicitará que você insira um CEP. Digite o CEP desejado e pressione Enter.

5. A aplicação fará uma solicitação à API dos Correios e exibirá as informações do endereço correspondentes ao CEP fornecido.

## Exemplo de Uso

```
Digite um CEP: 12345-678
```

```
Informações do endereço para o CEP 12345-678:

Logradouro: Rua Exemplo
Bairro: Bairro da Amostra
Cidade: Cidade Demonstrativa
Estado: UF
```

## Limitações

- A API dos Correios pode estar sujeita a mudanças na estrutura de resposta. Este projeto assume o formato de resposta atual da API e pode não funcionar corretamente se houver alterações na API dos Correios.

- Certifique-se de estar em conformidade com os termos de uso da API dos Correios ao usar este projeto em produção.

## Contribuições

Contribuições são bem-vindas! Se você quiser melhorar este projeto ou corrigir problemas, sinta-se à vontade para enviar um pull request.

## Autor

[Gabriel Enrique](https://github.com/GabrielEnriqueLS)

## Agradecimentos

- [Via Cep](https://viacep.com.br/)
- [requests - Biblioteca Python](https://docs.python-requests.org/en/latest/)
- [GitHub - Modelos de README](https://github.com/othneildrew/Best-README-Template)

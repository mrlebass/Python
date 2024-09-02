# Parse Access Log - Python Notebook

Este projeto é um notebook Jupyter desenvolvido para realizar a análise de arquivos de log de acesso. Ele inclui o carregamento, parsing e conversão de dados de logs para facilitar a análise e visualização das informações.

## Índice

- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Funcionalidades](#funcionalidades)
- [Contribuindo](#contribuindo)
- [Licença](#licença)


## Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/usuario/nome-do-projeto.git
    cd nome-do-projeto
    ```

2. Crie um ambiente virtual (opcional, mas recomendado):

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Instale as dependências necessárias:

    ```bash
    pip install -r requirements.txt
    ```

4. Certifique-se de que o arquivo de log de acesso (`access_mng3node.log`) esteja no caminho correto especificado no notebook.

## Como Usar

Abra o notebook Jupyter:

```bash
jupyter notebook ParseAsscessLogo.ipynb
```


## Execute as células passo a passo para:

1. Carregar e configurar bibliotecas e variáveis globais. <br>
2. Executar métodos auxiliares para parsing e conversão de dados. <br>
3. Carregar o arquivo de log e executar as análises. <br>


## Funcionalidades

1. Parsing de Data e Hora: Converte timestamps de log em objetos datetime. <br>
2. Conversão de Dados: Converte valores de status, tempo de resposta e bytes transferidos para formatos numéricos úteis. <br>
3. Carregamento de Logs: Carrega arquivos de log em um DataFrame do Pandas para fácil manipulação e análise. <br>

## Contribuindo
### Se quiser contribuir:

1. Faça um fork do repositório. <br>
2. Crie uma branch para sua feature (git checkout -b feature/nova-feature). <br>
3. Commit suas alterações (git commit -m 'Adiciona nova feature'). <br>
4. Faça um push para a branch (git push origin feature/nova-feature). <br>
5. Abra um Pull Request. <br>

## Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.  <br>


```perl
Esse `README.md` oferece uma estrutura clara para que outros desenvolvedores possam entender
e usar seu projeto de maneira eficaz. 
Ajuste conforme necessário para se adequar ao conteúdo
e ao propósito específico do seu notebook.
```

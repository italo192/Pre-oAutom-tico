# PreçoAutomático

PreçoAutomático é um script em Python que automatiza a captura de preços online e atualiza uma planilha Excel periodicamente. Utilizando Selenium e openpyxl, este projeto permite monitorar o preço de um produto específico e registrar as informações em uma planilha.

## Funcionalidades

- Captura automática do preço de um produto em um site especificado.
- Atualização de uma planilha Excel com as informações coletadas.
- Execução periódica a cada 30 minutos.

## Requisitos

- Python 3.x
- Selenium
- openpyxl
- schedule

## Instalação

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/PrecoAutomatico.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd PrecoAutomatico
    ```

3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

4. Certifique-se de ter o WebDriver do Chrome instalado e configurado no PATH do sistema.

## Como Usar

1. Edite o script para definir a URL do produto que deseja monitorar:
    ```python
    site = 'URL_DO_PRODUTO'
    ```

2. Execute o script:
    ```bash
    python main.py
    ```

3. O script irá capturar o preço do produto e atualizar a planilha Excel (`desafio_destrava_dev3.xlsx`) a cada 30 minutos.

## Estrutura do Projeto

```plaintext
PreçoAutomático/
├── main.py             # Script principal
├── requirements.txt    # Dependências do projeto
└── desafio_destrava_dev3.xlsx  # Planilha Excel gerada (criada automaticamente se não existir)


## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

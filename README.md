# Previsão de Preços de Aluguéis

Este repositório contém um modelo de previsão de preços de aluguéis. O projeto inclui uma análise exploratória dos dados, construção do modelo preditivo e instruções para reproduzir os resultados.

## Estrutura do Repositório

- `eda.ipynb` - Notebook contendo a EDA (análise exploratória dos dados).
- `modelo.ipynb` - Notebook contendo a construção e treinamento do modelo preditivo.
- `test_indicium_precificacao.csv` - Arquivo de dados para testes.

## Instalação e Configuração

. Crie um ambiente virtual (opcional):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows
   ```
. Instale as dependências:
   ```bash
   pip install -r requirements.txt # Pode ser realizado em um bloco no notebook
   ```

## Como Utilizar

### 1. Executar a Análise Exploratória
Abra e execute o notebook `eda.ipynb` para visualizar insights sobre os dados.

### 2. Treinar e Avaliar o Modelo
Execute o notebook `modelo.ipynb` para treinar o modelo e analisar seu desempenho.

### 3. Testar o Modelo com Novos Dados
Uma seção 'Sua Vez' foi adicionada ao final do notebook `modelo.ipynb`, onde você pode fornecer seus próprios dados para teste. Basta editar a célula correspondente e executar para obter previsões do modelo. Basta importar o modelo `.pkl` neste repositório que deseja e utilizar o modelo.

## Contribuição
Sugestões e melhorias são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).


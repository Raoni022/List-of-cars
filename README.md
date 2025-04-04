Descrição
A ferramenta utiliza a biblioteca Requests para realizar requisições HTTP e BeautifulSoup para processar o conteúdo HTML dos websites. Dois métodos de scraping são implementados, cada um direcionado a um site diferente, para demonstrar a extração de dados de estruturas distintas.

Observação: Os seletores utilizados (classes e tags) são exemplos. Adapte-os conforme a estrutura real dos websites que deseja raspar.

Pré-requisitos

Python 3.x

Instalar as bibliotecas:

requests

beautifulsoup4


Você pode instalá-las via pip:

pip install requests beautifulsoup4

Instalação

Clone o repositório:


git clone https://github.com/seu-usuario/nome-do-projeto.git


Navegue até o diretório do projeto:


cd nome-do-projeto


Uso
Para executar o script, basta rodar o arquivo principal:

python3 scrape_vehicles.py

Ao final da execução, se os dados forem obtidos com sucesso, um arquivo chamado "vehicle_listings.csv" será gerado com as informações extraídas.

Personalização

Para adicionar novos websites ou novos campos (como localização, quilometragem), crie métodos adicionais na classe VehicleScraper seguindo o mesmo padrão.

Ajuste os seletores HTML nos métodos scrape_site_a e scrape_site_b conforme a estrutura dos sites que serão raspados.

Tratamento de Erros e Logs

O script utiliza a biblioteca logging para registrar o andamento do processo e possíveis erros.

Em caso de falha na requisição ou na escrita do arquivo CSV, as exceções são capturadas e registradas no log.

Licença
Este projeto está licenciado sob a MIT License.

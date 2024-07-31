# News Bot

## Descrição
O **PyPoder** é um projeto que automatiza a coleta das principais notícias de várias editorias, personaliza banners, gera newsletters e envia as notícias para um bot do Telegram semanalmente. Este projeto foi desenvolvido como uma ferramenta de estudo e aplicação prática de diversas bibliotecas e técnicas em Python.

## Estrutura do Projeto
- `config/`: Configurações e constantes do projeto.
- `data/`: Manipulação e filtragem de dados.
- `templates/`: Templates para geração de conteúdo.
- `utils/`: Funcionalidades utilitárias.
- `main.py`: Ponto de entrada principal do projeto.
- `requirements.txt`: Lista de dependências do projeto.
- `README.md`: Documentação do projeto.

## Como Usar

### Pré-requisitos
Certifique-se de ter o Python 3.6+ instalado em seu sistema.

### Passos para Configuração

1. Clone o repositório:
    ```sh
    git clone link url
    cd news-bot
    ```

2. Crie um ambiente virtual (opcional, mas recomendado):
    ```sh
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    ```

3. Instale as dependências:
    ```sh
    pip install -r requirements.txt
    ```

4. Configure suas credenciais e variáveis de ambiente:
    - Abra o arquivo `config/settings.py` e configure o `TELEGRAM_TOKEN`, `CHAT_ID`, `NEWS_URL` e `SECTIONS` conforme suas necessidades.

5. Execute o projeto:
    ```sh
    python main.py
    ```

## Funcionalidades

- **Coleta de Notícias**: Coleta as 10 principais notícias de cada editoria especificada.
- **Filtragem de Notícias**: Filtra as principais notícias da semana.
- **Personalização de Banners**: Cria banners personalizados para cada notícia.
- **Geração de Newsletter**: Gera uma newsletter com as notícias coletadas.
- **Postagem no Telegram**: Envia a newsletter para um chat do Telegram semanalmente.

## Tecnologias Utilizadas
- **Python**: Linguagem de programação principal.
- **Requests**: Para fazer requisições web.
- **BeautifulSoup**: Para análise de HTML.
- **Selenium**: Para automação de navegador.
- **Pandas**: Para manipulação de dados.
- **Pillow**: Para manipulação de imagens.
- **python-telegram-bot**: Para interagir com a API do Telegram.
- **APScheduler**: Para agendamento de tarefas.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests. Para grandes mudanças, por favor abra uma issue primeiro para discutir o que você gostaria de mudar.

## Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter mais detalhes.

## Agradecimentos
A todos os desenvolvedores e membros da comunidade Python que contribuíram com bibliotecas e ferramentas utilizadas neste projeto. Este projeto foi inspirado pela vontade de aprender e aplicar conhecimentos em Python para resolver problemas reais e automatizar tarefas. Tambem um agradecimento a Lucas Marques e Gabriel Morais 

## Contato
Para mais informações, dúvidas ou sugestões, entre em contato:
- Email: igorestagios@gmail.com
- LinkedIn: [Igor Rocha](https://www.linkedin.com/in/igor-rocha-0bb14521a/)

---

Este projeto é uma excelente oportunidade para aprender e aplicar habilidades em web scraping, manipulação de dados, automação de navegador e integração com APIs. Esperamos que você aproveite este projeto tanto quanto nós aproveitamos desenvolvê-lo!

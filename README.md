Como rodar
pip install -r requirements.txt
streamlit run app.py
Configuração da API OpenAI (para perguntas não mapeadas)
Para usar o fallback com ChatGPT, configure sua API key:

Obtenha uma API key em: https://platform.openai.com/api-keys
Renomeie o arquivo env_example.txt para .env
Edite o arquivo .env e substitua sua_api_key_aqui pela sua chave real:
OPENAI_API_KEY=sua_api_key_aqui
O sistema carregará automaticamente as variáveis do arquivo .env usando python-dotenv.

Gerar relatório PDF (opcional)
python generate_report.py

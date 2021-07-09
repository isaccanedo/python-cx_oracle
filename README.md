# Como usar este CGI

Simplesmente configure seu servidor web para servir start.py, este é um script wrapper que vai configurar o ambiente do sistema em setEnv.sh antes de iniciar a interação do oracle principal em tablespace.py.

Este código de exemplo é apenas para demonstrar o uso de cx_Oracle para se conectar a um banco de dados Oracle. Neste exemplo, uma vez conectado o python executa uma consulta SQL para obter o tamanho do espaço de tabela para todas as tabelas em seu banco de dados.

### exemplo Você precisará editar os arquivos para torná-los específicos para o seu site, mas no final deverá ser capaz de chamar o CGI via;

http: // <yourDomain> /start.py

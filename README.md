01 - aplicação scheduler, vai de um em um minuto pegar a info necessária e salva no banco de dados

sls deploy
sls invoke -f commit-message-scheduler --logger
sls invoke local -f commit-message-scheduler --logger

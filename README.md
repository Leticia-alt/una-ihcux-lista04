# una-ihcux-lista04

O try-catch é uma estrutura de controle de fluxo fundamental na programação utilizada para tratar exceções (erros em tempo de execução).Ele permite que o desenvolvedor isole códigos suscetíveis a falhas, prevenindo que um erro inesperado derrube todo o sistema. Se conecta com a Prevenção de Erros quando evita a Parada Total do Sistema (Resiliência): A principal prevenção é impedir que um erro isolado, garantindo que o usuário possa continuar usando outras funcionalidades.
 Tratamento Gracioso de Erros: o catch permite que você apresente uma mensagem "amigável" ao usuário, prevenindo a frustração e confusão.
 Monitoramento e Log (Prevenção de Erros Futuros): Ao capturar a exceção no catch, o desenvolvedor pode registrar o erro. Isso permite identificar bugs, falhas de lógica ou entradas de dados inválidas, possibilitando correções que prevenirão esses mesmos erros no futuro.
 Segurança e Limpeza de Recursos: O uso de finally previne vazamentos de memória ou arquivos travados, pois garante que recursos (banco de dados, arquivos abertos) sejam fechados mesmo se um erro ocorrer, prevenindo falhas no sistema por exaustão de recursos.

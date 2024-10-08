# node-red-cep-search
Implementação de tratamento de dados de api, como listar corretoras e buscador de cep.

Passo a Passo: Instalando e Executando no Node-RED

1. Pré-requisitos
Node.js: Certifique-se de ter o Node.js instalado em seu sistema. Você pode baixá-lo em nodejs.org.
Node-RED: Caso ainda não tenha o Node-RED instalado, abra o terminal ou o prompt de comando e execute:
npm install -g --unsafe-perm node-red

3. Iniciando o Node-RED
Após a instalação, inicie o Node-RED executando o seguinte comando no terminal ou prompt de comando:
node-red
O Node-RED será iniciado e você verá uma saída no terminal informando que ele está rodando na URL http://127.0.0.1:1880.

5. Acessando a Interface do Node-RED
Abra o seu navegador e acesse http://127.0.0.1:1880. Você verá a interface do Node-RED.

7. Importando o Fluxo JSON
No canto superior direito da interface do Node-RED, clique no menu (três linhas horizontais) e selecione Import.
Na janela de importação, cole o JSON do fluxo que você deseja importar. O JSON pode ser encontrado no repositório do GitHub.
Clique em Import para adicionar o fluxo ao seu espaço de trabalho.

9. Configurando os Nós
Depois de importar o fluxo, você pode precisar configurar alguns nós (como credenciais da API, se necessário).
Clique duas vezes em cada nó para abrir suas configurações e ajustar conforme necessário.

11. Implantando o Fluxo
Após configurar os nós, clique no botão Deploy no canto superior direito da interface para salvar e executar seu fluxo.

13. Testando a Aplicação
Abra um navegador e acesse os endpoints que você configurou no Node-RED, como /corretoras, /cep-search ou /cep/:cep, para testar se tudo está funcionando corretamente.

15. Solução de Problemas
Se você encontrar algum erro, verifique a aba de debug no Node-RED (canto superior direito) para ver as mensagens de erro e ajustar o fluxo conforme necessário.

Agora você deve ter seu fluxo Node-RED rodando e funcionando corretamente. Certifique-se de seguir todos os passos e ajustar as configurações conforme necessário.

# Criação de chat 


1. Verificar se possui o Docker instalado
2. Crie e execute o contêiner RabbitMQ
3. Uritilizanso o prompt do comtainer criado cie o usuario:
   rabbitmqctl add_user ads ads
   rabbitmqctl set_user_tags ads administrator
   rabbitmqctl set_permissions -p / ads ".*" ".*" ".*"
4. Execute os o emissor e o receptor
   

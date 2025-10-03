MANUAL DE INSTALAÇÃO - SISTEMA DE VEÍCULOS
==========================================

PASSO A PASSO COMPLETO PARA INSTALAÇÃO

1. ✅ PREPARAÇÃO DO AMBIENTE
   ╰─➤ Instale o XAMPP: https://www.apachefriends.org/

2. 📁 COPIAR ARQUIVOS
   ╰─➤ Crie a pasta: C:\xampp\htdocs\vehicle_app\
   ╰─➤ Copie TODOS estes arquivos para a pasta:
        - index.php
        - dashboard.php  
        - cadastro_veiculo.php
        - salvar_veiculo.php
        - logout.php
        - db.php
        - script.sql

3. 🚀 INICIAR SERVIDORES
   ╰─➤ Abra o XAMPP Control Panel
   ╰─➤ Clique em "Start" no Apache
   ╰─➤ Clique em "Start" no MySQL
   ╰─➤ Verifique se ficou VERDE: [Apache] 🟢 [MySQL] 🟢

4. 🗃️ CRIAR BANCO DE DADOS
   ╰─➤ Abra seu navegador
   ╰─➤ Acesse: http://localhost/phpmyadmin
   ╰─➤ Clique em "Importar" no menu superior
   ╰─➤ Clique em "Escolher arquivo"
   ╰─➤ Selecione o arquivo: script.sql
   ╰─➤ Role até o final da página
   ╰─➤ Clique em "Executar"

5. 🔐 TESTAR ACESSO
   ╰─➤ Abra uma nova aba no navegador
   ╰─➤ Acesse: http://localhost/vehicle_app/
   ╰─➤ Tela de login deve aparecer

6. 📝 PRIMEIRO LOGIN
   ╰─➤ Usuário: admin
   ╰─➤ Senha: senha123
   ╰─➤ Clique em "Entrar"

7. ✅ SISTEMA PRONTO!
   ╰─➤ Dashboard deve carregar
   ╰─➤ Clique em "Novo Veículo" para testar cadastro
   ╰─➤ Sistema está funcionando!

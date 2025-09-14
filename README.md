# Santander-Code-Girls---2025
Santander Code Girls - 2025

Resumo e comparativo sobre as funcionalidades AWS aprendidas em aula. 
📦 Amazon S3 (Simple Storage Service)
Serviço de armazenamento de objetos (arquivos, imagens, vídeos, backups).
Escalável, seguro e com alta durabilidade (99,999999999%).
Usado para hospedar sites estáticos, armazenar dados para análise, backups, etc.

⚡ AWS Lambda
Serviço de computação serverless: você executa código sem precisar gerenciar servidores.
É acionado por eventos (ex: upload no S3, chamada HTTP via API Gateway, fila no SQS).
Cobra apenas pelo tempo de execução e memória usada.

🖥️ Amazon EC2 (Elastic Compute Cloud)

Máquinas virtuais na nuvem (servidores que você pode configurar do zero).
Dá controle sobre sistema operacional, rede, segurança e softwares instalados.
Usado para hospedar aplicações, bancos de dados, sistemas corporativos, etc.

💾 Amazon EBS (Elastic Block Store)
Serviço de armazenamento em blocos para ser usado com instâncias EC2.
Funciona como um “HD/SSD” que você pode anexar a sua máquina virtual.
Pode ser persistente (mesmo desligando a instância, os dados ficam salvos).

👉 Resumindo:
S3 = guardar arquivos/objetos.
Lambda = rodar código sem servidor.
EC2 = servidor virtual completo.
EBS = disco rígido/SSD para EC2.

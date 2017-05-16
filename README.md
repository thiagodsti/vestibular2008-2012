# Vestibular 2008-2012

MySQL com dados de vestibular de 2008-2012 para a matéria de Dataware House da UFSC.

Para executar:

```docker run -d -p 3306:3306 --name my-mysql-name -e MYSQL_ROOT_PASSWORD=root -v /opt/data:/var/lib/mysql thiagods/vestibular2008-2012```
OBS: pode trocar /opt/data por outro diretório aonde deseja guardar os dados.

Mais detalhes em https://hub.docker.com/_/mysql/

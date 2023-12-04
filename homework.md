## Обновление с помощью Canary Deployment.
- необходимо создать два конфигурационных файла.
1) nginx.yaml 
![logo](nginx.png)
в конфигурации файла видим, что у нас будет создано 3 реплики, версия nginx 1.14.2. Имя deployment будет multi-delpoyment/
2) nginx1.yaml
![logo](nginx1.png)
Во втором конфигурационном файле мы видим, что будет создано 0 реплик, так же версия nginx будет 1.23.3. Имя deployment будет multi-deployment-1.
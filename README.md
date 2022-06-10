# IniciativaDevOpsAula0001

Comando para a imagem criada:
docker push benitomarculanoribeiro/conversor-temperatura:lasted

Comando para publicar imagem criada:
docker push benitomarculanoribeiro/conversor-temperatura:v2

Comando para usar um container:
docker container run -d -p 8081:8080 benitomarculanoribeiro/conversor-temperatura:lasted

Comando para duplicar uma imagem (com nome diferente):
docker tag benitomarculanoribeiro/conversor-temperatura:v2 benitomarculanoribeiro/conversor-temperatura:lasted

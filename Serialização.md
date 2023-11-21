![[Pasted image 20231121130824.png]]
### O que está acontecendo:	
1ª linha: está criando uma instancia de Example pegando os dados do request com o request.DATA
2ª linha: então verifica se ele é válido com o seriliazer.is_valid() 
3ª linha: acessa a instância do objeto com o serializer.validated_data 
4ª linha: então salva no [[banco de dados]] configurado com o serializer.save()

[[Configurando Serializers]]




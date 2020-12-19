# architecture-micro-service-cloud-eureka
Les noms dans les services (spring.application.name) doivent avoir le meme nom dans le fichier de propriete dans le cloud-conf qui est appelé par service-config
le dossier cloud-conf doit avoir un commit dans le git (soit on peut le lire localement soit on fait le push sur git ) et chnager le lien dans le ficiher propriéties de service 
"service-config"


lien utile pour tester :
http://localhost:8080/company-service/myConfig
http://localhost:8080/company-service/companies
http://localhost:8081/actuator/refresh
http://localhost:8081/actuator
http://localhost:8081/myConfig
http://localhost:8083/companies : body : {"name":"azert","price":456}

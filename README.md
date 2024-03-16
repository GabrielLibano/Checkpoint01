## Como rodar o docker
### Como rodar em cada ambiente
- Desenvolvimento
    - docker run -d -p 8080:8080 -e PROFILE=dev gabriellibano/fiap-checkpoint-1
- Stage
    - docker run -d -p 8080:8080 -e PROFILE=stg gabriellibano/fiap-checkpoint-1
- Produção
    - docker run -d -p 8080:8080 -e PROFILE=prd gabriellibano/fiap-checkpoint-1

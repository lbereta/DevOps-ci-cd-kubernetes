## Pipeline CI/CD com Jenkins

Este projeto utiliza Jenkins para automação do build, testes e deploy da aplicação Flask.

### Configuração do Jenkins

1. Instale o Jenkins usando Docker:
   ```bash
   docker run -d -p 8080:8080 -p 50000:50000 --name jenkins \
     -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts

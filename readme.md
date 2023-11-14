# Djavue

Um 📦template de projeto completo **full-stack**, **pronto para produção**, com boas práticas e focado na produtividade. Combina um frontend moderno (Vue 3 | Vuetify | Axios) e Backend Python (🦄 Django API)

```
 _______         __       ___   ____    ____  __    __   _______
|       \       |  |     /   \  \   \  /   / |  |  |  | |   ____|
|  .--.  |      |  |    /  ^  \  \   \/   /  |  |  |  | |  |__
|  |  |  |.--.  |  |   /  /_\  \  \      /   |  |  |  | |   __|
|  '--'  ||  `--'  |  /  _____  \  \    /    |  `--'  | |  |____
|_______/  \______/  /__/     \__\  \__/      \______/  |_______|

```

## Backend

- 🦄 [Django](https://www.djangoproject.com/) e PostgreSQL
- 🛠️ Qualidade de código usando Linter
- 🐳 Container para PROD (Dockerfile + docker compose) | Início com mínimo de esforço

## Frontend

- 🔩 API Cliente usando [Axios](https://axios-http.com/docs/intro)
- 🛠️ Qualidade de código usando Linter + Code Style (ESLint + Prettier)
- 💡 Herança de página usando Layout (View Component & Router)

# Como executar o projeto
Pré-requisitos: Docker

```bash
# clonar repositório
git clone git@github.com:Rdemora2/Djavue.git

# buildar os containers docker
docker compose build

# subir os containers
docker compose up

# criar superuser do django admin
abra um terminal na raiz do projeto
docker exec -ti django_backend bash
python manage.py createsuperuser
preencha os campos e crie o super usuário com permissões administrativas

# acessar as respectivas urls
Frontend: http://localhost:8080/
backend: http://localhost:8000/

```

# Portas utilizadas
- Backend: 8000
- Frontend: 8080
- PostgreSQL: 5432
- Redis: 6379

# Autor

Roberto de Moraes

https://www.linkedin.com/in/robertomoraeszarzur/
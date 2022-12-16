FROM python:3
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
WORKDIR /Users/syedsaif/mycode/makeitwork/django_docker_project
COPY requirements.txt /Users/syedsaif/mycode/makeitwork/django_docker_project/
RUN pip install -r requirements.txt
COPY . /Users/syedsaif/mycode/makeitwork/django_docker_project/
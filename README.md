
# Project Title

This is a sample kubernetes files for Django Application deployment


## Authors

- [@lionnelpat](https://www.github.com/lionnetpat)


## Deployment

To deploy this project, run this command

```bash
  kubectl apply -f db/
  kubectl apply -f app/
  kubectl apply -f nginx/ 

```

To verify status of running pods, run this command

```bash 
   kubectl get pods -n django-on-k8s -w 

```

To get the list of running pods, run this command

``` 
kubectl get pods -n django-on-k8s 

```

To get inside the container shell, run:

``` 
kubectl exec -it <POD_NAME> -n django-on-k8s -- sh

```

Then, run:

```
python manage.py createsuperuser

```




## Documentation

[Documentation](https://kubernetes.io/docs/home/)


## 🚀 About Me
I'm a Software Engineer and Tech Enthousiast ...


## Tech Stack

**Client:** Bootstrap 5, HTML5, CSS3

**Server:** Python, Django 5

**Database:**  PostgresSQL

**Reverse Proxy:** Nginx 


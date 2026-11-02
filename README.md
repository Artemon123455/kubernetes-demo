# Kubernetes Demo

Простой пример деплоя Nginx в Kubernetes.

## Что использовано
- Kubernetes
- Deployment
- Service (NodePort)
- Nginx

## Файлы

- `deployment.yaml` — создаёт 2 реплики Nginx
- `service.yaml` — открывает доступ к приложению

## Как запустить (если есть minikube или Docker Desktop Kubernetes)

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl get pods
kubectl get svc

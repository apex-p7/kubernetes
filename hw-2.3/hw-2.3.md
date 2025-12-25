# Домашнее задание к занятию «Настройка приложений и управление доступом в Kubernetes»

## **Задание 1: Работа с ConfigMaps**

### Скриншот вывода `curl` или браузера
<img width="758" height="205" alt="task1 1" src="https://github.com/user-attachments/assets/89aad5a9-2498-4152-a3e4-1d888526a8ef" />

Манифесты
- https://github.com/apex-p7/kubernetes/blob/main/hw-2.3/deployment.yaml
- https://github.com/apex-p7/kubernetes/blob/main/hw-2.3/configmap-web.yaml

## **Задание 2: Настройка HTTPS с Secrets**

### Скриншот вывода `curl -k`
<img width="599" height="209" alt="task2 1" src="https://github.com/user-attachments/assets/5e4ec4a0-68c3-4f02-9ebd-f1d56fd442bb" />

Манифесты
- https://github.com/apex-p7/kubernetes/blob/main/hw-2.3/secret-tls.yaml
- https://github.com/apex-p7/kubernetes/blob/main/hw-2.3/ingress-tls.yaml

## **Задание 3: Настройка RBAC**

### Скриншот вывода команд генерации сертификатов
<img width="901" height="219" alt="task3 1" src="https://github.com/user-attachments/assets/596a3809-ca0b-4750-a418-c6858fd20638" />

### Скриншот проверки прав
<img width="1027" height="448" alt="task3 2" src="https://github.com/user-attachments/assets/5b096ee3-6317-498a-a7df-0d4f352a4715" />

Манифесты
- https://github.com/apex-p7/kubernetes/blob/main/hw-2.3/role-pod-reader.yaml
- https://github.com/apex-p7/kubernetes/blob/main/hw-2.3/rolebinding-developer.yaml

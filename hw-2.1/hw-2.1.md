# Домашнее задание к занятию «Хранение в K8s»

## Задание 1. Volume: обмен данными между контейнерами в поде

### Скриншоты
<img width="931" height="227" alt="task1 1" src="https://github.com/user-attachments/assets/da57452d-611c-454d-8efe-ee4775918541" />

### Ссылки
- Вывод команды чтения файла: https://github.com/apex-p7/kubernetes/blob/main/hw-2.1/task1.2.txt
- Манифест: https://github.com/apex-p7/kubernetes/blob/main/hw-2.1/containers-data-exchange.yaml

## Задание 2. PV, PVC

### Скриншоты
2. <img width="1030" height="150" alt="task2 2" src="https://github.com/user-attachments/assets/e12fee01-3dd3-4743-b3cc-4dc19d73d734" />
3. <img width="979" height="262" alt="task2 3" src="https://github.com/user-attachments/assets/44c2fe14-6193-4677-89e9-b5dbc877e317" />
4. <img width="444" height="328" alt="task2 4" src="https://github.com/user-attachments/assets/b24753c3-8c06-4b49-a070-56a1f3fa9473" />
5. <img width="373" height="477" alt="task2 5" src="https://github.com/user-attachments/assets/73fd95b9-cab7-4ea1-b8ab-172e8d7b3471" />

### Комментраии к заданиям:
- 4: После удаления PVC, PV остаётся со статусом Released. Status: Released — значит, PVC был удалён, PV больше не связан с PVC.
- 5: Так как Reclaim Policy = Retain, Kubernetes не трогает данные. Если бы Reclaim Policy была Delete, Kubernetes удалил бы все данные в этой директории автоматически при удалении PV.

### Манифест:
- https://github.com/apex-p7/kubernetes/blob/main/hw-2.1/pv-pvc.yaml

## Задание 3. StorageClass

### Скриншоты
<img width="798" height="140" alt="task3 2" src="https://github.com/user-attachments/assets/f2ad3ec7-312f-4340-9aba-3273e3ba9b5f" />
<img width="986" height="203" alt="task3 3" src="https://github.com/user-attachments/assets/d60e408f-b03e-43f8-a4a3-f7b10abaa785" />

### Манифест:
- https://github.com/apex-p7/kubernetes/blob/main/hw-2.1/sc.yaml

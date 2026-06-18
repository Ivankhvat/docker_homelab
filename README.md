# docker_homelab

Практический стенд для изучения Docker, Linux и контейнеризации.


## Project Architecture

Ubuntu Server
│
├── Docker Engine
├── Portainer
├── Nginx
├── MariaDB
├── WordPress
├── phpMyAdmin
├── Adminer
└── Nginx Proxy Manager

## Technologies
- Ubuntu Server
- Docker
- Docker Compose
- Portainer
- Nginx
- MariaDB
- WordPress
- phpMyAdmin
- Adminer
- Nginx Proxy Manager

## Выполненные задачи
- Установка Ubuntu Server
- Настройка Docker Engine
- Развертывание Portainer
- Создание Docker Compose Stack
- Настройка Nginx
- Работа с Docker Volumes
- Развертывание MariaDB
- Развертывание Adminer
- Развертывание WordPress
- Настройка phpMyAdmin
- Backup и Restore базы данных

## Reverse Proxy Lab

### Реализовано
- Развернут Nginx Proxy Manager
- Настроены Proxy Hosts
- Настроена маршрутизация по доменным именам
- Настроены локальные DNS-записи через hosts
- Выполнена диагностика Docker Network
- Устранена ошибка 502 Bad Gateway

### Домены
- site1.local → site1 container
- site2.local → site2 container

## Skills Demonstrated
- Linux Administration
- Docker Containerization
- Docker Compose
- Docker Networking
- Docker Volumes
- Reverse Proxy Configuration
- Web Hosting
- MariaDB Administration
- Backup and Restore
- Troubleshooting
- GitHub Documentation

### Linux Storage Management
- LVM (Logical Volume Manager)
- Volume Group expansion
- Logical Volume extension
- Online filesystem resize
- Disk capacity management

Commands used:
lvextend
resize2fs
df
lsblk
vgdisplay


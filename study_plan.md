<html-markdown>
# DevOps Learning Path: 0 to Junior (90 дней)
**Ежедневная нагрузка:** ≤3 часа  
**Формат:** Теория (1ч) + Практика (1.5ч) + Обзор (0.5ч)

---

## Неделя 1-2: Продвинутый Linux & Bash (Дни 1-14)
| День | Тема | Задачи |
|------|------|--------|
| 1 | Файловая система | Inodes, hard/soft links, создание цепочки симлинков |
| 2 | Права доступа | ACL, настройка прав для группы developers |
| 3 | Управление процессами | cgroups, systemd-сервисы |
| 4 | Сети | iptables, SSH-туннели |
| 5 | Bash-скриптинг | Скрипт для бэкапа с проверкой места |
| 6 | Системное администрирование | Настройка сервера: пользователи + SSH + firewall |
| 7 | Повторение | Конфигурация сервера с нуля |
| 8 | Git Hooks | Pre-commit для проверки секретов |
| 9 | Управление историей | rebase -i, cherry-pick |
| 10 | Git LFS | Работа с большими файлами |
| 11 | Git bisect | Поиск коммита с багом |
| 12 | CI/CD основы | GitHub Actions для pytest |
| 13 | Продвинутый Git | Решение сложных конфликтов |
| 14 | Повторение | Оптимизация workflow |

---

## Неделя 3-4: Python для DevOps (Дни 15-28)
| День | Тема | Задачи |
|------|------|--------|
| 15 | Основы Python | Чтение файлов, обработка данных |
| 16 | API запросы | Работа с GitHub API |
| 17 | boto3 (AWS) | Создание S3-бакетов |
| 18 | Парсинг логов | Регулярные выражения для ошибок Nginx |
| 19 | Мониторинг | Скрипт для алертов при 90% CPU |
| 20 | CLI-утилиты | Управление EC2 через argparse/click |
| 21 | Автоматизация | Telegram-бот для алертов |
| 22 | Тестирование | pytest для скриптов |
| 23 | Продвинутые API | gRPC, RESTful сервисы |
| 24 | Асинхронность | asyncio для массовых проверок URL |
| 25 | Парсинг данных | Анализ CSV/JSON логов |
| 26 | Интеграция | Python + Bash совместное использование |
| 27 | Безопасность | Шифрование данных в скриптах |
| 28 | Проект | Система мониторинга на Python |

---

## Неделя 5-7: AWS (Дни 29-49)
| День | Тема | Задачи |
|------|------|--------|
| 29 | AWS Basics | IAM пользователи/роли |
| 30 | EC2 | Launch Templates, подключение по SSH |
| 31 | VPC | Публичные/приватные подсети, NAT Gateway |
| 32 | S3 | Versioning, Lifecycle Policies |
| 33 | Security | IAM Policies с условиями |
| 34 | Lambda | Обработка S3-событий |
| 35 | RDS | Развертывание PostgreSQL |
| 36 | Auto Scaling | Настройка ASG, тестирование под нагрузкой |
| 37 | ELB | Application Load Balancer |
| 38 | CloudWatch | Метрики, алерты |
| 39 | Route 53 | Настройка DNS |
| 40 | ElastiCache | Redis для кэширования |
| 41 | KMS | Шифрование данных |
| 42 | CloudFormation | Infrastructure as Code |
| 43 | Cost Optimization | Анализ расходов, бюджеты |
| 44 | Well-Architected | Review архитектуры |
| 45 | Backup | Стратегии бэкапирования |
| 46 | Multi-AZ | Отказоустойчивая архитектура |
| 47 | ECS | Docker-контейнеры в AWS |
| 48 | SQS/SNS | Очереди и уведомления |
| 49 | Повторение | Развертывание fullstack приложения |

---

## Неделя 8-9: Docker & Kubernetes (Дни 50-63)
| День | Тема | Задачи |
|------|------|--------|
| 50 | Docker Security | Multi-stage builds, Trivy |
| 51 | Docker Compose | Healthchecks, Flask+PostgreSQL |
| 52 | Docker Networks | Custom networks, DNS aliases |
| 53 | Kubernetes Basics | Minikube, Pods/Deployments |
| 54 | Services | ClusterIP, NodePort, LoadBalancer |
| 55 | Helm | Установка Nginx Ingress |
| 56 | Volumes | PersistentVolume, hostPath |
| 57 | ConfigMaps | Управление конфигурацией |
| 58 | Network Policies | Calico, ограничение трафика |
| 59 | StatefulSets | PostgreSQL с PersistentVolume |
| 60 | RBAC | Роли и привязки |
| 61 | HPA | Автомасштабирование |
| 62 | Operators | Создание Custom Resources |
| 63 | Повторение | Развертывание WordPress в K8s |

---

## Неделя 10-11: CI/CD & Мониторинг (Дни 64-77)
| День | Тема | Задачи |
|------|------|--------|
| 64 | GitLab CI | .gitlab-ci.yml, этапы build/test |
| 65 | Jenkins | Declarative Pipeline, Docker build |
| 66 | ArgoCD | GitOps, синхронизация приложений |
| 67 | Prometheus | Node Exporter, метрики |
| 68 | Grafana | Дашборды, алерты |
| 69 | Loki | Сбор и анализ логов |
| 70 | Jaeger | Distributed tracing |
| 71 | SLO/SLI | Мониторинг качества сервиса |
| 72 | Thanos | Long-term storage для Prometheus |
| 73 | OpenTelemetry | Инструментирование приложений |
| 74 | Canary Deploy | Flagger для постепенных релизов |
| 75 | Blue/Green | Стратегии развертывания |
| 76 | Security Scanning | Интеграция SonarQube/Trivy |
| 77 | Повторение | Полный CI/CD пайплайн |

---

## Неделя 12-13: Terraform (Дни 78-84)
| День | Тема | Задачи |
|------|------|--------|
| 78 | Terraform Basics | EC2 + Security Groups |
| 79 | Модули | Создание модуля VPC |
| 80 | State Management | S3 + DynamoDB для блокировок |
| 81 | Workspaces | Управление средами (dev/stage/prod) |
| 82 | Динамические блоки | Сложные Security Groups |
| 83 | Sentinel/OPA | Политики для инфраструктуры |
| 84 | Terratest | Тестирование инфраструктуры |

---

## Неделя 14-15: DevSecOps & Закрепление (Дни 85-90)
| День | Тема | Задачи |
|------|------|--------|
| 85 | Vault | Динамические секреты для БД |
| 86 | SAST/DAST | Bandit, OWASP ZAP |
| 87 | Container Security | Trivy, запрет root в контейнерах |
| 88 | K8s Security | Pod Security Policies |
| 89 | Резюме и проекты | Оформление GitHub портфолио |
| 90 | Итоговый проект | Полный стек: Terraform + K8s + CI/CD |

---

## Ключевые принципы
1. **Тайм-менеджмент (3 часа/день):**
   - 60 мин: Теория/документация
   - 90 мин: Практические задания
   - 30 мин: Анализ ошибок/конспект

2. **Инструменты для экономии времени:**
   - [Killercoda](https://killercoda.com/) - готовые Kubernetes-лабы
   - [GitPod](https://gitpod.io/) - облачные среды разработки
   - [AWS Free Tier](https://aws.amazon.com/free/) - бесплатные ресурсы AWS

3. **Что делать при отставании:**
   - Сокращать лабораторные, но сохранять концепты
   - Переносить сложные темы на выходные
   - Фокусироваться на ключевых технологиях (Linux, Docker, K8s, AWS)

---

## После завершения 90 дней
1. **Сертификации:**
   - AWS Certified DevOps Engineer Professional
   - Certified Kubernetes Administrator (CKA)
2. **Портфолио:**
   - 3 проекта на GitHub с IaC и CI/CD
   - Технический блог с разбором кейсов
3. **Поиск работы:**
   - Junior DevOps Engineer
   - Cloud Support Engineer
   - Site Reliability Intern

> **Важно:** Все лабораторные работы сохраняйте в [GitHub-репозитории](https://github.com/) — это ваше техническое портфолио!
</html-markdown>

# Kubernetes Deployment для My Web App

Этот репозиторий содержит YAML манифесты для развертывания веб-приложения в Kubernetes.

## Описание

*   **Deployment:** Управляет репликами приложения, обеспечивает отказоустойчивость.
*   **HorizontalPodAutoscaler (HPA):** Автоматически масштабирует количество реплик в зависимости от нагрузки CPU.
*   **PodDisruptionBudget (PDB):** Гарантирует минимальное количество работающих подов во время обновлений.
*   **ConfigMap:** Хранит конфигурационные данные приложения.
*   **Secret:** Хранит секретные данные приложения.
*   **ServiceMonitor:** Интеграция с Prometheus для сбора метрик.
*   **NetworkPolicy:** Ограничивает сетевой доступ к приложению.


# Microservice Architecture with Dapr and Spring Boot:

Um die Anwendung zu starten, muss für jeden Service über Gradle eine JAR-File erstellt werden. Dann ein Docker Image für jeden Servcie erstellen:

```docker build -t {service-name}:master .```

Anschließend in das Hauptverzeichniss navigieren und den folgenden Befehl ausführen:

```docker compose up -d```

Hint: Database-Sequences für die Entities fehlen noch und müssen ergänzt werden, wenn Entities hinzugefügt werden sollen.

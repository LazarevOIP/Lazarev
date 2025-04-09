# Инструкции по работе с Git и GitHub через SSH

## Как создать SSH-ключ

Открой терминал и выполни команду:

```bash
+Создание ключа:
ssh-keygen -t ed25519 -C "your_email@example.com"
+Копирование публичного ключа:
cat ~/.ssh/id_ed25519.pub
+Копирование репозитория:
git clone git@github.com:USERNAME/REPOSITORY.git
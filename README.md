# SQL-C---
# Разные полезные команды для SQL и C#
### ___Команда для смены пользователя___
> ALTER AUTHORIZATION ON DATABASE::[Имя БД] TO [DOMAIN\user]
######
> Чтобы узнать пользователя введите команду "sp_helplogins"
### ___Команда для создания бекапа___
> BACKUP DATABASE DBName
   TO DISK = 'C:\temp\DBName-backup.bak'
   WITH INIT ;

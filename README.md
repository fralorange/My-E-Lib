# My-E-Lib

Проект для практики SolarLab 2024 года.

## Клонирование репозитория

Чтобы начать работу над проектом, необходимо склонировать репозиторий git clone по следующей ссылке:

```cmd
git clone https://github.com/fralorange/My-E-Lib/tree/master-debug-deployment
```

## Установка зависимостей

После клонирования репозитория необходимо перейти в директорию Clients\MyELib.Clients.Web:

```cmd
cd Clients\MyELib.Clients.Web
```

Затем установите необходимые зависимости, выполнив следующую команду:

```cmd
npm ci
```

## Запуск клиентской части приложения

После установки зависимостей необходимо запустить клиентскую часть приложения, выполнив следующую команду:

```cmd
ng serve --open
```

Эта команда запустит приложение в режиме разработки и автоматически откроет его в вашем браузере по адресу <http://localhost:4200>.

## Запуск серверной части приложения

После запуска клиентской части приложения необходимо запустить серверную часть. Для этого откройте проект MyELib.Hosts.Api в Visual Studio и нажмите кнопку "Запустить" или нажмите клавиши F5.

Приложение будет доступно по адресу <https://localhost:5001>.

Готово! Теперь вы можете начать работать над проектом My-E-Lib.

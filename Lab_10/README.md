# Настройка DHCP, NAT и NTP

![alt text](image.png)

# 1. Настройка NAT (PAT) в Москве на R14 и R15

## 1.1 Настройка NAT (PAT) на R14

- Создаем access-list с разрешенными сетями для трансляций NAT

![alt text](image-1.png)

- Настраиваем параметры для трансляции NAT (PAT)

![alt text](image-2.png)

- Добавляем входные и выходные интерфейсы NAT

![alt text](image-3.png) ![alt text](image-5.png)

- Проверяем работу NAT (PAT) на R14

![alt text](image-6.png)

![alt text](image-7.png)

## 1.2 Настройка NAT на R15

- Настроим статический NAT на R15

![alt text](image-8.png)

- Добавляем входные и выходные интерфейсы NAT

![alt text](image-9.png) ![alt text](image-10.png)

- Проверяем работу NAT на R15

![alt text](image-11.png)

![alt text](image-12.png)

_____________________________________________

# 2. Настройка NAT (PAT) на R18

- Создаем access-list с разрешенными сетями для трансляций NAT

![alt text](image-13.png)

- Создаем пул адресов для трансляции NAT

![alt text](image-14.png)

- Настраиваем динамический NAT

![alt text](image-15.png)

- Добавляем входные и выходные интерфейсы NAT

![alt text](image-16.png) ![alt text](image-17.png)

Проверяем работу NAT на R18

![alt text](image-18.png)

![alt text](image-19.png)

_______________________________________________

# 3. Настройка статического NAT на R20

- Настроим статический NAT на R20

![alt text](image-20.png)

Добавляем входные и выходные интерфейсы NAT

![alt text](image-21.png) ![alt text](image-22.png)

Проверяем работу NAT на R20

![alt text](image-23.png)

![alt text](image-24.png)

______________________________________

# 4. Настройка NAT на R19, чтобы он был доступен с любого узла сети

- Разрешим доступ по telnet на R19 с других устройств

![alt text](image-25.png)

- Настроим NAT с пробросом портов для доступа к R19 с других устройств

![alt text](image-26.png)

- Добавляем входные и выходные интерфейсы NAT

![alt text](image-27.png) ![alt text](image-28.png)

- Проверим доступность R19 по telnet из офиса в Санкт-Петербурге 

![alt text](image-29.png)

_________________________________________


# 5*. Настройка статического NAT(PAT) в офисе Чокурдах

- Настроим статический NAT на R28

![alt text](image-30.png)

- Добавляем входные и выходные интерфейсы NAT

![alt text](image-31.png) ![alt text](image-32.png)

- Проверяем работу NAT на R28

![alt text](image-33.png)

![alt text](image-34.png)

-----------------------------------

# 5. Настройка IPv4 DHCP сервер в офисе Москва на маршрутизаторах R12 и R13

## 5.1 Настройка IPv4 DHCP сервера на R12

- Настраиваем параметры сервера

![alt text](image-35.png)

- Исключаем выбранный диапазон адресов из раздачи

![alt text](image-36.png)

- Проверяем, что VPC1 получил настройки через DHCP

![alt text](image-37.png)

## 5.2 Настройка IPv4 DHCP сервера на R13

- Настраиваем параметры сервера

![alt text](image-38.png)

- Исключаем выбранный диапазон адресов из раздачи

![alt text](image-39.png)

- Проверяем, что VPC7 получил настройки через DHCP

![alt text](image-40.png)

__________________________

# 6. Настройка NTP сервера на R12 и R13, и синхронизации между узлами Московского офиса

## 6.1 Настройка NTP серверов

- Настройка NTP сервера на R12

![alt text](image-42.png)

- Настройка NTP сервера на R13

![alt text](image-41.png)

## 6.2 Настройка NTP клиентов на примере R14 и R15

- Настройка NTP клиента на R14

![alt text](image-43.png)

- Настройка NTP клиента на R14

![alt text](image-44.png)

## 6.3 Проверка синхронизации на примере R14 и R15

- Проверка синхронизации на R14

![alt text](image-45.png)

![alt text](image-46.png)

- Проверка синхронизации на R15

![alt text](image-47.png)

![alt text](image-48.png)






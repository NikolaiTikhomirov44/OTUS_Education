# Настройка eBGP/iBGP IPv6 unicast для всех сегментов сети

![alt text](image.png)

____________________________________________

# 1, 2, 3, 6) Совместим настройку eBGP IPv6 unicast между офисом в Москве и провайдерами, и iBGP IPv6 unicast в офисе Москва между маршрутизаторами R14 и R15

## 1.1  Настройки на R14 в Москве 

- Настройка ipv6 интерфейсов

![alt text](image-3.png)

- Включение ipv6 unicast-routing

![alt text](image-4.png)

- Добавление соседей в BGP и анонс Loopback

![alt text](image-21.png)

![alt text](image-6.png)

## 1.2 Настройки на R15 в Москве

- Настройка ipv6 интерфейсов

![alt text](image-7.png)

- Включение ipv6 unicast-routing

![alt text](image-8.png)

- Добавление соседей в BGP и анонс Loopback

![alt text](image-22.png)

![alt text](image-10.png)

## 1.3 Настройка eBGP IPv6 unicast на R22 в Киторне

- Настройка ipv6 интерфейсов  

![alt text](image-13.png)

- Включение ipv6 unicast-routing

![alt text](image-14.png)

- Добавление соседей в BGP и анонс Loopback

![alt text](image-16.png)

![alt text](image-17.png)

## 1.4 Настройка eBGP IPv6 unicast на R21 в Ламасе

- Настройка ipv6 интерфейсов  

![alt text](image-18.png)

- Включение ipv6 unicast-routing

![alt text](image-14.png)

- Добавление соседей в BGP и анонс Loopback

![alt text](image-19.png)

![alt text](image-20.png)

# 4 и 7) Совместим настройку eBGP IPv6 unicast между офисом С.-Петербург и провайдером Триада, и iBGP IPv6 unicast в провайдере Триада с использованием RR

## 4.1 Настройка eBGP IPv6 unicast на R18 в офисе Санкт-петербург

- Настройка ipv6 интерфейсов

![alt text](image-24.png)

Включение ipv6 unicast-routing

![alt text](image-14.png)

- Добавление соседей в BGP и анонс Loopback

![alt text](image-25.png)

![alt text](image-26.png)

## 4.2 Настройка eBGP IPv6 unicast и iBGP IPv6 unicast с использованием RR на R24 в офисе Триада

- Настройка ipv6 интерфейсов

![alt text](image-27.png)

Включение ipv6 unicast-routing

![alt text](image-14.png)

- Добавление соседей в BGP, настройка RR и анонс Loopback

![alt text](image-28.png)

![alt text](image-29.png)

Так же настроим route-map для RR клиентов

![alt text](image-30.png)

И проверим, что R23 и R26 получают актуальные маршруты

![alt text](image-31.png)

![alt text](image-32.png)

# 5 и 8) Проверка связности между сетями на примере офисов в Москве и Санкт-петербурге

## 5.1 Проверка таблицы маршрутизации на пограничном роутере R15 в Москве

![alt text](image-33.png)

## 5.2 Проверка таблицы маршрутизации на пограничном роутере R18 в Санкт-Петербурге

![alt text](image-34.png)

## 5.3 Проверка связности между сетями в Москве и Санкт-Петербурге

![alt text](image-35.png)

## 5.4 Проверка связности между сетями из офиса в Санкт-Петербурге

![alt text](image-36.png)



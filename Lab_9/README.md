# Настройка eBGP/iBGP IPv6 unicast для всех сегментов сети

![alt text](image.png)

____________________________________________

# 1 и 6) Совместим настройку eBGP IPv6 unicast между офисом Москва и двумя провайдерами - Киторн и Ламас с настройкой iBGP IPv6 unicast в офисе Москва между маршрутизаторами R14 и R15

## 1.1  Настройки на R14 в Москве 

- Настройка ipv6 интерфейсов

![alt text](image-3.png)

- Включение ipv6 unicast-routing

![alt text](image-4.png)

- Добавление соседей в в BGP и анонс Loopback

![alt text](image-5.png)

![alt text](image-6.png)

## 1.2 Настройки на R15 в Москве

- Настройка ipv6 интерфейсов

![alt text](image-7.png)

- Включение ipv6 unicast-routing

![alt text](image-8.png)

- Добавление соседей в в BGP и анонс Loopback

![alt text](image-9.png)

![alt text](image-10.png)

## 1.3 Настройки на R22 в Киторне
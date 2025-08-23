---
# This section at the top is called "Front Matter". Jekyll needs it.
layout: page
title: MKA
---

## Поребрики:

### 1. Параметрические поребрики
Генерация из набора линий, возможность наложить bevel любого размера и детализации

<video muted autoplay controls loop style="display: block; margin: 0 auto; max-width: 70%; height: auto;">
    <source src="assets/mka/Curb_1.webm" type="video/webm">
</video>

### 2. Проецирование на поверхность
Элементарная штука, но удобно и выглядит залипательно
<video muted autoplay controls loop style="display: block; margin: 0 auto; max-width: 70%; height: auto;">
    <source src="assets/mka/0_HD.mp4" type="video/mp4">
</video>

# Ландшафт
### 1. Генерация границы ландшафта с UDIM UV


<video muted autoplay controls loop style="display: block; margin: 0 auto; max-width: 70%; height: auto;">
    <source src="assets/mka/1_FHD.webm" type="video/webm">
</video>


<video muted autoplay controls loop style="display: block; margin: 0 auto; max-width: 70%; height: auto;">
    <source src="assets/mka/1_1_hd.mp4" type="video/mp4">
</video>

### 2. Упрощение геометрии границы в зависимости от материала

<video muted autoplay controls loop style="display: block; margin: 0 auto; max-width: 70%; height: auto;">
    <source src="assets/mka/2_FHD.webm" type="video/webm">
</video>

### 3. Нарезка ландшафта на поверхности 
и автокорректировка UV под UDIM
(Нарезка на основе knife-project, а не boolean exact. Вышло примерно в 40раз быстрее + меньше ошибок в нарезке)
<video muted autoplay controls loop style="display: block; margin: 0 auto; max-width: 70%; height: auto;">
    <source src="assets/mka/3_FHD.webm" type="video/webm">
</video>

# Генерация геометрии столкновений (коллизия)

# Экспорт-пресеты
1. Разные варианты экспорта FBX
2. Автогенерация JSON
3. Создание финального архива
![image1](./assets/mka/ExportPlugin.png)

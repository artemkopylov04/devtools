# Network

## Дублирующие ресурсы

Возможно некоторые из примеров ниже не 100% точны по получаемому контенту. Но даже если сравнивать по размеру файлов, очень похоже на дубль

![Вот](/network/dublicates1.JPG)

![Вот](/network/dublicates2.JPG)

![Вот](/network/dublicates3.JPG)

![Вот](/network/dublicates4.JPG)

![Вот](/network/dublicates5.JPG)

![Вот](/network/dublicates6.JPG)

![Вот](/network/dublicates7.JPG)

![Вот](/network/dublicates8.JPG)

![Вот](/network/dublicates9.JPG)

![Вот](/network/dublicates10.JPG)

## Не оптимизированные ресурсы

![Большие по размеру картинки](/network/big_size_resources.JPG)

Картинка в 2.6 мб? Две другие тоже не опитимизированы, еще и грузятся очень долго

## Медленная загрузка

![Медленная загрузка](/network/slow_download_sorted.JPG)

По сути все что на скриншоте не должно прогружаться с такой скоростью (файлы в килобайт грузятся за секунду и выше)

## Ресурсы блокирующие загрузку

![Ресурсы блокирующие загрузку](/network/block_resources.JPG)

Очень много ресурсов, которые мешают событию DOMContentLoaded. Ненужные картинки, запросы в рекламные сервисы, кучи ненужного css, js, шрифтов, все что на скриншоте - ресурсы получаемые до DCL

# Performance

## Время событий

### First Paint 
![First Paint](/performance/first_paint.JPG)

### First Meanningful Paint 
![First Meanningful Paint ](/performance/FMP.JPG)

### DOM Content Loaded
![DOM Content Loaded](/performance/DCL.JPG)

### Load Event
![Load Event](/performance/ONLOAD.JPG)

## Общее время этапов обработки документа

![Summary](/performance/Summary.JPG)

# Coverage

## Неиспользуемый CSS

### 394 кб (89% от общего количества)
![Unused_CSS](/coverage/unused_css.JPG)

## Неиспользуемый JS

### 2500 кб (63% от общего количества)
![Unused_JS](/coverage/unused_js.JPG)

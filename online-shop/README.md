# Online Shop

<img width="898" alt="Screen Shot 2022-04-24 at 5 46 19 PM" src="https://user-images.githubusercontent.com/60435025/114864206-87361300-9e12-11eb-92ca-5118cb76d7e1.png">
<img width="898" alt="Screen Shot 2022-05-24 at 5 46 57 PM" src="https://user-images.githubusercontent.com/60435025/114864254-961cc580-9e12-11eb-8f18-518adbd52172.png">
<img width="1440" alt="Screen Shot 2022-05-24 at 5 47 23 PM" src="https://user-images.githubusercontent.com/60435025/114864476-daa86100-9e12-11eb-841f-fe9d1973bb08.png">
<img width="1440" alt="Screen Shot 2022-05-24 at 5 48 11 PM" src="https://user-images.githubusercontent.com/60435025/114864496-e09e4200-9e12-11eb-823e-408bdb792b0d.png">
<img width="1440" alt="Screen Shot 2022-05-24 at 5 48 11 PM" src="https://user-images.githubusercontent.com/60435025/114864528-e98f1380-9e12-11eb-91c8-43cd09be23f0.png">
<img width="1440" alt="Screen Shot 2022-05-24 at 5 48 23 PM" src="https://user-images.githubusercontent.com/60435025/114864532-eac04080-9e12-11eb-8e87-576adcd2fbd1.png">
<img width="1440" alt="Screen Shot 2022-05-24 at 5 48 28 PM" src="https://user-images.githubusercontent.com/60435025/114864534-eb58d700-9e12-11eb-828f-8c8e6017334b.png">
<img width="1440" alt="Screen Shot 2022-05-24 at 5 48 37 PM" src="https://user-images.githubusercontent.com/60435025/114864536-ebf16d80-9e12-11eb-9582-19907723ba53.png">

## API Description

* To get Swagger you should "/swagger-ui.html"
* To login you should access "/login"
* To view all blog you should access "/"
* To view all man products you should access "/men"
* To view all woman products you should access "/women"
* To add products you should access "/add"
* To edit product you should access "/product/{id}/edit"
* To delete product you should access "/product/{id}/delete"
* To see detail of product you should access "/product/{id}"

## What is used
* MVC
* MySQL
* Bootstrap
* Spring
* Rest API
* Swagger


## Notes

* For Final examination
* User frieindly interface:)

## Script for MySQL

CREATE TABLE `product` (
`id` int NOT NULL,
`name` varchar(100) DEFAULT NULL,
`price` int DEFAULT NULL,
`info` varchar(250) DEFAULT NULL,
`image_url` varchar(255) DEFAULT NULL,
`types` varchar(25) DEFAULT NULL,
`sex` varchar(25) DEFAULT NULL,
PRIMARY KEY (`id`)
)

use shop;

insert into product values ('1', 'Adidas  T-shirt', '59 $', 'A lightweight T-shirt from Adidas will help create a memorable image for a walk around the city.', 'https://avatars.mds.yandex.net/get-mpic/5289692/img_id5907604583261761122.jpeg/orig', 'Clothes', 'Men');
insert into product values ('2', 'Adidas Trousers\n', '65 $', 'Classic fleece trousers for everyday wear. An active lifestyle is not only a sport.', 'https://avatars.mds.yandex.net/get-mpic/4866035/img_id6796570164167428593.jpeg/orig', 'Clothes', 'Men');
insert into product values ('3', 'Adidas Trousers\n', '78 $', 'Classic fleece trousers for everyday wear. An active lifestyle is not only a sport.', 'https://avatars.mds.yandex.net/get-mpic/5209894/img_id1923245779721321640.jpeg/orig', 'Clothes', 'Women');
insert into product values ('4', 'Puma trousers', '63 $', 'Modern women\'s sports trousers in a pleasant gray color are suitable for both sports and outdoor activities', 'https://avatars.mds.yandex.net/get-mpic/5231781/img_id603284592220405304.jpeg/orig', 'Clothes', 'Women');

# Online Shop

### [Link to webapp]( https://cs400database.herokuapp.com/)

### [Youtube link](https://youtu.be/hS7tV30kLjU)

### [Documentation](https://app.swaggerhub.com/apis/Robendano/api-documentation/1.0)

<img width="898" alt="Screen Shot 2022-04-24 at 5 46 19 PM" src="https://user-images.githubusercontent.com/78977590/170252884-ec1c1deb-b422-4989-916b-36d4088fe9cb.png">
<img width="898" alt="Screen Shot 2022-05-24 at 5 46 57 PM" src="https://user-images.githubusercontent.com/78977590/170253165-9c11824f-4349-4c16-a7d1-b84c3581ed7f.png">
<img width="1440" alt="Screen Shot 2022-05-24 at 5 47 23 PM" src="https://user-images.githubusercontent.com/78977590/170253257-df899fef-ce3a-4af5-ab69-f8ced75e5acc.png">
<img width="1440" alt="Screen Shot 2022-05-24 at 5 48 11 PM" src="https://user-images.githubusercontent.com/78977590/170253365-543f818b-3d6b-4f04-8115-2706abc6bbc1.png">
<img width="1440" alt="Screen Shot 2022-05-24 at 5 48 11 PM" src="https://user-images.githubusercontent.com/78977590/170253557-405f5d4c-4e25-455e-8a4c-010c7b332316.png">
<img width="1440" alt="Screen Shot 2022-05-24 at 5 48 23 PM" src="https://user-images.githubusercontent.com/78977590/170253692-4296ec56-9f4f-4750-81a1-6acd40699ec6.png">
<img width="1440" alt="Screen Shot 2022-05-24 at 5 48 28 PM" src="https://user-images.githubusercontent.com/78977590/170253799-acaf414b-de3d-4708-b2a8-a1e46e605547.png">

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
* tutorial - https://www.youtube.com/watch?v=971sG9wInBs&t=2276s

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

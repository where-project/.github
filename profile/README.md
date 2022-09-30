# Where: Blockchain Destekli Rezervasyon Sistemi 👩‍💻
### [BACKEND](https://github.com/where-project/where)
### [FRONTEND](https://github.com/where-project/where-frontend)
### 1 - [INTRODUCTION](https://github.com/where-project#1-introduction)
### 2 - [DESIGN](https://github.com/where-project#2-design)
### 3 - [THE WORKS OF TEAM MEMBERS](https://github.com/where-project#3-the-works-of-team-members)

## 1. INTRODUCTION
This application allows you to discover new places in your area, and to make predictions about how good the service you will receive in the places you go, based on comments and ratings. In addition, it offers the opportunity to make a blockchain-supported reservation without the need for an third party before going to restaurants, hotels or businesses and places that work with the reservation system. It guides you as a guide that you have with you.

It is to create a platform that aims to increase the satisfaction of people who plan touristic trips or who want to explore different, new businesses and places to act in a more planned way. The project we developed for this purpose creates an environment where people can list the places, see the comments and ratings of these places, and make reservations for the places. Thus, it will be a web application that allows people to discover new places and spend quality time.

The project is written using the popular **Java (Spring Boot framework)**, **React** and **Solidity** language for smart contracts, which have been popular in recent years.

We will use the client-server model in our project. According to this model, we can say that a client is a machine that requests data or services. The server is the machine that returns services and data to the client. Servers listen for incoming network requests. In the client-server architecture we created, all requests and services are delivered over a network.

  _Hedeflenen bu uygulama, bulunduğunuz bölgede yeni yerler keşfedebilmenizi, gittiğiniz mekanlarda alacağınız hizmetin ne kadar iyi olabileceği konusunda yorum ve puanlamalara dayanarak tahminde bulunmanızı sağlamaktadır. Bunun yanında restoran, otel veya rezervasyon sistemi ile çalışan işletme ve mekanlara gitmeden önce aracı bir tarafa ihtiyaç duymadan blockchain destekli rezervasyon yapma imkânı sunmaktadır. Yanınızda bulundurduğunuz bir rehber olarak size yol göstermektedir.

_Turistik gezi planlayan veya farklı, yeni işletme ve yerleri keşfetmek isteyen kişilerin daha planlı bir şekilde hareket etmelerini ve kişilerin memnuniyetlerini artırmayı amaçlayan bir platform oluşturmaktır. Bu amaç doğrultusunda gerçekleştireceğimiz proje, insanların mekanları listeleyebildiği, bu mekanlara ait yorum ve puanları görebildiği, mekanlara rezervasyon gerçekleştirebildiği bir ortam oluşturmaktadır. Böylece insanların yeni mekanlar keşfetmesini ve kaliteli zaman geçirmesini sağlayan bir web uygulaması olacaktır.

_Proje, son yıllarda popüler olan **Java (Spring Boot framework)**, **React** ve akıllı sözleşmeler için **Solidity** dili kullanılarak yazılmıştır.

_Projemizde client(istemci)-server(sunucu) modeli kullanacağız. Bu modele göre istemcinin, veri veya hizmet talep eden bir makine olduğunu söyleyebiliriz. Sunucu ise istemciye hizmet ve verileri döndüren makinedir. Sunucular gelen ağ isteklerini dinlerler. Oluşturduğumuz client-server mimarisinde bütün istek ve hizmetler bir ağ üzerinden teslim edilir.

![image](https://user-images.githubusercontent.com/61885344/187069017-718e05b8-fb22-4fdc-b458-88dfc6934180.png)

Our application will allow listing all registered reservations. The person who wants to make a reservation will send crypto money. Smart contracts are the structures responsible for sending the payment to the owner of the place where the reservation will be made (business owner) and giving the reservation to the buyer.

_Uygulamamız kayıtlı olan bütün rezervasyonların listelenebilmesine izin verecektir. Rezervasyon yaptırmak isteyen kişi kripto para gönderimi gerçekleştirecektir. Akıllı sözleşmeler rezervasyonun yapılacağı mekanın sahibine (işletme sahibine) ödemeyi göndermekten ve rezervasyonu da satın alan kişiye vermekten sorumlu yapılardır.

![image](https://user-images.githubusercontent.com/61885344/187069285-0983f7b6-5c12-4e31-8429-37f5ba1aaf63.png)

## 2. DESIGN
- ### Login Screen
![image](https://user-images.githubusercontent.com/61885344/187069502-e154037d-2b97-42ba-9f5d-2958d9ab4133.png)

-  ### Register Screen
![image](https://user-images.githubusercontent.com/61885344/187069571-4975d7bd-8c86-415a-875e-96031bfec541.png)

- ### Main Screen
![image](https://user-images.githubusercontent.com/61885344/187069681-58591fe3-b4d8-4f7c-94d4-c461beade2d7.png)

- ### Venue Listing Screen
![image](https://user-images.githubusercontent.com/61885344/187073573-6e2181c5-c943-4e3a-9c13-fe74415222a7.png)

- ### Venue Detail Screens
![image](https://user-images.githubusercontent.com/61885344/187073755-24ec2d15-e151-49df-9e9a-4d04b0716006.png)
> - ### Overview Screen ![image](https://user-images.githubusercontent.com/61885344/187074887-7f89a673-5737-4416-8d8d-a8c428cf6c34.png)
> - ### Pricing Screen ![image](https://user-images.githubusercontent.com/61885344/187074931-b10c695f-8afb-45c5-b289-116c3cfd58fe.png)
> - ### Location Screen ![image](https://user-images.githubusercontent.com/61885344/187074968-d4dc1b94-39b3-4f44-9abe-5f2cb4e429a2.png)
> - ### Review Screen ![image](https://user-images.githubusercontent.com/61885344/187075207-98c1dae1-cb60-42d8-963f-b1c3cae4bae9.png) ![image](https://user-images.githubusercontent.com/61885344/187075242-48cd2f3d-490f-451f-97bc-6840aca8b396.png)
> - ### Reservation Screen ![image](https://user-images.githubusercontent.com/61885344/187075055-c22abd4b-77fd-40de-b039-8fce06ec2b39.png)![image](https://user-images.githubusercontent.com/61885344/187477763-3ffa3638-128b-4997-8664-cbfbe44261c1.png)

- ### Confirmation Mail 
![image](https://user-images.githubusercontent.com/61885344/187477491-3dc426da-9bbb-400b-9e59-9bf06bc0192c.png)
- ### Transaction Screen 
![image](https://user-images.githubusercontent.com/61885344/187477661-3b6e9206-4bc9-4eb1-b177-c363205ae638.png)
- ### Contact Screen 
![image](https://user-images.githubusercontent.com/61885344/187477994-cadc0753-a114-4623-8f8b-3374ab206565.png)
- ### Add Venue Screen
>  ### ![image](https://user-images.githubusercontent.com/61885344/187478346-64246b7c-8f43-4f67-8e8f-c204177107cf.png)
>  ### ![image](https://user-images.githubusercontent.com/61885344/187478466-a68ce614-9fe5-49d5-93e3-cef058ca3d50.png)
>  ### ![image](https://user-images.githubusercontent.com/61885344/187478499-64237f09-7b40-439d-b8ca-11d17ec2e9d3.png) 
>  ### ![image](https://user-images.githubusercontent.com/61885344/187478521-8715e0e1-974b-44ed-9ece-8ce29c79853a.png)
- ### Delete Venue Screen 
![image](https://user-images.githubusercontent.com/61885344/187478636-22cd68d9-7c98-432e-a3aa-0e614fc21112.png)


## 3. THE WORKS OF TEAM MEMBERS
>* [Onur Akkepenek](https://github.com/OnurAkkepenekk)
>* [Berkay Hüseyinoğlu](https://github.com/thehuseyinoglu)
>* [Yasemin Gerboğa](https://github.com/yasemingerboga)

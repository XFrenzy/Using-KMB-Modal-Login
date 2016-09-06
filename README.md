# Using-KMB-Modal-Login
Using KMBModalLogin popup in ASP.NET MVC Projects. 

You can use Visual Studio and download modal login automatically. For download, you can use nuget package manager. Enter KMBModalLogin to search box and just download it. 

> **PM > Install-Package [KMBModalLogin](https://www.nuget.org/packages/KMBModalLogin/)**

## Sample Layout

You can use quickly **_ModalLoginMenuItemPartial.cshtml** partial view that shows **SignIn** and **SignUp** links.
KmbLayout that in shared folder, has two partials.

![Layout has two partials](http://goo.gl/uqy1Es)

> **You can sure using JQuery(>=2.2.4) and Bootstrap(>=3.3.0)**  

![Adding Scripts to Head Block](http://goo.gl/YCZso0)

![KMBModalLogin Sample Layout Screen](http://goo.gl/35GOMW)

## Login Screen

For login your user(s) in website.

![KMBModalLogin Login Screen](https://goo.gl/rre4Px)

## SignUp/Register Screen

For register your new user(s) in website.

![KMBModalLogin SignUp-Register Screen](https://goo.gl/bEyp7O)

## Lost Password Screen

Remember Password for lost password of user(s) in website.

![KMBModalLogin Lost Password Screen](https://goo.gl/xaA5iN)

## Controllers

All buttons make AJAX callback in **modal-login.js**. You can change them. All required GET and POST actions in **ModalLoginController**. You can change into some code lines. They have required basic sample code but you can use that. Only you can change database request lines. I added **// TODO : ...** comment line top of them. So you can use TaskList in Visual Studio and you can see all of them. 

![you can use Task List](https://goo.gl/XfyzEx)

[![Everything Is AWESOME](http://img.youtube.com/vi/StTqXEQ2l-Y/0.jpg)](https://www.youtube.com/watch?v=StTqXEQ2l-Y "Everything Is AWESOME")

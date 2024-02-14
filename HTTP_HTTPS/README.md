# 🌏 HTTP and HTTPS
HTTP= Hypertext transfer protocol

* *Hypertext* = it's text which send to get another information to different pages

* *Hyperlink* = if you click on something, you arrive to other place

HTTP sends Hypertext with Hyperlinks, it makes a specific path to another file in Internet (URL) with TCP session of port 80

## 👇 Example :

**PC**--------(send HTTP request)------->**Server**--------------->**Database**--------------->**return to PC**

* When you click on Youtube video on your PC you're send HTTP request to the **Server** and you're get HTML page at the end with video

* The second way to get the same HTML page is to use **URL** (Uniform Resourse Locator)

* If it works **Server** will give you 200 (OK status), 404 (Not Found) 5XX (**Server** doesn't work now) and more

## 🥪 HTTP and HTTPS Consist :
**Started string**: URL, method of request(GET,POST and more)
**Title**: Information about the language choose, login/password
**Body**: Text, Answer

## 🔒 HTTP and HTTPS Difference :
The database of sending to you with HTTP doesn't hashed on the way, so someone can use it, for example use your passwords, credit cards informations

So for that we need security hashed way to send the database, we use **HTTPS**

**HTTPS** = S means Security

To hash the data HTTPS protocol use SSL and TLS

* SSL (Secure Sockets Layer) = The site will send you request copy of certificate and if he's okay you can send data

* SSL it's like outdated TLS with V1.0. TLS it's updated version of SSL

* Nowadays we use TLS 1.2 and 1.3

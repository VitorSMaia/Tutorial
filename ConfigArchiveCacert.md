<h1 align="center">
    <a href="https://cdnjs.com"><img src="https://raw.githubusercontent.com/cdnjs/brand/master/logo/standard/dark-512.png" width="175px" alt="< cdnjs >"></a>
</h1>

<h3 align="center">DevTech created to make life easier for developers.</h3>

---

## Table of Contents

* [cURL error 77](#cURL error 77)

## cURL error 77

* Error setting certificate verify locations

<p>This error occurs for not finding the cacert file, to make api requests.
Let me help you solve this in a simple way.</p>

## [[Download]](https://curl.se/docs/caextract.html)

* After the download, go to the folder that contains the files of your version of php and put the downloaded file inside the folder:

`*\extras\ssl`

* Then access the php.ini file, and change the two options below, with the path of the file you downloaded: 

`curl.cainfo = {Coloque o Caminho do arquivo aqui}`

`openssl.cafile = {Coloque o Caminho do arquivo aqui}`

<p>Restart your machine and test.</p>

<p>If it doesn't work, contact me and maybe I can help.</p>

***
***
***
<p>
João Vitor </br>
Developer PHP </br></br>
    <a href = "https://wa.me/5511913564982">
     <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank">
    </a>
    <a href = "mailto:vito.smaia1@gmail.com">
     <img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank">
    </a>
</p>
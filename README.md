# ระบบบริหารสหกร
เป็นระบบจัดการระบบทั้งหมดของสหกรณ์ รวมถึงจัดการหุ้นส่วนของสหกณ์ พัฒนาโดย Laravel แล้วทำเป็น Windows application เก็บข้อมูลที่ local แต่มีการ Sync กับระบบ Cloud ตลอด เพื่อใช้งานแบบออนไลน์ และออฟไลน์ได้
> ใช้หลัการพัฒนาแบบ Agile เครื่องมือคือ Scrum

## Tools
- Laravel 5.5 LTS
- Vue 2
- Microsoft Visual Studio Code
- MSSQL
- Nginx

## Language
- PHP
- SQL oracle
- JavaScript
- HTML , CSS
- C# for Windows Application
 
## Microsoft Visual Studio Code Extension
- Laravel Artisan
- Laravel Blade Snippets
- mssql
- PHP IntelliSense
- Vetur
  ### optional
- Better align
- Auto close tag
- Auto rename tag
- REST Client

## Test
- Unit test -> Laravel
- System testing -> Dusk

## Directory tree
```
prject
│   README.md
│   file001.txt    
│
└───app
│   │   Models.php
│   │
│   └───Http
│       └───Controller
│           |   NameController.php
│   
└───resource
    └───assets
    |   └───js
    |   |   |   app.js
    |   |   |   bootrap.js
    |   |   |
    |   |   └───pages
    |   |       └───pagename
    |   |           |   index.js
    |   |           |
    |   |           └───component
    |   └───sass
    |       |   _variables.scss
    |       |   app.scss
    |
    └───lang
    |
    └───view
        |   main.blade.php
        |
        └───auth
        |   |   login.blade.php
        |   |
        |   └───password
        |       |   email.blade.php
        |       |   password.blade.php
        |
        └───email
        |   |   filename.blade.php
        |
        └───layouts
            |   footer.blade.php
            |   header.blade.php
            |   sidebar.blade.php
            |   theme.blade.php
```

## Coding styles

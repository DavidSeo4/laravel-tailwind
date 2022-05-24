Blog con Laravel + Tailwind CSS



- 1 Creamos un sitio rapido de Laravel por medio de Laragon

  ![image-20220524130951101](C:\Users\Usuario\AppData\Roaming\Typora\typora-user-images\image-20220524130951101.png)

- 2 Introducimos los siguientes comandos

  - ```composer require laravel/ui --devbash
    composer require laravel/ui --dev (instalar Laravel/ui)
    composer require laravel-frontend-presets/tailwindcss --dev (dependencia para usar los estilos de Tailwind CSS)
    php artisan ui tailwindcss --auth (generar los archivos de autenticación )
    npm install && npm run dev (instalar las dependencias que utiliza Tailwind CSS y compilar los css y js.)
    ```

- 3 Ahora lanzamos el comando php artisan serve para comprobar que hasta ahora todo funciona correctamente

![image-20220524133449267](C:\Users\Usuario\AppData\Roaming\Typora\typora-user-images\image-20220524133449267.png)



- 4 Conectamos correctamente el proyecto con la base de datos de PhpMyadmin

![image-20220524133652165](C:\Users\Usuario\AppData\Roaming\Typora\typora-user-images\image-20220524133652165.png)

- 5 Crear los modelos y migraciones para los posts y comentarios. Al añadir **-m** le estamos diciendo que también nos cree el archivo para las migraciones.

![image-20220524133813489](C:\Users\Usuario\AppData\Roaming\Typora\typora-user-images\image-20220524133813489.png)

- 6  Ahora vamos a las tablas creadas para las migraciones y las configuramos segun nos dice el tutorial:

  ![image-20220524141145166](C:\Users\Usuario\AppData\Roaming\Typora\typora-user-images\image-20220524141145166.png)

  

![image-20220524141221498](C:\Users\Usuario\AppData\Roaming\Typora\typora-user-images\image-20220524141221498.png)

- 7 Creamos base de datos de prueba y modificamos DatabaseSeeder y Postfactory con el codigo que nos proporciona el tutorial (https://cosasdedevs.com/posts/creacion-de-modelos-y-migracion-de-tablas-con-laravel-8/) en ambos casos. 

  ![image-20220524142229492](C:\Users\Usuario\AppData\Roaming\Typora\typora-user-images\image-20220524142229492.png)

  ![image-20220524142253734](C:\Users\Usuario\AppData\Roaming\Typora\typora-user-images\image-20220524142253734.png)

  - 8 Añadiendo la funcion para crear un usuario podremos acceder por fin a la aplicacion y asociar Posts.

  

  ![image-20220524142558462](C:\Users\Usuario\AppData\Roaming\Typora\typora-user-images\image-20220524142558462.png)

  

  ![image-20220524142855454](C:\Users\Usuario\AppData\Roaming\Typora\typora-user-images\image-20220524142855454.png)

  

  - 

  


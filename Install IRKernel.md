Instalación de IRKernel 
===================


***Objetivo***— Al finalizar esta actividad, el estudiante debe haber instalado exitosamente IRKernel para Jupyter.  
***Tipo de actividad*—** Tutorial.  
***Formato***— Individual.  
***Duración***— 00:15:00 horas.  
***Descripción***— Este tutorial explica el proceso de instalación de IRKernel.  
***Restricciones***— Previamente se debió haber instalado el programa R y Anaconda.   

**1.** Ejecute las siguientes lineas de código en R.
  
install.packages(c('repr', 'pbdZMQ', 'devtools'))   
devtools::install_github('IRkernel/IRdisplay')  
devtools::install_github('IRkernel/IRkernel')  
IRkernel::installspec()  

Aparecerá la siguiente ventana, de clic en **sí** para continuar.

![ok](https://raw.githubusercontent.com/yurymp/Ciencia-de-los-datos/IRKernel/IRKernel/1.PNG)

**2.** Luego aparecerá la siguiente ventana, de clic en **sí** para continuar.

![ok](https://raw.githubusercontent.com/yurymp/Ciencia-de-los-datos/IRKernel/IRKernel/2.PNG)


**3.** Elija el servidor que desee para descargar los paquetes, se recomienda utilizar **Colombia (Cali)**.   

![ok](https://raw.githubusercontent.com/yurymp/Ciencia-de-los-datos/IRKernel/IRKernel/3.PNG)

**4.** Se esta realizando la instalación de los paquetes de R.

![ok](https://raw.githubusercontent.com/yurymp/Ciencia-de-los-datos/IRKernel/IRKernel/4.PNG)

**5.** Una vez se haya ejecutado jupyter notebook en el **anaconda prompt** se puede verificar que en el botón **new** ubicado al lado derecho ya está la opción para crear notebooks para R.

![ok](https://raw.githubusercontent.com/yurymp/Ciencia-de-los-datos/IRKernel/IRKernel/5.png)



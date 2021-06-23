%Se corrigio el script 

% Titulo: Modelo matematico de temperatura 
% Descriocion: Scrip para graficar f(x) = 5/9(x-32)
% Autor: Irving Jeremy Martinez Avila @Neo
% Fecha: Jueve 15 de abril del 2021

clear

%Impresion de texto
disp('¿A que temperatura en grados fahrenheit corresponde 20*C?') 

%Se declaran las variables
syms x1 y1 temperatura1 x2 y2 temperatura2 
temperatura1 = 20

%Se realiza la operacion
x1= temperatura1*9/5
y1= x1+32

%Mostrar los resultador con fprintf
fprintf('El resultado es: %6.1f\n', y1)

x = [temperatura1:y1];
plot (x)
title ('Grafica de Fahrenheit a Celcius');
xlabel ('Celcius');
ylabel ('Fahrenheit');
grid

%-------------------------------------------------------------------
clear

%Impresion de texto
disp('¿A que temperatura en grados centigrados corresponde 100*F')

temperatura2 = 100

%Se realiza la operacion 
x2 = temperatura2-32
y2 = x2*5/9
fprintf('El resultado es: %6.1f\n', y2)

x = [temperatura2:y2];
plot (x)
title ('Grafica de Centigrados a Fahrenheit');
xlabel ('Fahrenheit');
ylabel ('Centigrados');
grid

%----------------------------------------------------------------
%limpiar variables
clear

%rango de -212 .. 212 en i = 0.2
f=-212:0.2:212;

%valor de la funcion
C=((f*5)/9)+32;

%dibujar x,y 
plot (f,C);

%titulo
title("Modelo Matematico de la Temperatura C   (f) =((f*5)/9)+32");

%etiqueta para x
xlabel ("Fahrenheit(F)");

%etiqueta para y
ylabel ("Celcius(C)");

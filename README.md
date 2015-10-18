# programacion_5.16
%5.16
%un circulo exentrico en los duntos dados a-b
%punto a
angulo=linspace(0,2*pi,50);
radio= 2;
x1=1+radio*cos(angulo);
y1=1+radio*sin(angulo);
plot(x1,y1,'r')
%punto b
hold on
x2=-2+radio*cos(angulo);
y2=1+radio*cos(angulo);
plot(x2,y2,'m')
axis('auto')

# Codigo-area-y-perimetro
Aquí añadiremos el código para obtener el área y perímetro de un rectángulo a partir de su base y altura
Utilizamos Matlab ya que es el programa que actualmente estamos dominando un poco, y conocemos algunos comandos.

Código
% Solicitar al usuario la base y la altura del rectángulo
base = input('Introduce la base del rectángulo: ');
altura = input('Introduce la altura del rectángulo: ');
area = base * altura;
perimetro = 2 * (base + altura);

fprintf('El área del rectángulo es: %.2f\n', area);
fprintf('El perímetro del rectángulo es: %.2f\n', perimetro);

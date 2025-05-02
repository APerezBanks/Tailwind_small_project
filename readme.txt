Small project to practice Tailwind Css skills



// gradient en tail wind

bg-gradient-to-* from - [color] to - [color]

example 
bg-gradient-to-b from-red-500 to-custom_orange

* 
t - top
r - right
b - bottom
l - left
tr - top right
tl  - top left
br - bottom right
bl - bottom left


// list

    list-disc
    list-decimal

    para cambiar el color de los puntos o numeros de las listas tenemos
    
    marker:text-color

example de grid 

grid para activarlo
grid-rows-num
grid-cols-num
h-full (altura que ocupa todo el espacio)
gap-num (espacio entre los grids)
col-span-num (para que un cuadrado ocupe mas hueco)

code example 

class="grid grid-rows-3 grid-cols-3 h-full gap-1"

 anadir images de fondo , en el archivo config.js
 
tailwind.config = {
    theme: {
        extend: {
            backgroundImage: {
                mobile: "url('mobile.jpg')",
                desktop: "url('desktop.jpg')",
            }
        }
    }
}
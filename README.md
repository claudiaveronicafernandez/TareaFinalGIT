# TareaFinalGIT
hola
Hola soy lucas
Algoritmo sin_titulo
	definir base, altura, area como real
	Escribir "ingrese la base", base
	leer base
	Escribir "ingrese la altura", altura
	leer altura
	Escribir "La superficie es de " base * altura / 2
FinAlgoritmo
El volumen de un prisma rectangular se calcula de la siguiente manera: volumen = largo x 
ancho x alto. Escribe una función que calcule el volumenDeRectPrism.
const form = document.getElementById('myForm');
form.addEventListener('submit', function(event) {
  event.preventDefault();
  validateForm();
});
function validateEmail(email) {
    const regex =  /^[^\s@]+@[^\s@]+\.[^\s@]{2,7}$/
    return regex.test(email)
  }
  function validateForm() {
    const emailInput = document.getElementById('email');
    const email = emailInput.value;
    if (!validateEmail(email)) {
      alert('Por favor ingrese un correo electrónico válido.');
    } else {
      alert('Correo electrónico enviado correctamente.');
    }
  }

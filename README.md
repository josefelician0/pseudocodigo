# pseudocódigo

##Crear un nuevo repositorio en el cual deberá definir mediante pseudocódigo las clases, 

## atributos y métodos para un sistema de una botillería. Centrarse en la parte de Inventario y NO en la Transaccional

class products
{ 

## Atributos

 NameProduct = ""  #Nombre producto.
 
 Category = "" #Categoria o tipo de producto.
 
 Quantity = 0 #Cantidad producto.
 
 Price = 0 #Precio del producto.
 
 Stock = 0 #Stock disponible.
 
 CriticalStock = 0 #Stock mínimo.
 
 ExpirationDate = "" #Fecha vencimiento.
 
 BarCode = "" #Código de barra.
 
 ## Métodos
 
 Discount {} #Descuento o promoción.
 
 CriticalStock_Warning {} #Aviso de stock mínimo.
 
 ExpirationDate_Warning {} #Aviso vencimiento de productos.
 
 }
 
 class workers
 {
 
 ##Atributos
 
 NameComplete = "" #Nombre completo.
 
 Gender = "" #Genero.
 
 Nationality = "" #Nacionalidad.
 
 Salary = 0 #Salario trabajador.
 
 DocumentNumber = "" #Número de identificacion o run.
 
 HiringDate = "" #Fecha de contratación.
 
 Area = "" #Área de trabajo.
 
 WorkHours = 0 #Horas de trabajo.
 
 }
 
 ##Métodos
 {
 
 ExtraHours {} #Horas extras.
 
 EndContract {} #Aviso Despido.
 
 NewArea {} #Cambio de área de trabajo.
 
 }

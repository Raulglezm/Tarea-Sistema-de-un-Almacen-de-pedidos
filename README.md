# Tarea-Sistema-de-un-Almacen-de-pedidos

![imagen](https://user-images.githubusercontent.com/91153605/136595952-38ef4858-283c-410c-b0b9-fd6efc8cf22c.png)


# CÓDIGO

```bash
<?xml version="1.0" encoding="iso-8859-15" standalone="yes"?>

<!DOCTYPE Almacen [
<!ELEMENT Almacen (pedidos)+>
	 <!ELEMENT Pedidos (plantas*, flores*, utensilios*)>

<!ELEMENT planta (cantidad, nombre)>
	 <!ELEMENT cantidad (#PCDATA)>
	 <!ELEMENT nombre (#PCDATA)>

<!ELEMENT flores (cantidad, nombre, color?)>
	 <!ELEMENT cantidad (#PCDATA)>
	 <!ELEMENT nombre (#PCDATA)>
	 <!ELEMENT color (#PCDATA)>

<!ELEMENT utensilios (cantidad, nombre)>
	 <!ELEMENT cantidad (#PCDATA)>
	 <!ELEMENT nombre (#PCDATA)>

]>

<Almacen>

	<Pedidos>

		<Plantas>

			<cantidad> 5 </cantidad>
			<nombre> Bromelia </nombre>

		</Plantas>

		<flores> 

	 	 <cantidad> 3 </cantidad>
		 <nombre> Rosa </nombre>
		 <color> Roja </color>

		</flores>

		<utensilios> 

			<cantidad> 1 </cantidad>

			<nombre> rastrillo </nombre>

		</utensilios>

	</Pedidos>
	
</Almacen>

```
#
# Procedimiento: 
Lo primero fue dividir las distintas etiquetas y sus características, para posteriormente crear el DTD y por último una muestra del funcionamiento del código, hay que tener en cuenta datos como que el color de las flores es opcional. 

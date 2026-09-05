# TALLER 1 ANA MARIA GARCIA GOMEZ 
# 0.
options(scipen = 999)
rm(list = ls())
nombre_negocio = "DULCE TORTAS"
nit = "32107435-8"
numero_factura = 1
tarifa_iva = 0.19
cat("Bienvenido al sistema de facturacion de DULCE TORTAS")

cliente <- readline("Nombre del cliente: ")
producto <- readline("producto: ")
cantidad_texto <- readline("cantidad: ")
valor_texto <- readline("valor unitario antes de IVA: ")
competencia_texto <- readline("precio del producto en la competencia: ")

cantidad <- as.numeric(cantidad_texto)
valor_unitario <- as.numeric(valor_texto)
precio <- valor_unitario
total_competencia <- as.numeric(competencia_texto)

cat("Tipo de cantidad:", class(cantidad), "\n")
cat("Tipo de valor_unitario:", class(valor_unitario), "\n")

subtotal <- cantidad * valor_unitario
iva <- subtotal * tarifa_iva
total <- subtotal + iva

total_competencia <- total_competencia * cantidad
ahorro <- total_competencia - total

cat("\n--- RESUMEN DE FACTURA ---\n")
cat("Cliente:", cliente, "\n")
cat("Producto:", producto, "\n")
cat("Cantidad:", cantidad, "\n")
cat("Precio Unitario:", precio, "\n")
cat("Subtotal:", subtotal, "\n")
cat("IVA (19%):", iva, "\n")
cat("Total:", total, "\n")
cat("Total Competencia:", total_competencia, "\n")
cat("Ahorro con respecto a la competencia:", ahorro, "\n")

venta2 <- float(input("Total de la venta2: "))
venta3 <- float(input("Total de la venta3: "))

total_dia <- total + venta2 + venta3
promedio_dia <- (total + venta2 + venta3) / 3

cat("resumen del dia")
cat("ventas registradas: 3")
cat("total vendido:", total_dia)
cat("promedio por venta:", promedio_dia)

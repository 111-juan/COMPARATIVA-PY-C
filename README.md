# Factorial en C y Python

## Descripción 📌
Este proyecto implementa el cálculo del **factorial** de un número utilizando dos lenguajes:
- **C** con la biblioteca **GMP** para manejar números grandes.
- **Python** con implementaciones iterativas y recursivas.

Ambas versiones miden el tiempo de ejecución para comparar el rendimiento entre los dos lenguajes y métodos.

---

## Requisitos 🛠️
### Para C:
- **GCC** (Compilador de C)
- **GMP (libgmp-dev)** para manejar números grandes

Para verificar si tienes GMP instalado:
```bash
 dpkg -l | grep libgmp-dev
```
Si no está instalado, usa:
```bash
sudo apt install libgmp-dev
```

### Para Python:
- **Python 3**
- No se requieren librerías adicionales

---

## Instalación y Uso 
### 1️⃣  Uso en C
#### Crear el archivo en la terminal
```bash
nano factorial_gmp.c
```
Copia y pega el código fuente.

#### Compilar el código
```bash
gcc factorial_gmp.c -o factorial_gmp -lgmp
```

#### Ejecutar el programa
```bash
./factorial_gmp
```

---

### 2️⃣ Uso en Python
#### Crear el archivo en tu editor de confianza: Colab, visual, etc.
```bash
factorial.py
```
Copia y pega el código fuente.

#### Ejecutar el programa
```bash
ejecutarlo.
```

---

## Comparación de Rendimiento 
| Método  | Lenguaje | Tiempo de ejecución |
|---------|---------|---------------------|
| Iterativo | C (GMP) | Muy rápido  |
| Recursivo | C (GMP) | Rápido  |
| Iterativo | Python | Medio  |
| Recursivo | Python | Más lento  |

 **Nota:** C con GMP es más eficiente para números muy grandes.

---

## Explicación del Código 
- **C (GMP)**: Usa `mpz_t` de GMP para manejar números grandes sin desbordamiento.
- **Python**: Usa `int`, que maneja enteros grandes automáticamente.
- Ambos programas permiten elegir entre **método iterativo y recursivo**.

---



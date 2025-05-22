# Sistema de Control de Inventario Básico en Python 🛒📦

Un sistema sencillo para gestionar inventarios iniciales mediante consola, ideal para aprender conceptos fundamentales de programación en Python.

## 🚀 Funcionalidades Actuales
1. **Interacción básica con usuario**
   - Mensaje de bienvenida personalizado con `print()`
   - Captura de datos mediante `input()` para:
     - 📛 Nombre del producto
     - 🔢 Cantidad en stock
     - 💲 Precio unitario

2. **Cálculos esenciales**
   - Fórmula de valor total: \[ \text{Valor Total} = \text{Cantidad} \times \text{Precio Unitario} \]
   - Almacenamiento temporal en variables

3. **Flujo básico**
   ```python
   # Ejemplo de flujo de ejecución
   print("Bienvenido al Sistema de Inventario")
   producto = input("Ingrese nombre del producto: ")
   cantidad = int(input("Ingrese cantidad disponible: "))
   precio = float(input("Ingrese precio unitario: "))
   total = cantidad * precio
   print(f"Valor total en inventario para {producto}: ${total:.2f}")
   ```

## 🔧 Tecnologías Utilizadas
- **Lenguaje**: Python 3.x
- **Entrada/Salida**: Consola interactiva
- **Almacenamiento**: Variables en memoria (sin persistencia)

## 📥 Instalación y Uso
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/sistema-inventario-basico.git
   ```
2. Ejecuta el script:
   ```bash
   python inventario.py
   ```

## 🌟 Próximas Mejoras (Roadmap)
- [ ] Persistencia de datos en archivo CSV
- [ ] Menú interactivo con opciones múltiples
- [ ] Sistema de categorización de productos
- [ ] Generación de reportes en PDF

## 🤝 Cómo Contribuir
1. Haz fork del proyecto
2. Crea tu rama: `git checkout -b feature/nueva-funcionalidad`
3. Realiza tus cambios y commit: `git commit -m 'Agrego funcionalidad X'`
4. Push a la rama: `git push origin feature/nueva-funcionalidad`
5. Abre un Pull Request

📄 **Licencia**: MIT  
🔗 **Repositorio**: [github.com/tu-usuario/sistema-inventario-basico](https://github.com/tu-usuario/sistema-inventario-basico)

¡Te invitamos a probar el sistema y dejar tus sugerencias en los issues! 💡

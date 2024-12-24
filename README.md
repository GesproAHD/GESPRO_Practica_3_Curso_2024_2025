# Simulación de Gestión de Versiones (Práctica P3)

Este README explica los pasos para realizar una simulación de control de versiones utilizando GitKraken (GK) y GitHub (GH). Para esta práctica, trabajaremos con el repositorio "Go Bees" y nuestro repositorio local llamado "GESPRO_PRACTICA_3_CURSO_2024_2025" que abrebiaremos a "P3". 
A continuación, se detallan los pasos a seguir para posicionarnos en un nuevo commit del repositorio "Go Bees" hasta que los cambios sean visibles en nuestra rama `master` local.


---

## **Guía completa de acciones**

### 1. **Go BEES (GK)**
- Posicionarse en el commit deseado para iniciar los cambios.
  - Haz clic derecho sobre el commit elegido.
  - Selecciona `Reset master to this commit` → Opción `Hard`.
![image](https://github.com/user-attachments/assets/51596647-bcf2-4628-836c-cb4dfa3cc381)

---

### 2. **P3 (GK)**
- Asegurarse de que la rama `master` está actualizada:
  - Realiza un `Fetch` para obtener los últimos cambios del remoto.
  - Haz un `Pull` para sincronizar `master` local con el remoto si es necesario.
- Posiciónate en la rama `master`.

![image](https://github.com/user-attachments/assets/80371e2a-5049-4a3e-9cc8-fbce75337367)
![image](https://github.com/user-attachments/assets/5b77eae1-c675-410e-8f34-1df5041c7a3b)

---

### 3. **P3 (GH)**
- Crear una nueva rama para la tarea:
  - Asegúrate de que `master` está actualizado tanto en local como en remoto.
  - Crea una nueva rama desde GitHub o desde GK con el nombre `GO-BEES`.
![image](https://github.com/user-attachments/assets/f1284713-d230-4858-9fc2-be6c6c983b69)

---

### 4. **P3 (GK)**
- Posicionarse en la nueva rama:
  - La nueva rama debería aparecer en el remoto.
  - Haz doble clic sobre la rama para subirla y posicionarte en local.
![image](https://github.com/user-attachments/assets/5f9964e2-7641-4d6b-88d9-b73cba239a6e)

---

### 5. **ARCHIVOS**
- Añadir los cambios del repositorio `Go Bees` al repositorio `P3`:
  - Copia todos los archivos de la carpeta `Go Bees` al repositorio `P3`, excepto la carpeta `.git`.

---

### 6. **P3 (GK)**
- Realizar el commit:
  - Ve a la pestaña `View Changes`.
    ![image](https://github.com/user-attachments/assets/6adc2440-b224-46fb-ba96-9bbcae3cd172)
  - Selecciona `Stage All Changes`.
    ![image](https://github.com/user-attachments/assets/7546b4df-7cfa-46bc-9782-afa9672dec59)
  - Escribe un nombre descriptivo para el commit (relacionado con la tarea).
  - Realiza el commit.
![image](https://github.com/user-attachments/assets/efd0fd10-2f41-4b2d-b2a0-6843a4797bcf)

---

### 7. **P3 (GK)**
- Subir los cambios al remoto:
  - Haz un `Fetch All`.
  - Si hay cambios remotos, realiza un `Pull` antes de hacer el `Push`.
  - Finalmente, realiza el `Push` de los cambios a la nueva rama.
![image](https://github.com/user-attachments/assets/a1ab2551-3e35-409b-b1e2-26775e14b189)

---

### 8. **P3 (GK)**
- Crear una Pull Request (PRQ):
  - Desde GK, selecciona la opción para crear una Pull Request.
  - Indica que deseas fusionar la nueva rama con `master` en el repositorio remoto.
![image](https://github.com/user-attachments/assets/8b413966-ba01-40f0-a226-f1e7449432ca)

---

### 9. **P3 (GH)**
- Gestionar la Pull Request en GitHub:
  - Ve a la sección `Pull Requests`.
  - Haz clic en `Compare & Pull Request` para la rama creada.
  - Revisa los cambios y crea la Pull Request.
  - Una vez aprobada, realiza el merge.
![image](https://github.com/user-attachments/assets/ea51a9ad-47b5-447e-b9b5-dd0f5f74069c)

---

### 10. **P3 (GK)**
- Actualizar `master` en local:
  - Posiciónate en la rama `master` en local (doble clic sobre `master`).
  - Realiza un `Fetch All`.
  - Realiza un `Pull` para obtener los últimos cambios fusionados desde remoto.

---

## Participantes
- Aarón del Santo Izquierdo
- Daniel Miguel Muiña
- Héctor Sáchez García

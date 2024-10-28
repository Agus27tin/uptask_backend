## Importante

**Debes seguir estos pasos para ejecutar correctamente el proyecto. Es sencillo.**

1. **Configura las variables de entorno (.env):**  
   En el archivo `.env`, donde dice `MONGODB=`, necesitas tener una cuenta en MongoDB Atlas y crear un cluster. Ingresa allí tus credenciales en este formato:
   ```plaintext
   MONGODB=mongodb+srv://usuario:contraseña@cluster0.oze3z.mongodb.net/

2. **Configura una cuenta en Mailtrap:**
   
   En este paso, debes hacer lo siguiente:
   - Regístrate en [Mailtrap](https://mailtrap.io/).
   - Una vez registrado, ve a la sección **Email Testing > Inboxes** y crea una nueva bandeja de entrada (**Inbox**).
   - Después, desplázate un poco hacia abajo y elige **Node.js** como lenguaje de programación.
   - Copia el código que te proporciona Mailtrap y pégalo en el archivo `helpers/email.js` dentro del proyecto, reemplazando los valores con los de Mailtrap.
   - Una vez que inicies el proyecto, podrás ver los correos en la misma pestaña de **Email Testing** en Mailtrap.

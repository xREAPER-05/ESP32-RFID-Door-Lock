# 🔐 ESP32 RFID Door Lock

Sistema de control de acceso mediante RFID desarrollado con ESP32 y el lector RC522.

El proyecto permite autorizar o denegar el ingreso de un usuario comparando el UID de una tarjeta RFID registrada previamente.

---

# 📌 Características

- Lectura de tarjetas RFID.
- Identificación mediante UID.
- Comparación con usuarios autorizados.
- Activación de una cerradura electrónica.
- Indicador LED de acceso permitido.
- Indicador LED de acceso denegado.
- Comunicación Serial para depuración.

---

# 🛠️ Tecnologías

- ESP32
- Arduino IDE
- MFRC522
- RFID RC522
- SPI

---

# ⚙️ Funcionamiento

1. El lector RC522 detecta una tarjeta RFID.
2. Se obtiene el UID de la tarjeta.
3. El sistema compara el UID con el registrado.
4. Si coincide:
   - Se activa la cerradura.
   - Se enciende el LED verde.
5. Si no coincide:
   - Se rechaza el acceso.
   - Se enciende el LED rojo.

---

# 👨‍💻 Autor

César David Rodríguez Mora

Tecnólogo en Computación y Desarrollo de Software

Bogotá D.C., Colombia

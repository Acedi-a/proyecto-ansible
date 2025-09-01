# Proyecto InnovaSys - Configuración DevOps


---

## 🚀 ¿Cómo ejecuto el playbook?

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/Acedi-a/proyecto-ansible.git
   cd proyecto-ansible
   ```

2. **Configura el inventario**  
   Editar el `inventory/inventory.ini` y añadir las direcciones IP o nombres de los servidores que se quiera administrar.

3. **Ejecutar el playbook principal:**

   ```bash
   ansible-playbook -i inventory/inventory.ini playbooks/site.yml
   ```

   > Se puede modificar el archivo de inventario o el playbook según las necesidades.

---

## 🛠️ Requisitos

- [Ansible](https://www.ansible.com/) instalado en tu máquina.
- Acceso SSH a los servidores de destino.
- Haber configurado las variables necesarias si tu playbook las requiere.

---

## 💡 Consejos

- Si se necesita privilegios de superusuario, añadir la opción `-K` al comando para que te pida la contraseña de sudo.
- Si la clave SSH tiene passphrase, se puede añadir `--ask-pass` para que la solicite.

---

¿Dudas, sugerencias o mejoras?  
¡No dudes en abrir un issue o un pull request! 😄

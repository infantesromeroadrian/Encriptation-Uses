# Proyecto de Encriptación y Hash en Python

Este proyecto contiene ejemplos prácticos de implementación de algoritmos de encriptación y funciones hash en Python. Está diseñado con fines educativos para comprender los conceptos fundamentales de la criptografía.

## Estructura del Proyecto

- `symmetric_encryption.py`: Ejemplos de encriptación simétrica (AES)
- `asymmetric_encryption.py`: Ejemplos de encriptación asimétrica (RSA)
- `hash_functions.py`: Ejemplos de funciones hash (MD5, SHA-256, etc.)
- `password_hashing.py`: Técnicas seguras para el almacenamiento de contraseñas
- `digital_signatures.py`: Implementación de firmas digitales
- `hybrid_encryption.py`: Ejemplo de encriptación híbrida

## Requisitos

Para ejecutar estos ejemplos, necesitarás Python 3.6+ y las siguientes bibliotecas:

```
cryptography
pycryptodome
bcrypt
hashlib (incluida en la biblioteca estándar)
```

Puedes instalar las dependencias con:

```bash
pip install -r requirements.txt
```

## Uso

Cada archivo puede ejecutarse de forma independiente para ver ejemplos de diferentes técnicas de encriptación y hash:

```bash
python symmetric_encryption.py
python hash_functions.py
# etc.
```

## Advertencia

Este código es solo para fines educativos. Para aplicaciones en producción, consulta con expertos en seguridad y sigue las mejores prácticas actualizadas.

## Recursos Adicionales

Para más información sobre encriptación y funciones hash, consulta el archivo `docs/encriptacion_y_hash.txt` en este repositorio. 
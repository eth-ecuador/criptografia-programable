# Criptografía Programable (Versión 2)

Curso intensivo en español sobre criptografía programable. Consta de 3 módulos que exploran los fundamentos matemáticos, pruebas de conocimiento cero (ZKP), y los ecosistemas de Aztec con Noir y Starknet con Cairo, con un enfoque en escalabilidad de Ethereum y privacidad. Combina teoría, ejemplos prácticos y recursos de apoyo.

## HIGHLIGHTS

* **Modalidad:** Clases virtuales por Google Meet, serán grabadas.
* **Duración del programa:** 3 semanas/módulo. Las 2 primeras semanas son clases y estudio, última semana es el buildathon. Durante las 2 semanas de estudio, se tendrán las clases de 2hrs, 2-3 veces a la semana, aparte horas de oficina y keynotes de ponentes invitados del ecosistema.
* **Pre requisitos por clase:** Leer el material preliminar de apoyo para preparación.
* **Sobre el buildathon:** El programa incluye 3 buildathones donde los participantes pueden contribuir de diversas maneras según lo aprendido, como:
  * Redactar un blog que explique un concepto teórico en detalle.
  * Implementar circuitos ZK con Noir o Cairo.
  * Desarrollar una aplicación parcial o end-to-end utilizando los conocimientos adquiridos.
  * Implementar algún algoritmo criptográfico visto durante las clases en cualquier programa: Jupyter notebook, Sage, etc.
* **Comunidad:** Se manejará un servidor de Discord para notificaciones, discusiones, y comunicación durante el transcurso del programa.
* **Idioma:** Contenido y clases en español, con referencias y keynotes en inglés-español.
* **Número de participantes:** 10 - 20.&#x20;
* **Preselección de participantes:** Se llevará una fase de preselección de los participantes con requisito mínimo el ser estudiante de Ingeniería o Ciencias desde 4to semestre en adelante o graduado/egresado en alguna carrera técnica. Se busca que los participantes tengan bases fuertes en matemáticas y/o programación.&#x20;
* Certificado: Los participantes seleccionados podrán obtener la certificación si han culminado el curso exitosamente con contribuciones en los 3 buildathones y su asistencia a las clases virtuales.

## SÍLABO

### MÓDULO 1: Fundamentos Matemáticos y Pruebas de Conocimiento Cero

📆 **Semanas 1-2: Teoría y Aplicaciones**

* **Matemáticas para Criptografía Programable (Primitivas Esenciales)**
  * **Teoría de números:** Divisibilidad, números primos, y funciones aritméticas.
  * **Aritmética modular:** Conceptos básicos, inversos multiplicativos, y exponentes.
  * **Extensiones de campos (Field Extensions):** Introducción a campos finitos y su uso en criptografía.
  * **Grupos:** Teoría de grupos y su aplicación en criptografía.
  * **Curvas elípticas (Elliptic Curves):** Fundamentos y aplicaciones en criptografía moderna.
  * **Criptografía clásica y moderna:** De cifrados simétricos a asimétricos (RSA, Diffie-Hellman).
  * Recursos:
    * [Crypto101](https://www.crypto101.io/),
    * [Cryptography Handbook](https://drive.google.com/drive/folders/1uoH11bXs5G_H7v8b0PTIBNXBPSjKz-Oi?dmr=1\&ec=wgc-drive-globalnav-goto)
    * [Number Theory](https://drive.google.com/file/d/1-jBKgQ1J8NWYBXKfknJp2YuMxo6Y9CEQ/view?usp=sharing)
    * [MoonMath Manual](https://github.com/LeastAuthority/moonmath-manual)
    * [Abstract Algebra: Theory and Applications (AATA)](https://judsonbooks.org/aata-files/aata-20240706.pdf)
    * [Elliptic Curves: Number Theory and Cryptography](https://people.cs.nycu.edu.tw/~rjchen/ECC2012S/Elliptic%20Curves%20Number%20Theory%20And%20Cryptography%202n.pdf)
    * [A Graduate Course in Applied Cryptography](https://toc.cryptobook.us/)
* **Introducción a las Pruebas de Conocimiento Cero**
  * ¿Qué son y por qué son necesarias? (Escalabilidad y Privacidad).
  * Tipos de ZK-Proofs: zk-SNARKs vs zk-STARKs.
  * Aplicaciones prácticas en blockchain: transacciones privadas y verificación eficiente.
  * Recursos:
    * [_Four Easy Pieces in Programmable Cryptography_](https://drive.google.com/drive/folders/1CEDR3-F68alGT3r6U4nPdpIO2g07YqnH?dmr=1\&ec=wgc-drive-globalnav-goto)
    * [_Why and How zk-SNARK Works_](https://drive.google.com/drive/folders/1k9KT6wti_44TxGOof0Ebiiyy6Wm0qKr-?dmr=1\&ec=wgc-drive-globalnav-goto)
    * [SNARK Fundamentals](https://erroldrummond.gitbook.io/snark-fundamentals)
    * [A Survey on the Applications of Zero-Knowledge Proofs](https://arxiv.org/pdf/2408.00243)

📆 **Semana 3: Buildathon 1**\
🛠 **Proyecto:**

* Escribir un artículo explicando un concepto matemático (por ejemplo, el algoritmo de Euclides o aritmética modular).
* Implementar un algoritmo criptográfico en Python (por ejemplo, RSA o un cifrado simétrico como AES).
* Crear una aplicación básica que demuestre una prueba de conocimiento cero (puede ser un ejemplo simple usando una librería como Libsnark).

### MÓDULO 2: Aztec y Noir - Privacidad, SNARKs y Pruebas Recursivas

📆 **Semanas 4-5: Teoría y Aplicaciones**

* **SNARKs y Pruebas Recursivas**&#x20;
  * SNARKs
  * Compromisos KZG (Kate-Zaverucha-Goldberg).
  * Sistemas de prueba: Plonk y Ultraplonk.
  * Reducción de restricciones y pruebas recursivas.
  * Aplicaciones en privacidad y descentralización: ejemplos como transacciones privadas y votaciones seguras.
  * Recursos:
    * Plonk: A Universal SNARK for Trusted Setup
    * KZG Commitments Explained
* **Aztec 101 - Programación con Noir y Sandbox de Aztec**
  * Introducción a Noir: sintaxis y estructura.
  * ACIR (Abstract Circuit Intermediate Representation) y backend de Barrentenberg.
  * Ejecución en navegadores con WebAssembly (WASM).
  * Ejemplo de código en el ecosistema de Aztec
  * Recursos:&#x20;
    * [Noir Documentation](https://noir-lang.org/docs/noir/concepts/data_types/)
    * [https://github.com/noir-lang/awesome-noir](https://github.com/noir-lang/awesome-noir)
    * [Building a web app with Noir and Barretenberg](https://noir-lang.org/docs/tutorials/noirjs_app)
    * [ https://aztec.network/research ](https://aztec.network/research)

📆 **Semana 6: Buildathon 2**\
🛠 **Proyecto:**

* Desarrollar un contrato en Noir.
* Implementar una prueba recursiva (por ejemplo, para verificar múltiples transacciones).
* Caso de uso práctico: sistema de identidad digital ecuatoriana (verificación privada de identidad con Noir).



### **MODULE 3: STARKNET & Cairo - Scalability with STARKs**

📆 **Week 7-8: Theory & Applications**

* **Cairo y STARKs**
  * Conceptos fundamentales:
    * Ciclo de vida de un STARK: declaración, LDE (Low-Degree Extension) y compromiso.
    * Restricciones polinomiales.
    * Protocolo de compromiso FRI (Fast Reed-Solomon Interactive Oracle Proofs).
    * Generación y verificación de la prueba.
    * Recursos:
      * [_STARKs: A Gentle Introduction_ de StarkWare](https://starkware.co/stark-101/)
      * [Anatomy of a STARK](https://aszepieniec.github.io/stark-anatomy/)
* **Desarrollo en STARKNET**
  * Creación de contratos inteligentes con Cairo.
  * Ejemplo de código de una dApp escalable en el ecosistema de Starknet
  * Recursos:
    * [Stark 101](https://starkware.co/stark-101/)
    * [Cairo 101](https://github.com/starknet-edu/starknet-cairo-101/blob/main/README.es.md)

📆 **Semana 9: Buildathon 3**\
🛠 **Proyecto:**

* Construir una dApp en Starknet (por ejemplo, un sistema de votación escalable).
* Implementar un sistema basado en STARKs (como una verificación eficiente de múltiples transacciones).

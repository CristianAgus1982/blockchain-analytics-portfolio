\# 🪙 BITCOIN FUNDAMENTALS - Mis Notas Visuales

\*\*Fecha:\*\* 19 Enero 2026

\*\*Fuente:\*\* 3Blue1Brown - "But how does bitcoin actually work?"



---



\## 🎯 EL PROBLEMA QUE BITCOIN RESUELVE



\*\*SIN BITCOIN (Sistema tradicional):\*\*

```

Alice ----$10----> Bob

&nbsp;        ↓

&nbsp;   \[BANCO = Intermediario]

&nbsp;        ↓

&nbsp;   - Cobra comisiones

&nbsp;   - Puede bloquear transacciones

&nbsp;   - Necesitas confiar en ellos

```



\*\*CON BITCOIN:\*\*

```

Alice ====₿10====> Bob

&nbsp;        ↓

&nbsp;   \[RED P2P = Sin intermediario]

&nbsp;        ↓

&nbsp;   - Sin comisiones altas

&nbsp;   - Nadie puede censurarte

&nbsp;   - No necesitas confiar en nadie

```



---



\## 📖 ¿QUÉ ES EL LEDGER? (Libro de cuentas)



Es un \*\*libro público\*\* donde se registran TODAS las transacciones:

```

BLOCKCHAIN = LEDGER PÚBLICO



┌─────────────────────────────┐

│ Alice paga 10 BTC a Bob     │

│ Bob paga 5 BTC a Charlie    │

│ Charlie paga 2 BTC a Alice  │

│ ...                         │

│ \[Miles de transacciones]    │

└─────────────────────────────┘



TODO EL MUNDO puede verlo

NADIE puede borrarlo

```



---



\## 🔑 FIRMAS DIGITALES (¿Cómo sé que eres TÚ?)



Cada persona tiene DOS llaves:

```

👤 ALICE tiene:



🔐 LLAVE PRIVADA (SECRET KEY)

&nbsp;  - NUNCA la compartes

&nbsp;  - La usas para FIRMAR transacciones

&nbsp;  - Como tu contraseña del banco



🔓 LLAVE PÚBLICA (PUBLIC KEY)

&nbsp;  - La compartes con TODO EL MUNDO

&nbsp;  - Es tu "dirección Bitcoin"

&nbsp;  - Como tu número de cuenta

```



\*\*EJEMPLO DE TRANSACCIÓN:\*\*

```

Alice quiere enviar 10 BTC a Bob:



1️⃣ Alice escribe: "Yo (Alice) pago 10 BTC a Bob"



2️⃣ Alice FIRMA con su llave privada 🔐

&nbsp;  (Genera una firma única imposible de falsificar)



3️⃣ Todos pueden VERIFICAR con la llave pública de Alice 🔓

&nbsp;  ✅ "Sí, esta firma es de Alice"

&nbsp;  ❌ "No, alguien intentó falsificarla"

```



---



\## ⛓️ ¿QUÉ ES LA BLOCKCHAIN?



Es una \*\*cadena de bloques\*\* que contiene transacciones:

```

BLOQUE 1           BLOQUE 2           BLOQUE 3

┌──────────┐      ┌──────────┐      ┌──────────┐

│ TX 1     │      │ TX 501   │      │ TX 1001  │

│ TX 2     │──────│ TX 502   │──────│ TX 1002  │

│ ...      │      │ ...      │      │ ...      │

│ TX 500   │      │ TX 1000  │      │ TX 1500  │

│          │      │          │      │          │

│ HASH:    │      │ HASH:    │      │ HASH:    │

│ 0000abc  │      │ 0000def  │      │ 0000ghi  │

└──────────┘      └──────────┘      └──────────┘

```



---



\## ⛏️ MINING (Minería)



Los mineros buscan un número (NONCE) que haga que el hash del bloque empiece con muchos ceros:

```

BLOQUE SIN NONCE:

Hash = "a3f9d2c8b1e4..."  ❌ (No empieza con 0000)



BLOQUE CON NONCE = 67890:

Hash = "0000f3a9c2b1..."  ✅ ¡ENCONTRADO!



Esto requiere BILLONES de intentos

= MUCHA electricidad = TRABAJO

```



---



\## 💡 MIS CONCEPTOS CLAVE:



1\. \*\*Bitcoin = Ledger público descentralizado\*\*

2\. \*\*Firmas digitales = Autenticidad\*\*

3\. \*\*Mining = Seguridad\*\*

4\. \*\*Blockchain = Historial inmutable\*\*



---



\## ❓ MIS PREGUNTAS:



1\. ¿Qué es un "change address"?

2\. ¿Cómo funcionan las "wallets"?

3\. ¿Qué es UTXO?


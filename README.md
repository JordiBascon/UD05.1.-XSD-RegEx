# UD05.1.-XSD-RegEx

## 1.- Tabla organizativa del documento XML:

Nombre Usuario |     Correo Electrónico      | Número Teléfono | Código Postal | Contraseña
---------------|-----------------------------|-----------------|---------------|------------
ManuelBas      | manuelbascon98@gmail.com    | +34 646 092 134 | 41610         | mbf2424
JoaquinRP      | joaquinrap1998@gmail.com    | +34 635 789 954 | 41000         | jrp1243
MariaFuentes   | mariafuentes1928@gmail.com  | +34 674 345 126 | 41611         | 986217M
IsaMariPB      | isabelmaria2@gmail.com      | +34 689 234 523 | 41610         | im19231
David2001      | david2001@gmail.com         | +34 621 654 788 | 41611         | dvpteq9

## 2.- Validaciones de campos
### `Usuario`

Para que un nombre de usuario pueda considerarse correcto y valido debe:
- Tener al menos 4 caracteres.
- Si tiene caracteres especiales solo puede tener caracteres alfanuméricos ASCII o guión (-) o guión bajo (_).

Fuente: [Clic Aquí](https://kb.mailfence.com/es/kb/hay-algun-requisito-para-que-el-nombre-de-usuario-sea-valido/).

### `Correo`

`Sintaxis:` `usuario@dominio`

`NOMBRE DE USUARIO`
PERMITE        |    NO PERMITE     | 
---------------|-----------------------------|
Letras [a-z]   | . al principio y al final    | 
Números [0-9]  | . consecutivos ni otros caracteres especiales   | 
Caracteres especiales [_ , - , .]   | Los caracteres especiales deben ir seguidos de más letras o números  | 

`NOMBRE DE DOMINIO`
- Consta de una o más partes separadas por un punto (dominio.com)
- La segunda parte debe tener dos o más caracteres (.com, .org)

  PERMITE
- Letras [a-z]
- Números [0-9]
- Guionmes [-] excepto al principio y al final

Fuente: [Clic Aquí](https://snov.io/knowledgebase/es/que-es-un-formato-de-direccion-de-correo-electronico-valido/).

### `Número`

### `Código Postal`

Actualmente el territorio español se divide en 11.752 códigos postales.
- Las dos primeras cifras hacen referencia a la prinvia por orden alfabético. (41(Sevilla), 21(Huelva)).
  
`Dato Curioso: antes Ceuta y Melilla  tenían los códigos postales de Cádiz (11) y Málaga (29) respectivamente, actualmente tienen los suyos propios.`

<img width="682" height="490" alt="image" src="https://github.com/user-attachments/assets/6f791d9a-49f8-4cab-bdf5-bd54d481f4dd" />

- La tercera cifra indica el encaminamiento.
- La cuarta cifra representa la ruta
- La quinta cifra refresenta el reparto

`Dato Curioso: en cada capital de provincia existen códigos reservados para usos especiales como correos (070) o correspondencia de organismos oficiales(071)-.`

### `Contraseña`

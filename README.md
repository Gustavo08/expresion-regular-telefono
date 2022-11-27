# Expresión regular para validar un teléfono con el siguiente formato +?? ??? ??? ????

```bash
  let validPhone = /^\+?\d{2}(\s\d{3}){2}\s\d{4}$/;
```

  - inicio de linea
  - \+? Que tenga o no el caracter de +
  - \d{2} seguido de 2 digitos
  - (\s\d{3}){2} repetir el patron 2 veces de un espacio en blanco, seguido de 3 digitos.
  - \s un espacio en blanco
  -  \d{4} seguido de 4 digitos
  - $ fin de la línea.
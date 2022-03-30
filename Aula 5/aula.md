# Quantos VBOs e VAOs?

GLfloat vert_P[]{
  x, y, z,
  x, y, z,
}

 - Um atributo, então 1 VBO e um VAO.

GLfloat vert_P1[]{
  x, y, z,
}

- Um atributo, então 1 VBO.

__________________________________________________

GLfloat vert_PC[]{
  x, y, z, r, g, b,
  x, y, z, r, g, b,
}

- Dois atributos, portanto 2 VAO.

  gerar novo glAttribPointer

GLfloat vert_PC2 []{
  x, y, z, r, g, b,
}

- um VBO.

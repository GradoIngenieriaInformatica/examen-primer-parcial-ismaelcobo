db.cursos.updateOne(
  { nombre: "Arquitectura de Software" },
  { $set: { creditos: 7 } }
)
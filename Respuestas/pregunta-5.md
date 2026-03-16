db.cursos.aggregate([
  {
    $group: {
      _id: "$nivel",
      total_creditos: { $sum: "$creditos" }
    }
  }
])
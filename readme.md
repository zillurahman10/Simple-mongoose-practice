# All Problems should be solved in nosql booster or studio 3T

// Problem 1 = solved
// db.person_data.find({"address.city" : 'New York'})

// Problem 2 = solved
// db.person_data.find({"email": "johndoe@example.com"}).project({ "favorites.food" : 1 })

// Problem 3 = solved
// db.person_data.find({"favorites.food" : "pizza"}).sort({ age:1 })

//Problem 4 = solved
// db.person_data.find({ age: { $gt: 30 }, "favorites.color": "green" })

// Problem 5 = solved
// db.person_data.find({ "favorites.movie" : "The Shawshank Redemption" }).count()

//Problem 6 = solved
// db.person_data.updateOne({email : "johndoe@example.com"},
// {$set:{ "address.zipcode" : 1212 }},
// )

// Problem 7 = solved
// db.person_data.deleteOne({email : "alicewilliams@example.com"})

// Problem 8 = not solved
// db.person_data.aggregate([
// {
// $group: {
// _id: {
// movie: "$favorites.movie",
// avarageAge: { $avg: "$age" }
// }
// },
// }
// ])

// Problem 9 =
// db.person_data.find(
// { "favorites.food" : "pizza" },
// { avarageAge : { $avg: "$age" } }
// )

// Problem 10

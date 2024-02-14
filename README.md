
#Object JavaScript








<html>
    <head>
        <meta charset="UTF-8" />
    </head>
    <script>

     
        const person = {
            name: "Lais",
            age: 40,
            address: {
                street: "Avenida 123",
                city: "são Paulo",

            },
        }

        console.log(person.name)
        console.log(person.age)
        console.log(
            `${person.name} tem ${person.age} anos e reside em ${person.address.city} ${person.address.street}`
        )
    </script>
</html>

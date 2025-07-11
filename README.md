<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cards preview</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            display: flex;
            margin: 10px;
            padding: 20px;
            background-color:rgb(255, 0, 0);
        }

        .card {
            background-color:white;
            border: 2px solid black;
            border-radius: 25px;
            width: 250px;
            height: 600px;
            margin: 10px;
        }

        .pikachu {
            background-color: yellow;
            border: 2px solid black;
            border-radius: 25px;
            width: 250px;
            height: 600px;
            margin: 10px;
        }
        .bulbasaur {
            background-color: greenyellow;
            border: 2px solid black;
            border-radius: 25px;
            width: 250px;
            height: 600px;
            margin: 10px;
        }
        .blastoise {
            background-color: lightblue;
            border: 2px solid black;
            border-radius: 25px;
            width: 250px;
            height: 600px;
            margin: 10px;
        }
        .charizard {
            background-color:goldenrod;
            border: 2px solid black;
            border-radius: 25px;
            width: 250px;
            height: 600px;
            margin: 10px;
        }

        .image {
            padding: 20px;
        }

        .image img {
            border: 2px solid black;
            border-radius: 12px;
            ;
            padding: 3px;

        }

        .type {
            padding: 2px 16px;
        }

        .type span {
            font-size: 18px;
            color: black;
            background-color: lightgray;
            border: 2px solid black;
            text-align: center;
            border: none;
        }

        .content {
            padding: 3px 16px;
            align-content: center;
        }

        .content p {
            font-size: 12px;
        }

        .button:hover {
            background-color: rgba(110, 141, 213, 0.8);
            cursor: pointer;
        }

        .button {
            align-content: center;
            text-align: center;
            background-color: rgb(42, 194, 245);
            width: 220px;
            height: 30px;
            /* margin: 10px; */
            border-radius: 23px;
            color: white;
        }
    </style>
</head>

<body>
    <div class="card">
        <div class="image">
            <img width="200" height="300" src="https://upload.wikimedia.org/wikipedia/en/e/e4/Ash_Ketchum_Journeys.png"
                alt="">
        </div>

        <div class="type">
            <span>Type - Pokemon trainer</span>
        </div>

        <div class="content">
            <h2>Ash Ketchum</h2>
            <p>Ash Ketchum is the main protagonist of the Pokémon series. He is a passionate and determined Pokémon
                Trainer from Pallet Town who dreams of becoming a Pokémon Master. Ash is known for his strong bond with
                his Pokémon, fearless attitude, and ability to think quickly during battles. His journey across various
                regions has made him a symbol of friendship, perseverance, and growth.
            </p>
            <div class="button">
                Read more
            </div>
        </div>
    </div>

    <div class="pikachu">
        <div class="image">
            <img width="200" height="300"
                src="https://oyster.ignimgs.com/mediawiki/apis.ign.com/pokemon-blue-version/8/89/Pikachu.jpg?width=325" alt="">
        </div>

        <div class="type">
            <span>Type - ⚡ Electric</span>
        </div>

        <div class="content">
            <h2>Pikachu</h2>
            <p>Pikachu is an Electric-type Pokémon and Ash’s very first and most loyal companion. Known for its cute
                appearance and cheerful personality, Pikachu is also incredibly powerful, using moves like Thunderbolt
                and Iron Tail to defeat strong opponents. Its speed and bravery in battles have made it an icon of the
                Pokémon franchise.
            </p>
            <div class="button">
                Read more
            </div>
        </div>
    </div>

    <div class="bulbasaur">
        <div class="image">
            <img width="200" height="300" src="https://static.vecteezy.com/system/resources/previews/051/480/562/non_2x/cute-bulbasaur-pokemon-free-vector.jpg"
                alt="">
        </div>

        <div class="type">
            <span>Type - 🌿 Gras</span>
        </div>

        <div class="content">
            <h2>Bulbasaur</h2>
            <p>Bulbasaur is a dual-type Grass/Poison Pokémon that has been one of Ash’s most reliable team members. Calm
                and loyal, Bulbasaur prefers to stay in its original form and has a strong sense of responsibility. It
                uses moves like Vine Whip, Razor Leaf, and SolarBeam and is often seen acting as a peacemaker among
                other Pokémon.
            </p>
            <div class="button">
                Read more
            </div>
        </div>
    </div>

    <div class="blastoise">
        <div class="image">
            <img width="200" height="300" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTM0ZvnJ2EPHO6TyFVkxcJqXav1cvfBbfpJKQ&s"
                alt="">
        </div>

        <div class="type">
            <span>Type - 💧 Water</span>
        </div>

        <div class="content">
            <h2>Blastoise</h2>
            <p>Blastoise is a Water-type Pokémon that evolves from Squirtle. It has large water cannons on its back,
                which it uses to unleash powerful attacks like Hydro Pump. Though not originally owned by Ash, Blastoise
                has played key roles in many episodes and is admired for its strength, defense, and battle skills.
            </p>
            <div class="button">
                Read more
            </div>
        </div>
    </div>

    <div class="charizard">
        <div class="image">
            <img width="200" height="300" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT7fbUHbXD7quBO5gRk19otqkfYXdTiYsE2IQ&s"
                alt="">
        </div>

        <div class="type">
            <span>Type - 🔥 Fire</span>
        </div>

        <div class="content">
            <h2>Charizard</h2>
            <p>Charizard is a Fire/Flying-type Pokémon that evolved from Ash’s Charmander. Although it was once
                rebellious and refused to obey Ash, over time it grew to trust him and became one of his most powerful
                allies. With devastating moves like Flamethrower and Dragon Claw, Charizard has won many important
                battles and is known for its fierce determination.
            </p>
            <div class="button">
                Read more
            </div>
        </div>
    </div>
</body>

</html>

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ahmed Dev</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial;
        }

        body{
            background:#0f172a;
            color:white;
        }

        header{
            height:100vh;
            display:flex;
            flex-direction:column;
            justify-content:center;
            align-items:center;
            text-align:center;
            background:linear-gradient(135deg,#020024,#090979,#00d4ff);
        }

        header h1{
            font-size:65px;
            margin-bottom:15px;
        }

        header p{
            font-size:22px;
            width:80%;
            max-width:700px;
            color:#e2e8f0;
        }

        .btn{
            margin-top:30px;
            padding:15px 35px;
            border:none;
            border-radius:12px;
            background:white;
            color:black;
            font-size:20px;
            cursor:pointer;
            transition:0.3s;
        }

        .btn:hover{
            transform:scale(1.1);
            background:#38bdf8;
            color:white;
        }

        .section{
            padding:80px 20px;
            text-align:center;
        }

        .section h2{
            font-size:40px;
            margin-bottom:50px;
        }

        .cards{
            display:flex;
            justify-content:center;
            flex-wrap:wrap;
            gap:25px;
        }

        .card{
            background:#1e293b;
            width:280px;
            padding:30px;
            border-radius:20px;
            transition:0.4s;
        }

        .card:hover{
            transform:translateY(-12px);
            background:#334155;
        }

        .card h3{
            color:#38bdf8;
            margin-bottom:15px;
            font-size:28px;
        }

        .card p{
            color:#cbd5e1;
        }

        footer{
            background:#020617;
            text-align:center;
            padding:25px;
            color:#94a3b8;
        }
    </style>
</head>

<body>

<header>

    <h1>🚀 Ahmed Dev</h1>

    <p>
        Future Web Developer & Game Creator
    </p>

    <button class="btn" onclick="welcome()">
        Start Journey
    </button>

</header>

<section class="section">

    <h2>🔥 My Skills</h2>

    <div class="cards">

        <div class="card">
            <h3>HTML</h3>
            <p>
                Building powerful website structures.
            </p>
        </div>

        <div class="card">
            <h3>CSS</h3>
            <p>
                Designing modern and responsive pages.
            </p>
        </div>

        <div class="card">
            <h3>JavaScript</h3>
            <p>
                Making websites interactive and dynamic.
            </p>
        </div>

    </div>

</section>

<section class="section">

    <h2>🎯 My Goals</h2>

    <div class="cards">

        <div class="card">
            <h3>Learn</h3>
            <p>
                Improve coding skills every day.
            </p>
        </div>

        <div class="card">
            <h3>Create</h3>
            <p>
                Build amazing websites and games.
            </p>
        </div>

        <div class="card">
            <h3>Earn</h3>
            <p>
                Start freelancing and earn online.
            </p>
        </div>

    </div>

</section>

<footer>
    © 2026 Ahmed Dev | GitHub Portfolio
</footer>

<script>

function welcome(){
    alert("Welcome Ahmed 🔥");
}

</script>

</body>

</html>

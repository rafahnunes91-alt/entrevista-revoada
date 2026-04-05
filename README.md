<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Equipe Entrevista — Revoada RP</title>
    <meta name="description" content="Formulário de entrevista para candidatos a staff do servidor Revoada RP.">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #0f172a;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            width: 90%;
            max-width: 700px;
            background: #1e293b;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 0 20px rgba(0,0,0,0.3);
        }

        h1 {
            text-align: center;
            margin-bottom: 20px;
        }

        p {
            text-align: center;
            margin-bottom: 30px;
            color: #cbd5e1;
        }

        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 8px;
        }

        input, textarea {
            width: 100%;
            padding: 12px;
            border: none;
            border-radius: 8px;
            outline: none;
        }

        textarea {
            resize: vertical;
            min-height: 100px;
        }

        button {
            width: 100%;
            padding: 14px;
            background: #2563eb;
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background: #1d4ed8;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Entrevista Staff — Revoada RP</h1>
        <p>Preencha o formulário abaixo para candidatura à equipe.</p>

        <form>
            <div class="form-group">
                <label>Qual seu nome?</label>
                <input type="text" placeholder="Digite seu nome">
            </div>

            <div class="form-group">
                <label>Qual sua idade?</label>
                <input type="number" placeholder="Digite sua idade">
            </div>

            <div class="form-group">
                <label>Quanto tempo joga na cidade?</label>
                <input type="text" placeholder="Ex: 6 meses">
            </div>

            <div class="form-group">
                <label>Experiência como staff</label>
                <textarea placeholder="Descreva sua experiência"></textarea>
            </div>

            <button type="submit">Enviar Entrevista</button>
        </form>
    </div>
</body>
</html>

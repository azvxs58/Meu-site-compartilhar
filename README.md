DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>@Anixx4art compartilhamento</title>

<style>
    body {
        background-color: black;
        color: blue;
        text-align: center;
        font-family: Arial;
        margin-top: 100px;
    }

    h1 {
        font-size: 28px;
    }

    p {
        color: white;
        font-size: 19px;
    }

    .aviso {
        color: red;
        font-size: 22px;
        font-weight: bold;
        margin-top: 20px;
    }

    .botao {
        background-color: #2196F3;
        color: white;
        border: none;
        padding: 15px 40px;
        font-size: 18px;
        border-radius: 15px;
        cursor: pointer;
        margin-top: 30px;
    }
</style>

<script>
function enviar() {
    document.body.innerHTML = `
        <h1 style="color:lime;">🔓COMPARTILHAMENTI ENVIADO🔓
@Anixx4art vai ter acesso as permissão </h1>

        <p style="color:white; font-size:24px; margin-top:25px;">
        Agradecemos por compartilhar dados com @Anixx4art.
        </p>

        <p style="color:gray; font-size:16px; margin-top:10px;">
        se acontecer falha no dispositivo a gente não se responsabiliza pelo dano
        </p>
    `;
}
</script>

</head>

<body>

<h1>DESEJA COMPARTILHAR DADOS COM @Anixx4art</h1>

<p>proprietário de compartilhamento @Anixx4art</p>

<p>
@Anixx4art terá acesso logins, contas, ler mensagem de e-mail, ligações, número, banco, cartão ADDS, localização do smartphone, gerenciar configurações do dispositivo

⚠️ Aviso, essas compartilhamentos de dados pessoais, pode ter roubo
de dados e danificar seu aparelho..
</p>
<p style="color:red; font-weight:bold; font-size:22px;">
⚠️ Aviso: esses compartilhamentos de dados pessoais podem causar roubo
de dados e danificar seu aparelho.
</p>

<button class="botao" onclick="enviar()">
Compartilhar
</button>

</body>
</html>

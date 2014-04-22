contactFormValidator-jQuery
===========================

Description: This is a plugin for a basic contact form validation. This package contains a page html (contato.html), a stylesheet (style.css) and a jQuery code (formValidator.js).

Descrição: Esse é um plugin criado para um formulário de contato  básico. O pacote contém uma página em html (contact.html), um estilo css (style.css) e um arquivo jQuery (formValidator.js).


===========================


Create a HTML:

<div class="formulario">
    <form id="formContato" method="post" action="" enctype="multipart/form-data">
        <div class="form-group">
            <label for="nome" class="topLabel">Nome:</label>
            <input class="inputForm" type="text" id="nome" name="nome" value=""/>
            <div class="msg-erro"></div>
        </div>

        <div class="form-group half space">
            <label for="telefone" class="topLabel">Telefone:</label>
            <input class="inputForm" type="text" id="telefone" name="telefone" value=""/>
        </div>

        <div class="form-group half">
            <label for="email" class="topLabel">E-mail:</label>
            <input class="inputForm" type="text" id="email" name="email" value=""/>
            <div class="msg-erro"></div>
        </div>

        <div class="form-group">
            <label for="assunto" class="topLabel">Assunto:</label>
            <input class="inputForm" type="text" id="assunto" name="assunto" value=""/>
            <div class="msg-erro"></div>
        </div>

        <div class="form-group">
            <label for="mensagem" class="topLabel">Mensagem:</label>
            <textarea class="areaForm" rows="3" id="mensagem" name="mensagem"></textarea>
            <div class="msg-erro"></div>
        </div>
        <div class="container-botao">
            <input type="submit" value="enviar mensagem" class="botao buttomForm"/>
        </div>
    </form>
</div>


===========================


Create a CSS:

/* Classes de formulário início */

.formulario{ width: 620px; margin: 0 auto; margin-top: 130px;}
.form-group{ width: 100%; float: left; margin-bottom: 20px;}
.half{ width: 48%;}
.space{ margin-right: 4%;}/* O space deverá ser usado juntamente com o half */
.topLabel{ width: 100%; float: left; font-family: 'Ruluko', sans-serif; color: #fff; font-size: 16px;}
.inputForm{ width: 98%; float: left; height: 30px; padding-left: 1%; padding-right: 1%; border: 0px solid #fff; border-radius: 5px; font-family: 'Ruluko', sans-serif;}
.areaForm{ width: 98%; float: left; height: 90px; padding: 5px 1% 5px 1%;  border: 0px solid #fff; border-radius: 5px; font-family: 'Ruluko', sans-serif;}
.buttomForm{ border: 0px solid #000; font-size: 18px; cursor: pointer;}

/* Classes de formulário fim */


===========================

Version: 0.1

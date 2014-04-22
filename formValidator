/* 
 * Create by Victor Frossard
 * Version: 0.1
 * Date: 22/04/2014
 * Obs: Este plugin acompanha as classes de formuário presentes no arquivo style.css e 
 * a estrutura do formulário presente no html contato..html
*/

$(function(){
    $.validateEmail = function(email) {
        er = /^[a-zA-Z0-9][a-zA-Z0-9\._-]+@([a-zA-Z0-9\._-]+\.)[a-zA-Z-0-9]{2}/;
        if (er.exec(email))
            return true;
        else
            return false;
    };

    $(".buttomForm").click(function(){

        $nome = $("#nome");
        if($nome.val() === "")
        {
            $nome.focus();  
            $nome.next(".msg-erro").html("<p style='color:red; font-size: 12px;'>O nome deve ser preenchido!</p>");
            return false;
        }

        $email = $("#email");
        if($email.val() === "")
        {
            $email.focus();  
            $email.next(".msg-erro").html("<p style='color:red; font-size: 12px;'>O e-mail deve ser preenchido!</p>");
            return false;
        }else{
            if(!$.validateEmail($email.val()))
            {
                $email.focus();  
                $email.next(".msg-erro").html("<p style='color:red; font-size: 12px;'>O e-mail digitado não é válido, preencha novamente!</p>");
                return false;
            }
        }

        $assunto = $("#assunto");
        if($assunto.val() === "")
        {
            $assunto.focus();  
            $assunto.next(".msg-erro").html("<p style='color:red; font-size: 12px;'>O assunto deve ser preenchido!</p>");
            return false;
        }

        $mensagem = $("#mensagem");
        if($mensagem.val() === "")
        {
            $mensagem.focus();  
            $mensagem.next(".msg-erro").html("<p style='color:red; font-size: 12px;'>O mensagem deve ser preenchida!</p>");
            return false;
        }

        $("#formContato").submit();
   });
});



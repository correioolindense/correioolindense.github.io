---
title: "Contate-nos"
permalink: "/contact.html"
---

<form action="https://formspree.io/f/mgegayze" method="POST">
   <p class="mb-4">Por favor, envie sua mensagem para {{site.title}}. Responderemos o mais breve possível!</p>
   <div class="form-group row">
      <div class="col-md-6">
         <input class="form-control" type="text" name="name" placeholder="Nome*" required>
      </div>
      <div class="col-md-6">
         <input class="form-control" type="email" name="_replyto" placeholder="E-mail*" required>
      </div>
   </div>
   <textarea rows="8" class="form-control mb-3" name="message" placeholder="Mensagem*" required></textarea>
   <input class="btn btn-success" type="submit" value="Enviar">
</form>
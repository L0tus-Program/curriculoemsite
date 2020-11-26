
<!DOCTYPE html>
<html lang="pt">
<head>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="logo.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo Online</title>
</head>
<body>
    <nav id='menu'>
        <input type='checkbox' id='responsive-menu' onclick='updatemenu()'><label></label>
        <ul>
          <li><a href='url aqui'>Inicio </a></li>
          <li><a href='url aqui'>Habilidades</a></li>
          <li><a href='url aqui'>Experiência</a></li>
          <li><a class='dropdown-arrow' href='url aqui'>Certificados</a>
            <ul class='sub-menus'>
              <li><a href='url aqui'>SQL</a></li>
              <li><a href='https://drive.google.com/file/d/1l3MCe7xA_MJFb7rJE1-jEALUN8WKmTpH/view?usp=sharing' target="_blank">Python</a></li>
              <li><a href='url aqui'>PHP</a></li>
              <li><a href='url aqui'>Marketing</a></li>
              <li><a href='url aqui'>Web Designer e Design Gráfico</a></li>
              <li><a href='url aqui'>HTML + CSS</a></li>
            </ul>
          </li>
          <li><a href='url aqui'>Contato</a></li>
        </ul>
      </nav>
      <h1>
        Olá , meu nome é Felipe Gomes. Fiz este pequeno site com o objetivo de apresentar um currículo de maneira um pouco diferente.
      </h1>
      <span> Tenho uma grande paixão pela tecnologia , possuo formações para trabalhar tanto no back quanto frontend.
        Sendo bem sincero , onde me colocarem eu me viro, e oque eu não souber eu dou um jeito de aprender. 
        Além da paixão pela tecnologia , também amo música , toco alguns instrumentos como guitara , violão , baixo e teclado.
        Tenho uma experiência básica com produção musical. 
    </span>
      <footer id="footer">
          <nav class="redes">
            <ul>
              <a href="mailto:felipelesgomes.1@gmail.com" id="email">
                <img src="icon/Gmail_icon-icons.com_66934.png" alt="email">
              </a>
              <a href="tel:+5551992090470" id="whats">
                <img src="icon/whatsapp_108042.png" alt="whats">
              </a>
              <a href="https://www.linkedin.com/in/felipelgomes/" target="_blank">
                <img src="icon/linkedin_icon-icons.com_65929.png" alt="linkedin">
              </a>
              <a href="https://github.com/L0tus-Program" target="_blank">
                <img src="icon/github_icon-icons.com_65450.png" alt="github">
              </a>              
              </nav>
            </ul>
          
          <span>Email : felipelesgomes.1@gmail.com | Whats : 51 992090470</span>
          <address>Cachoeirinha - RS</address>
          <small>© Pensado e desenvolvido por Felipe Gomes </small>
          
      </footer>
      <script>
        function updatemenu() {
        if (document.getElementById('responsive-menu').checked == true) {
          document.getElementById('menu').style.borderBottomRightRadius = '0';
          document.getElementById('menu').style.borderBottomLeftRadius = '0';
        }else{
          document.getElementById('menu').style.borderRadius = '34px';
        }
      }</script>
</body>
</html>

<!-- JavaScript Bundle with Popper -->
<script
  src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"
  integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa"
  crossorigin="anonymous"></script>

<!-- CSS only -->
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css"
  rel="stylesheet"
  integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx"
  crossorigin="anonymous"
/>


<body>
  <h1>Log in</h1>
  <form>
    <label for="f-email">Insert your e-mail</label><br />
    <input type="email" id="f-email" /><br />
    <label for="f-password">Insert your password</label><br />
    <input type="password" id="f-password" /><br><br>
    <button type="submit" class="btn btn-primary">Log in</button>
    <button type="submit" class="btn btn-success">Sign In</button>
  </form>
</body>
  


<style>
  h1 {
    font-size: 3em;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: bold;
    margin: 0 auto;
    width: 800px;
  }
  form{
    margin: 0 auto;
    width: 800px;
    height: auto;
  }
  body{
    background: #667db6;  /* fallback for old browsers */
background: -webkit-linear-gradient(to right, #667db6, #0082c8, #0082c8, #667db6);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to right, #667db6, #0082c8, #0082c8, #667db6); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  }
</style>

 @import url("https://fonts.googleapis.com/css?family=Poppins:100,200,300,400,500,600,700,800,900");
:root {
    --primary: #06285b;
    --light: #eee;
    --grey: #eee;
}

body {
    overflow: hidden;
    font-family: "Poppins", sans-serif;
    font-weight: 300;
    color: var(--primary);
}

a:hover {
    text-decoration: none;
}

.bg-primary {
    background-color: var(--primary) !important;
}

.bg-light {
    background-color: var(--light) !important;
}

.bg-grey {
    background-color: var(--grey) !important;
}

.bg-mix {
    background: linear-gradient(180deg, var(--light) 50%, var(--grey) 0);
}

.btn-primary {
    background-color: var(--primary);
    border: 0;
}

.btn-primary:hover {
    background-color: var(--primary);
}

#sidebar-container {
    min-height: 100vh;
}

#sidebar-container .logo {
    padding: 0.875rem 1.25rem;
}

#sidebar-container .menu {
    width: 14rem;
}

#button {
    margin-top: 30px;
    margin-bottom: 30px;
}

#content {
    overflow-y: auto;
    height: 100vh;
    padding-bottom: 5rem;
    background-color: var(--grey) !important;
}

#content2 {
    overflow-y: auto;
    height: 100vh;
    padding-bottom: 5rem;
    background-color: var(--grey) !important;
}

#dropdowntrash
{
    margin-top:10px;
}


    text-decoration: none;
}

.bg-primary { background-color: var(--primary) !important; }

.bg-light { background-color: var(--light) !important; }

.bg-grey { background-color: var(--grey) !important; }

.bg-mix { background: linear-gradient(180deg, var(--light) 50%, var(--grey) 0); }

.btn-primary {
    background-color: var(--primary);
    border: 0;
}

.btn-primary:hover {
    background-color: var(--primary);
}

#sidebar-container {
    min-height: 100vh;
}
  
#sidebar-container .logo{
    padding: 0.875rem 1.25rem;
}
  
#sidebar-container .menu {
    width: 14rem;
}

#content {
    overflow-y: auto;
    height: 100vh;
    padding-bottom: 5rem;
}

.avatar {
    max-width: 35px;
}

.btn-search {
    right: 0;
}

.stat {
    border-right: 1px solid var(--grey);
}

  
@media (max-width: 768px) {
    #sidebar-container {
      display: none;
    }
    .stat {
        border: 0;
    }
  }
  @import url('https://fonts.googleapis.com/css?family=Poppins:100,200,300,400,500,600,700,800,900');
body{
  font-family: 'Poppins', sans-serif;
  font-size: 16px;
  background: #eee;
  color:#053873;
}
.login-container{
  height: 100vh;
  width: 100%;
}
.login-form{
  margin: auto;
  width: 370px;
  padding: 15px;
  max-width: 100%;
}
.login-form .form-control{
  font-size: 15px;
  min-height: 48px;
  font-weight: 500;
}
.login-form a{
  text-decoration: none;
  color:#666;
  margin: auto;
}
.login-form a:hover{
  color:#053873;
}
.forgot-link{
  font-size: 13px;
}

.form-control:focus{
  border-color:#06285b;
  box-shadow: 0 0 0 0.2rem #06285b);
}
.btn-custom{
  background: #06285b;
  border-color:#06285b;
  color:#fff;
  font-size: 15px;
  font-weight: 600;
  min-height: 48px;
}
.btn-custom:focus,
.btn-custom:hover,
.btn-custom:active,
.btn-custom:active:focus{
  background: #06285b;
  border-color: #06285b;
  color:#fff;
}
.btn-custom:focus{
  box-shadow: 0 0 0 0.2rem rgba(114,61,190,.25);
}

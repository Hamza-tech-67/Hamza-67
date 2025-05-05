<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>تسجيل الدخول</title>
<style>
  body {
    font-family: 'Arial', sans-serif;
    background: linear-gradient(135deg, #0f9d58, #0b7e44);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  .login-container {
    background: white;
    padding: 2rem;
    border-radius: 16px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    width: 100%;
    max-width: 400px;
    text-align: center;
  }

  .login-container h2 {
    margin-bottom: 1rem;
    color: #0b7e44;
  }

  input {
    width: 100%;
    padding: 12px;
    margin: 8px 0;
    border: 1px solid #0f9d58;
    border-radius: 8px;
  }

  button {
    width: 100%;
    padding: 12px;
    background-color: #0f9d58;
    color: white;
    border: none;
    border-radius: 8px;
    margin-top: 12px;
    cursor: pointer;
    font-size: 1rem;
  }

  button:hover {
    background-color: #0b7e44;
  }

  .social-login {
    margin-top: 16px;
  }

  .social-login button {
    background-color: #000;
    color: white;
    margin-bottom: 8px;
  }

  .social-login button.google { background-color: #34a853; color: white; }
  .social-login button.facebook { background-color: #000; color: white; }

  .social-login button.google:hover { background-color: #0b7e44; }
  .social-login button.facebook:hover { background-color: #222; }

</style>
</head>
<body>

<div class="login-container">
  <h2>تسجيل الدخول</h2>

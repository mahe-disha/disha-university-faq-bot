<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>University FAQ Chatbot</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    header {
      background-color: #003366;
      color: white;
      padding: 20px 0;
    }

    main {
      padding: 30px;
    }

    .chat-info {
      font-size: 18px;
      color: #333;
      max-width: 600px;
      margin: auto;
    }

    #help-desk {
      margin: 30px auto;
      background-color: #004080;
      color: white;
      border: none;
      padding: 15px 25px;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
    }

    #help-content {
      display: none;
      margin: 20px auto;
      max-width: 600px;
      background: #ffffff;
      border: 1px solid #ccc;
      padding: 20px;
      border-radius: 6px;
      text-align: left;
    }

    footer {
      background-color: #003366;
      color: white;
      padding: 10px 0;
      position: fixed;
      bottom: 0;
      width: 100%;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h1>University FAQ Chatbot</h1>
  </header>

  <main>
    <p class="chat-info">
      Ask questions about <strong>faculty<

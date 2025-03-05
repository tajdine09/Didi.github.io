<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MauriDrive - Transport Moderne en Mauritanie</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #f5e9d4, #e0d7c3);
            color: #2d2d2d;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(90deg, #007bff, #00c4ff);
            color: white;
            padding: 40px 20px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        header::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: rgba(255, 255, 255, 0.1);
            transform: rotate(30deg);
            pointer-events: none;
        }
        header h1 {
            font-size: 2.5em;
            letter-spacing: 1px;
            animation: fadeIn 1s ease-in;
        }
        header p {
            font-size: 1.2em;
            opacity: 0.9;
        }
        .hero {
            text-align: center;
            padding: 80px 20px;
            background: #fff;
            border-bottom:​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​
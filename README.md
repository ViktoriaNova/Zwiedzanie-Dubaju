# Zwiedzanie-Dubaju
Strona prezentująca nietypowe miejsca do zwiedzenia w Dubaju z polskim przewodnikiem
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zwiedzaj Dubaj z przewodnikiem</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: url('dubai-main.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 80px 20px;
        }
        header h1 {
            font-size: 48px;
            margin: 0;
        }
        header p {
            font-size: 20px;
        }
        .cta-button {
            display: inline-block;
            background-color: #007BFF;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
            font-weight: bold;
        }
        section {
            padding: 40px 20px;
            text-align: center;
        }
        .benefits, .program, .reviews {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        .benefits div, .program div {
            margin: 10px;
            max-width: 300px;
        }
        .benefits img, .program img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <!-- Sekcja Główna -->
    <header>
        <h1>Zwiedzaj Dubaj z przewodnikiem</h1>
        <p>Odkryj nieznane atrakcje i przeżyj niezapomniane przygody!</p>
        <a href="mailto:twojemail@example.com" class="cta-button">Skontaktuj się ze mną</a>
    </header>

    <!-- Sekcja Korzyści -->
    <section>
        <h2>Dlaczego warto wybrać się ze mną?</h2>
        <div class="benefits">
            <div>
                <img src="custom-tour.jpg" alt="Indywidualne podejście">
                <p>Indywidualne podejście</p>
            </div>
            <div>
                <img src="hidden-gems.jpg" alt="Nieznane atrakcje">
                <p>Nieznane atrakcje</p>
            </div>
            <div>
                <img src="organization.jpg" alt="Pełna organizacja">
                <p>Pełna organizacja</p>
            </div>
        </div>
    </section>

    <!-- Sekcja Program -->
    <section>
        <h2>Co możemy zwiedzić?</h2>
        <div class="program">
            <div>
                <img src="old-dubai.jpg" alt="Stara dzielnica Al Fahidi">
                <p>Stara dzielnica Al Fahidi</p>
            </div>
            <div>
                <img src="hatta.jpg" alt="Hatta - Góry Hajjar">
                <p>Hatta - Góry Hajjar</p>
            </div>
            <div>
                <img src="desert.jpg" alt="Nocleg na pustyni">
                <p>Nocleg na pustyni</p>
            </div>
        </div>
    </section>

    <!-- Sekcja Opinie -->
    <section>
        <h2>Co mówią moi klienci?</h2>
        <div class="reviews">
            <p>„Najlepsza wycieczka w moim życiu! Wszystko było dopięte na ostatni guzik.” – Anna K.</p>
        </div>
    </section>

    <!-- Sekcja CTA -->
    <section>
        <h2>Gotowy na przygodę?</h2>
        <p>Napisz do mnie teraz i stwórzmy razem Twoją wymarzoną podróż!</p>
        <a href="mailto:twojemail@example.com" class="cta-button">

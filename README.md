<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AutoBozor - Avtomobil E'lonlari Sayti</title>
</head>
<body>

    <header>
        <h2>AutoBozor</h2>
        <nav>
            <a href="#">Bosh sahifa</a> | 
            <a href="#">E'lonlar</a> | 
            <a href="#">Biz haqimizda</a> | 
            <a href="#">Aloqa</a>
        </nav>
    </header>

    <hr>

    <section>
        <h3>Moshina qidirish</h3>
        <form>
            <label for="marka">Markasi:</label>
            <select id="marka">
                <option value="">Barchasi</option>
                <option value="chevrolet">Chevrolet</option>
                <option value="kia">Kia</option>
                <option value="byd">BYD</option>
            </select>

            <label for="yil">Ishlab chiqarilgan yili:</label>
            <input type="number" id="yil" placeholder="Masalan: 2020">

            <label for="narx">Maksimal narx ($):</label>
            <input type="number" id="narx" placeholder="Masalan: 15000">

            <button type="submit">Qidirish</button>
        </form>
    </section>

    <hr>

    <main>
        <h3>So'nggi e'lonlar</h3>

        <article>
            <img src="https://via.placeholder.com/250x150" alt="Chevrolet Gentra moshinasi">
            <h4>Chevrolet Gentra</h4>
            <p><b>Narxi:</b> $13,500</p>
            <p><b>Yili:</b> 2022 | <b>Bosgan masofasi:</b> 45,000 km</p>
            <p><b>Joylashuv:</b> Toshkent shahri</p>
            <button type="button">Batafsil ko'rish</button>
        </article>

        <br>

        <article>
            <img src="https://via.placeholder.com/250x150" alt="Kia K5 moshinasi">
            <h4>Kia K5</h4>
            <p><b>Narxi:</b> $24,000</p>
            <p><b>Yili:</b> 2023 | <b>Bosgan masofasi:</b> 12,000 km</p>
            <p><b>Joylashuv:</b> Samarqand shahri</p>
            <button type="button">Batafsil ko'rish</button>
        </article>
    </main>

    <hr>

    <section>
        <h3>Yangi e'lon joylashtirish</h3>
        <form>
            <label for="sarlavha">Moshina nomi:</label><br>
            <input type="text" id="sarlavha" placeholder="Masalan: Chevrolet Cobalt" required><br><br>

            <label for="moshina-narx">Narxi ($):</label><br>
            <input type="number" id="moshina-narx" placeholder="12000" required><br><br>

            <label for="tavsif">Moshina haqida qo'shimcha ma'lumot:</label><br>
            <textarea id="tavsif" rows="4" cols="40" placeholder="Kraskasi toza, xolati a'lo..."></textarea><br><br>

            <button type="submit">E'lonni e'lon qilish</button>
        </form>
    </section>

    <hr>

    <footer>
        <p>&copy; 2026 AutoBozor. Barcha huquqlar himoyalangan.</p>
    </footer>

</body>
</html>

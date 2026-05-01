<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>УК Majestic RP | Справочник FIB</title>
    <style>
        :root {
            --bg: #0b1120;
            --surface: #151e32;
            --surface-hover: #1e293b;
            --text: #e2e8f0;
            --text-muted: #94a3b8;
            --accent: #3b82f6;
            --accent-glow: rgba(59, 130, 246, 0.25);
            --gold: #f59e0b;
            --red: #ef4444;
            --green: #10b981;
            --orange: #f97316;
            --border: #2a3550;
            --radius: 12px;
        }

        * { box-sizing: border-box; margin: 0; padding: 0; }
        body {
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            background: var(--bg);
            color: var(--text);
            line-height: 1.6;
            min-height: 100vh;
        }

        header {
            background: linear-gradient(135deg, #1e3a8a 0%, #0f172a 100%);
            padding: 3rem 1rem 2rem;
            text-align: center;
            border-bottom: 3px solid var(--gold);
            box-shadow: 0 10px 30px rgba(0,0,0,0.4);
            position: relative;
            overflow: hidden;
        }
        header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(245,158,11,0.08) 0%, transparent 70%);
            pointer-events: none;
        }

        h1 {
            font-size: clamp(2rem, 5vw, 3rem);
            margin-bottom: 0.5rem;
            background: linear-gradient(to right, #fff, #cbd5e1);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 2px 15px rgba(0,0,0,0.3);
        }
        .subtitle { color: var(--text-muted); font-size: 1.1rem; margin-bottom: 2rem; }

        .search-wrap {
            max-width: 600px;
            margin: 0 auto;
            position: relative;
        }
        #search {
            width: 100%;
            padding: 1rem 1.2rem;
            border-radius: 10px;
            border: 2px solid var(--border);
            background: #0f172a;
            color: #fff;
            font-size: 1rem;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
        }
        #search:focus {
            outline: none;
            border-color: var(--accent);
            box-shadow: 0 0 0 4px var(--accent-glow);
        }
        .search-stats {
            margin-top: 0.8rem;
            font-size: 0.85rem;
            color: var(--text-muted);
        }

        main {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1.5rem 4rem;
        }

        section { margin-bottom: 3.5rem; }
        h2 {
            color: var(--gold);
            border-bottom: 2px solid var(--border);
            padding-bottom: 0.6rem;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        h2 span { font-size: 1.4rem; }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.2rem;
        }

        .card {
            background: var(--surface);
            border: 1px solid var(--border);
            border-radius: var(--radius);
            padding: 1.4rem;
            transition: transform 0.2s, box-shadow 0.2s, border-color 0.2s;
        }
        .card:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.35);
            border-color: var(--accent);
        }

        .card-header { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 0.8rem; }
        .article-id { font-weight: 700; font-size: 1.1rem; color: #fff; background: var(--accent); padding: 0.2rem 0.6rem; border-radius: 6px; }
        .article-id.admin { background: var(--orange); }
        .stars { color: var(--gold); font-size: 1.2rem; letter-spacing: 2px; }
        .title { font-size: 1.15rem; font-weight: 600; margin-bottom: 0.4rem; color: #fff; }
        .hint { color: var(--text-muted); font-style: italic; margin-bottom: 0.8rem; font-size: 0.9rem; }
        .desc { margin-bottom: 1rem; color: var(--text); white-space: pre-line; }
        
        .meta-row { display: flex; flex-wrap: wrap; gap: 0.8rem; margin-top: 0.5rem; font-size: 0.9rem; }
        .meta { padding: 0.3rem 0.7rem; border-radius: 6px; background: rgba(255,255,255,0.05); }
        .meta.bail { color: var(--green); }
        .meta.no-bail { color: var(--red); font-weight: 600; background: rgba(239,68,68,0.1); }
        .meta.punish { color: var(--gold); }
        .meta.fine { color: var(--orange); font-weight: 600; }

        .list-section { background: var(--surface); border: 1px solid var(--border); border-radius: var(--radius); padding: 1.5rem; }
        .list-section ol, .list-section ul { padding-left: 1.4rem; }
        .list-section li { margin-bottom: 0.6rem; color: var(--text); }
        .list-section strong { color: var(--accent); }

        .star-table {
            width: 100%;
            border-collapse: collapse;
            background: var(--surface);
            border-radius: var(--radius);
            overflow: hidden;
            border: 1px solid var(--border);
        }
        .star-table th, .star-table td {
            padding: 1rem;
            text-align: left;
            border-bottom: 1px solid var(--border);
        }
        .star-table th { background: #0f172a; color: var(--gold); font-weight: 600; }
        .star-table tr:hover { background: var(--surface-hover); }

        /* Miranda Card */
        .miranda-card {
            background: linear-gradient(135deg, #1e3a8a 0%, #0f172a 100%);
            border: 2px solid var(--gold);
            border-radius: var(--radius);
            padding: 2rem;
            text-align: center;
            box-shadow: 0 0 30px rgba(245, 158, 11, 0.15);
            position: relative;
            overflow: hidden;
        }
        .miranda-card::before {
            content: '⚖️';
            position: absolute;
            top: -20px;
            right: -20px;
            font-size: 8rem;
            opacity: 0.08;
            pointer-events: none;
        }
        .miranda-title {
            color: var(--gold);
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
        }
        .miranda-text {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #fff;
            background: rgba(255,255,255,0.05);
            padding: 1.2rem;
            border-radius: 8px;
            border-left: 3px solid var(--accent);
        }

        /* Promotion System */
        .promo-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.2rem;
        }
        .promo-card {
            background: var(--surface);
            border: 1px solid var(--border);
            border-radius: var(--radius);
            padding: 1.5rem;
            border-top: 4px solid var(--accent);
        }
        .promo-card h4 {
            color: var(--gold);
            font-size: 1.2rem;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        .promo-card ol {
            padding-left: 1.3rem;
            color: var(--text);
        }
        .promo-card li {
            margin-bottom: 0.7rem;
            line-height: 1.5;
        }
        .promo-card a {
            color: var(--accent);
            text-decoration: none;
            transition: color 0.2s;
        }
        .promo-card a:hover {
            color: var(--gold);
            text-decoration: underline;
        }
        .promo-note {
            font-size: 0.85rem;
            color: var(--text-muted);
            font-style: italic;
            margin-top: 0.5rem;
        }

        /* Admin Section Badge */
        .section-badge {
            display: inline-block;
            background: var(--orange);
            color: #fff;
            padding: 0.2rem 0.6rem;
            border-radius: 4px;
            font-size: 0.8rem;
            font-weight: 600;
            margin-left: 0.5rem;
        }

        .hidden { display: none !important; }
        .highlight { background: rgba(245, 158, 11, 0.25); border-radius: 4px; padding: 0 3px; color: #fff; }

        footer {
            text-align: center;
            padding: 2rem;
            color: var(--text-muted);
            border-top: 1px solid var(--border);
            font-size: 0.9rem;
            margin-top: 2rem;
        }

        @media (max-width: 768px) {
            header { padding: 2rem 1rem 1.5rem; }
            .grid, .promo-grid { grid-template-columns: 1fr; }
            .card, .miranda-card { padding: 1.2rem; }
        }
    </style>
</head>
<body>

<header>
    <h1>📜 Уголовный Кодекс Majestic RP</h1>
    <p class="subtitle">Официальный справочник FIB | Быстрый поиск, статьи, процедуры</p>
    <div class="search-wrap">
        <input type="text" id="search" placeholder="🔍 Поиск по статье, нарушению, залогу или времени...">
        <div class="search-stats" id="search-stats">Найдено: <span id="match-count">все</span> записей</div>
    </div>
</header>

<main>
    <!-- Звёзды и время -->
    <section id="star-time" class="searchable">
        <h2><span>⭐</span> Соответствие звёзд и времени задержания</h2>
        <table class="star-table">
            <thead><tr><th>Звёзды</th><th>Время</th></tr></thead>
            <tbody>
                <tr><td><span class="stars">1 ★</span></td><td>10 минут</td></tr>
                <tr><td><span class="stars">2 ★</span></td><td>20 минут</td></tr>
                <tr><td><span class="stars">3 ★</span></td><td>30 минут</td></tr>
                <tr><td><span class="stars">4 ★</span></td><td>40 минут</td></tr>
                <tr><td><span class="stars">5 ★</span></td><td>50 минут</td></tr>
            </tbody>
        </table>
    </section>

    <!-- Миранда -->
    <section id="miranda" class="searchable">
        <h2><span>🗣️</span> Текст Миранды</h2>
        <div class="miranda-card">
            <div class="miranda-title">⚖️ Права задержанного</div>
            <div class="miranda-text">
                Вы имеете право хранить молчание. Всё, что Вы скажете, может быть и будет использовано против вас. 
                Вы имеете право на адвоката и на конфиденциальную беседу с ним, также на телефонный звонок. 
                Вам ясны Ваши права?
            </div>
        </div>
    </section>

    <!-- Система повышения -->
    <section id="promotion" class="searchable">
        <h2><span>📈</span> Система повышения</h2>
        <div class="promo-grid">
            <div class="promo-card">
                <h4>🔹 С 1 → 2 ранг</h4>
                <ol>
                    <li>Получить удостоверение в Мэрии у NPC</li>
                    <li>Вступить и получить роль в <a href="https://discord.gg/statemajestic" target="_blank">State Fraction</a></li>
                    <li>Пройти экзамен по: <strong>УК и ПК</strong></li>
                    <li>Заполнить <a href="https://discord.com/channels/1119257099545870457/1419717951044714496" target="_blank">форму заявки</a></li>
                </ol>
                <div class="promo-note">💡 После выполнения всех пунктов — ожидайте проверку руководством</div>
            </div>
            <div class="promo-card">
                <h4>🔹 С 2 → 3 ранг</h4>
                <ol>
                    <li>Пройти экзамен по <strong>задержанию</strong></li>
                    <li>Принять участие в <strong>одном фракционном мероприятии</strong></li>
                </ol>
                <div class="promo-note">🎯 Активность и знание процедур — ключ к повышению</div>
            </div>
        </div>
    </section>

    <!-- Административные нарушения -->
    <section id="admin-offenses" class="searchable">
        <h2><span>📋</span> Административные нарушения <span class="section-badge">Админ. Кодекс</span></h2>
        <div class="grid">
            <div class="card admin-card" data-search="2.1 мелкое хулиганство маты общественное место штраф 5000 20000 административный кодекс нарушение общественного порядка неуважение обществу">
                <div class="card-header">
                    <span class="article-id admin">Адм. ст. 2.1</span>
                </div>
                <div class="title">Мелкое хулиганство</div>
                <div class="hint">(МАТЫ В ОБЩЕСТВЕННОМ МЕСТЕ)</div>
                <div class="desc">Нарушение общественного порядка, выражающее явное неуважение к обществу. Квалифицируется как мелкое хулиганство при использовании нецензурной брани в общественных местах.</div>
                <div class="meta-row">
                    <span class="meta fine">💰 Штраф: 5.000$ — 20.000$</span>
                    <span class="meta punish">⚠️ Без задержания</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Процедурные блоки -->
    <section id="procedures" class="searchable">
        <h2><span>📋</span> Процедурные правила</h2>
        <div class="grid">
            <div class="list-section card">
                <div class="title">Процесс задержания гражданского</div>
                <ol>
                    <li>Наручники</li>
                    <li>Представиться</li>
                    <li>Статьи (если надо объясните)</li>
                    <li>Досмотр документов</li>
                    <li>Первичка (без изъятия)</li>
                    <li>Маска + фоторобот</li>
                    <li>Посадить в машину + миранда</li>
                    <li>Доставить в кпз PD/SD/FIB</li>
                    <li>Реализация прав</li>
                    <li>Допрос, если требуется</li>
                </ol>
            </div>
            <div class="list-section card">
                <div class="title">Установление личности</div>
                <ol>
                    <li>Надеть наручники на задержанного</li>
                    <li>Разъяснить причину установления личности</li>
                    <li>Предпринять все меры установления личности</li>
                    <li>Сверить лицо с фотороботом</li>
                    <li>Провести личный обыск задержанного</li>
                </ol>
            </div>
            <div class="list-section card">
                <div class="title">Основания для освобождения</div>
                <ol>
                    <li>За инкриминируемое нарушение не предусмотрена мера пресечения в виде заключения под стражу</li>
                    <li>Отсутствуют достаточные доказательства совершения преступления</li>
                    <li>В ходе расследования прокурор не подтвердил факт совершения преступления или правонарушения</li>
                    <li>Задержанному не были своевременно и в полном объёме разъяснены его права</li>
                </ol>
            </div>
            <div class="list-section card">
                <div class="title">Основания для задержания</div>
                <ol>
                    <li>Лицо застигнуто в момент совершения правонарушения или непосредственно после</li>
                    <li>На лице/одежде/в жилище обнаружены явные следы правонарушения</li>
                    <li>Имеется фото- или видеозапись, фиксирующая правонарушение</li>
                    <li>Имеется действующий ордер на задержание</li>
                    <li>Мотивированное требование Генпрокурора или заместителя</li>
                    <li>Действующая ориентировка на лицо или ТС</li>
                    <li>Лицо объявлено в розыск</li>
                </ol>
            </div>
            <div class="list-section card" style="grid-column: 1 / -1; border-left: 3px solid var(--red);">
                <div class="title" style="color: var(--red);">⚠️ Не стоит забывать</div>
                <ul>
                    <li>Всегда проверяйте удостоверение</li>
                    <li>Проверяйте, включён ли откат</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Уголовные статьи -->
    <section id="articles" class="searchable">
        <h2><span>⚖️</span> Уголовные статьи <span class="section-badge">УК РФ</span></h2>
        <div class="grid" id="articles-grid"></div>
    </section>
</main>

<footer>
    <p>© 2026 Majestic RolePlay | Справочник FIB. Все права защищены.</p>
    <p style="margin-top: 0.5rem; font-size: 0.8rem;">Используйте поиск для быстрого нахождения нужной статьи или процедуры.</p>
</footer>

<script>
    // Данные уголовных статей
    const articles = [
        { id: "4.1", title: "Общие положения", desc: "Лицу, признанному виновным в совершении преступления или правонарушения, назначается справедливое наказание в пределах, предусмотренных соответствующей статьей настоящего Кодекса.", stars: 0, bail: "-", punish: "-" },
        { id: "6.1", title: "Нанесение телесных повреждений", desc: "Умышленное и/или неоднократное нанесение телесных повреждений легкой или средней степени тяжести.", hint: "(ЕСЛИ ЧЕЛОВЕК ДЕРЕТСЯ С ДРУГИМ)", stars: 3, bail: "75.000$", punish: "До 30 минут" },
        { id: "6.2", title: "Убийство", desc: "Умышленное причинение смерти другому человеку и/или нанесения телесных повреждений тяжелой степени.", hint: "(УБИЙСТВО)", stars: 4, bail: "100.000$", punish: "До 40 минут" },
        { id: "6.8", title: "Нарушение ПДД с тяжким вредом/смертью", desc: "Нарушение правил дорожного движения, повлекшее за собой причинение потерпевшим тяжкого вреда здоровью и(или) наступила их смерть.", hint: "(СБИЛ НА МАШИНЕ)", stars: 3, bail: "75.000$", punish: "До 30 минут" },
        { id: "7.1", title: "Похищение человека", desc: "", hint: "", stars: 5, bail: "Запрещён", punish: "До 50 минут" },
        { id: "10.1", title: "Кража", desc: "Тайное хищение чужого имущества.", hint: "(УГОНКА)", stars: 3, bail: "75.000$", punish: "До 30 минут" },
        { id: "10.3.1", title: "Незаконное проникновение в жилой дом", desc: "Часть 1: Кража/грабеж со взломом без насилия.\nЧасть 2: Грабеж дома с применением насилия или угрозой.", hint: "(ОГРАБЛЕНИЕ БЕЗ СТРЕЛЬБЫ / С СТРЕЛЬБОЙ)", stars: 3, bail: "75.000$ / 100.000$", punish: "До 30 / 40 минут" },
        { id: "10.5", title: "Вымогательство", desc: "Требование передачи чужого имущества или права на имущество под угрозой применения насилия либо уничтожения/повреждения имущества.", hint: "(ТРЕБУЮТ ОТДАТЬ МАШИНУ)", stars: 3, bail: "75.000$", punish: "До 30 минут" },
        { id: "10.6", title: "Уничтожение чужого имущества", desc: "Умышленные уничтожение или повреждение чужого имущества.", hint: "(СТРЕЛЬБА ПО МАШИНЕ)", stars: 2, bail: "50.000$", punish: "До 20 минут" },
        { id: "10.6.1", title: "Уничтожение гос. имущества", desc: "Умышленные уничтожение или повреждение государственного имущества.", hint: "(СТРЕЛЬБА ПО ГОС МАШИНЕ)", stars: 3, bail: "75.000$", punish: "До 30 месяцев лишения свободы" },
        { id: "12.7.1", title: "Незаконное проникновение на закрытую территорию", desc: "В соответствии с нормативно-правовой базой штата Сан-Андреас.", hint: "(РЕСПА FIB и не только)", stars: 4, bail: "100.000$", punish: "До 40 минут" },
        { id: "12.8", title: "Незаконное хранение оружия", desc: "Приобретение, передача, сбыт, хранение, перевозка, ношение или использование любых видов оружия, бронежилетов и боеприпасов.", hint: "(НЕЗАКОННОЕ ХРАНЕНИЕ ОРУЖИЯ)", stars: 4, bail: "100.000$", punish: "До 40 минут" },
        { id: "12.8.1", title: "Незаконное хранение гос. средств", desc: "Приобретение, передача, сбыт, хранение, перевозка, ношение или использование гос. спецсредств, дефибрилляторов, эпинефрина.", hint: "(НЕЗАКОННОЕ ХРАНЕНИЕ ГОС ОРУЖИЯ, дефибрилляторов, эпинефрина)", stars: 4, bail: "100.000$", punish: "До 40 минут" },
        { id: "12.9", title: "Незаконное хранение взрывчатки", desc: "Приобретение, передача, сбыт, хранение, перевозка, изготовление или ношение взрывчатых веществ или взрывных устройств.", hint: "(НЕЗАКОННОЕ ХРАНЕНИЕ ГРАНАТ)", stars: 5, bail: "Запрещён", punish: "До 50 минут" },
        { id: "13.3", title: "Выращивание наркотиков", desc: "Незаконное выращивание наркотических веществ, независимо от их количества.", hint: "(ВЫРАЩИВАТЬ НАРКОТИКИ)", stars: 4, bail: "100.000$", punish: "До 40 минут" },
        { id: "13.5", title: "Наркотики до 25 грамм", desc: "Незаконный сбыт, пересылка и производство наркотических средств, совершенные в размере до 25 грамм включительно.", hint: "(НАРКОТИКИ до 25 грамм)", stars: 4, bail: "100.000$", punish: "До 40 минут" },
        { id: "13.6", title: "Наркотики от 25 грамм", desc: "Незаконный сбыт, пересылка и производство наркотических средств, совершенные в размере от 25 грамм не включительно и выше.", hint: "(НАРКОТИКИ от 25 грамм)", stars: 5, bail: "125.000$", punish: "До 50 минут" },
        { id: "17.1", title: "Посягательство на жизнь сотрудника", desc: "На жизнь сотрудника правоохранительного органа, военнослужащего, а равно их близких в связи с исполнением обязанностей либо из мести.", hint: "(СТРЕЛЬБА ПО ГОС)", stars: 5, bail: "Запрещён", punish: "До 50 минут" },
        { id: "17.2", title: "Угроза представителю власти", desc: "Применение насилия, не опасного для жизни или здоровья, либо угроза применения насилия в отношении представителя власти или его близких.", hint: "(УГРОЗА ГОС)", stars: 3, bail: "75.000$", punish: "До 30 минут" },
        { id: "17.3", title: "Оскорбление сотрудника гос. организации", desc: "При исполнении им своих служебных обязанностей.", hint: "(ОСКОРБЛЕНИЕ ГОС)", stars: 1, bail: "25.000$", punish: "До 10 минут" },
        { id: "17.4", title: "Подделка документов/лицензий", desc: "Использование не зарегистрированной лицензии и(или) подделка удостоверения или иного официального документа, предоставляющего права.", hint: "(ФЕЙК ЛИЦЕНЗИЯ, ДОКУМЕНТЫ)", stars: 3, bail: "75.000$", punish: "До 30 минут" },
        { id: "17.6", title: "Неподчинение законным требованиям", desc: "Неподчинение законным требованиям сотрудника силовых, охранно-силовых, военных структур а также прокуратуры, равно как злонамеренное игнорирование.", hint: "(НЕПОДЧИНЕНИЕ)", stars: 3, bail: "75.000$", punish: "До 30 минут" },
        { id: "17.7", title: "Отказ от оплаты штрафа", desc: "Отказ от оплаты штрафа выписанного правомочным лицом, а равно отказ от возмещения ущерба согласно законодательству.", hint: "(ОТКАЗ ОТ ОПЛАТЫ ШТРАФА)", stars: 3, bail: "75.000$", punish: "До 30 минут" },
        { id: "17.9", title: "Помеха задержанию", desc: "Незаконная помеха при задержании нарушителя, равно как содействие повлекшее за собой упущение задержанного/преследуемого/арестованного.", hint: "(ПОМЕХА ЗАДЕРЖАНИЮ)", stars: 3, bail: "75.000$", punish: "До 20 месяцев лишения свободы" },
        { id: "17.11", title: "Побег при задержании", desc: "", hint: "(ПОБЕГ)", stars: 3, bail: "75.000$", punish: "До 30 месяцев лишения свободы" }
    ];

    // Рендер уголовных статей
    const grid = document.getElementById('articles-grid');
    const starHTML = (n) => n === 0 ? '' : `<span class="stars">${'★'.repeat(n)}</span>`;
    const bailClass = (b) => b.toLowerCase().includes('запрещён') ? 'meta no-bail' : 'meta bail';

    articles.forEach(a => {
        const card = document.createElement('div');
        card.className = 'card article-card';
        card.setAttribute('data-search', `${a.id} ${a.title} ${a.desc} ${a.hint} ${a.bail} ${a.punish}`.toLowerCase());
        card.innerHTML = `
            <div class="card-header">
                <span class="article-id">Ст. ${a.id}</span>
                ${starHTML(a.stars)}
            </div>
            <div class="title">${a.title}</div>
            ${a.hint ? `<div class="hint">${a.hint}</div>` : ''}
            ${a.desc ? `<div class="desc">${a.desc}</div>` : ''}
            <div class="meta-row">
                <span class="${bailClass(a.bail)}">💰 Залог: ${a.bail}</span>
                <span class="meta punish">⏱️ ${a.punish}</span>
            </div>
        `;
        grid.appendChild(card);
    });

    // Поиск по всем секциям
    const searchInput = document.getElementById('search');
    const matchCount = document.getElementById('match-count');
    const allItems = document.querySelectorAll('.card, .list-section, .miranda-card, .promo-card, .admin-card');
    const totalItems = allItems.length;

    searchInput.addEventListener('input', (e) => {
        const query = e.target.value.toLowerCase().trim();
        let matches = 0;

        allItems.forEach(item => {
            // Получаем текст для поиска из data-search или innerText
            const searchText = item.getAttribute('data-search') || item.innerText.toLowerCase();
            const itemText = searchText.toLowerCase();
            
            if (query === '' || itemText.includes(query)) {
                item.classList.remove('hidden');
                matches++;
            } else {
                item.classList.add('hidden');
            }
        });

        matchCount.textContent = query === '' ? `все (${totalItems})` : matches;
    });
</script>

</body>
</html>

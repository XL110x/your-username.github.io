<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>鈴木晴奈 - ファッションデザイナー</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: #e6f2e6;
            color: #333;
        }
        header {
            background: #2e8b57;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #3cb371;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 1rem;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section {
            margin-bottom: 2rem;
        }
        h1, h2 {
            color: #2e8b57;
        }
        .awards {
            background: #f5f5f5;
            padding: 1rem;
            border-radius: 8px;
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin-bottom: 2rem;
        }
        footer {
            background: #2e8b57;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 10px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <header>
        <h1>鈴木晴奈 - ファッションデザイナー</h1>
    </header>
    <nav>
        <a href="#about">私について</a>
        <a href="#awards">受賞歴</a>
        <a href="#gallery">ギャラリー</a>
        <a href="#contact">連絡先</a>
    </nav>
    <main>
        <img src="file:///C:/Users/Administrator/Desktop/服装设计/铃木晴奈.jpg" alt="鈴木晴奈">
        <section id="about" class="section">
            <h2>私について</h2>
            <p>鈴木晴奈は、ファッション業界で才能を発揮しているデザイナーです。彼女のデザインは繊細な美しさと革新的な創造力を融合し、世界中のファッション愛好家から注目を集めています。</p>
            <p>彼女は東京とシドニーで学び、異なる文化と美学のエッセンスを吸収し、独自のスタイルを築き上げました。伝統的な技術と現代の要素を巧みに組み合わせて、時代を超えたエレガンスを表現しています。</p>
            <p>デザインは、細部へのこだわりと高品質な材料の選択が特徴です。さらに、環境に優しい持続可能なファッションを提倡し、エコフレンドリーな材料を積極的に使用しています。</p>
            <p>彼女のブランドは多くのファッションショーと展示会で高い評価を受け、国際的にも広く認知されています。情熱と献身で新しいファッションの波を作り出し、ファッションの未来をリードしています。</p>
        </section>
        <section id="awards" class="section">
            <h2>受賞歴</h2>
            <div class="awards">
                <ul>
                    <li>2021年「ゴールデンタイム・ベストドレスデザイナー賞」受賞</li>
                    <li>2022年「高級ファッションデザイナー大賞」チャンピオン</li>
                    <li>その他、多数の日本映画の衣装デザインにも関与</li>
                </ul>
            </div>
        </section>
        <section id="gallery" class="section gallery">
            <h2>ギャラリー</h2>
            <img src="file:///C:/Users/Administrator/Desktop/服装设计/服装设计1.jpg" alt="服装设计1">
            <img src="file:///C:/Users/Administrator/Desktop/服装设计/服装设计2.jpg" alt="服装设计2">
            <img src="file:///C:/Users/Administrator/Desktop/服装设计/服装设计4.jpg" alt="服装设计4">
            <img src="file:///C:/Users/Administrator/Desktop/服装设计/服装设计6.jpg" alt="服装设计6">
            <img src="file:///C:/Users/Administrator/Desktop/服装设计/服装设计7.jpg" alt="服装设计7">
        </section>
        <section id="contact" class="section">
            <h2>連絡先</h2>
            <p>作品に興味がある方やご質問がある方は、以下の連絡先からお気軽にご連絡ください。</p>
            <p>Email: Haruna87813@gmail.com</p>
        </section>
    </main>
    <footer>
        &copy; 2024 鈴木晴奈. すべての権利を保持.
    </footer>
</body>
</html>

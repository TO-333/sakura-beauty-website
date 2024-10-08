<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>桜ビューティーサロン</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Serif+JP:wght@400;700&display=swap');
        body {
            font-family: 'Noto Serif JP', serif;
            background-color: #FFF5EE;
        }
        .sakura {
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='120' height='120' viewBox='0 0 120 120'%3E%3Cpath d='M60 20c-3 0-5 2-5 5s2 5 5 5 5-2 5-5-2-5-5-5zm-20 20c-3 0-5 2-5 5s2 5 5 5 5-2 5-5-2-5-5-5zm40 0c-3 0-5 2-5 5s2 5 5 5 5-2 5-5-2-5-5-5zM60 60c-3 0-5 2-5 5s2 5 5 5 5-2 5-5-2-5-5-5zm-20 20c-3 0-5 2-5 5s2 5 5 5 5-2 5-5-2-5-5-5zm40 0c-3 0-5 2-5 5s2 5 5 5 5-2 5-5-2-5-5-5z' fill='%23FFB7C5' fill-opacity='0.2'/%3E%3C/svg%3E");
        }
    </style>
</head>
<body class="sakura">
    <header class="bg-white bg-opacity-80 shadow-md">
        <nav class="container mx-auto px-6 py-3">
            <div class="flex justify-between items-center">
                <a href="#" class="text-2xl font-bold text-pink-600">桜ビューティー</a>
                <div class="hidden md:flex items-center space-x-4">
                    <a href="#services" class="text-gray-800 hover:text-pink-600">サービス</a>
                    <a href="#staff" class="text-gray-800 hover:text-pink-600">スタッフ</a>
　　　　　　　　　　<a href="#about" class="text-gray-800 hover:text-pink-600">当店について</a>
                    <a href="#feedback" class="text-gray-800 hover:text-pink-600">お客様の声</a>
                    <a href="#agenda" class="text-gray-800 hover:text-pink-600">年間予定</a>
                    <a href="#contacts" class="text-gray-800 hover:text-pink-600">連絡先</a>
                    <a href="#contact" class="text-gray-800 hover:text-pink-600">お問い合わせ</a>
                </div>
            </div>
        </nav>
    </header>

    <main class="container mx-auto px-6 py-8">
        <section id="hero" class="text-center py-20">
            <h1 class="text-4xl md:text-6xl font-bold text-gray-800 mb-4">真の日本の美を体験</h1>
            <p class="text-xl text-gray-600 mb-8">リラクゼーションと若返りの芸術を堪能</p>
            <a href="#contact" class="bg-pink-600 text-white px-6 py-3 rounded-full hover:bg-pink-700 transition duration-300">予約する</a>
        </section>


        <img src="andrea-donato-lJFLGirYwV0-unsplash.jpg">

        <section id="services" class="py-16">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">サービス内容</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-4">指圧マッサージ</h3>
                    <p class="text-gray-600">伝統的な日本のツボ療法の癒しの力を体験</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-4">フェイシャルトリートメント</h3>
                    <p class="text-gray-600">当店独自の日本発想のフェイシャルトリートメントでアンチエイジング</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-4">温泉風呂</h3>
                    <p class="text-gray-600">本格的な温泉体験で心身ともにリラックス</p>
                </div>
            </div>
        </section>

        <section id="staff" class="py-16 bg-white bg-opacity-80 rounded-lg shadow-md">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">スタッフ紹介</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="text-center">
                    <img src="/api/placeholder/150/150" alt="佐藤 美香" class="rounded-full mx-auto mb-4">
                    <h3 class="text-xl font-semibold mb-2">佐藤 美香</h3>
                    <p class="text-gray-600">指圧マッサージ専門</p>
                </div>
                <div class="text-center">
                    <img src="/api/placeholder/150/150" alt="田中 健太" class="rounded-full mx-auto mb-4">
                    <h3 class="text-xl font-semibold mb-2">田中 健太</h3>
                    <p class="text-gray-600">フェイシャルトリートメント担当</p>
                </div>
                <div class="text-center">
                    <img src="/api/placeholder/150/150" alt="鈴木 さくら" class="rounded-full mx-auto mb-4">
                    <h3 class="text-xl font-semibold mb-2">鈴木 さくら</h3>
                    <p class="text-gray-600">美容セラピスト</p>
                </div>
            </div>
        </section>

        <section id="feedback" class="py-16">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">お客様の声</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <p class="text-gray-600 mb-4">「スタッフの皆さんの丁寧な対応と、心地よい施術に大変満足しています。毎回訪れるのが楽しみです。」</p>
                    <p class="font-semibold">- 岡下 Hさん</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <p class="text-gray-600 mb-4">「フェイシャルトリートメントを受けた後は、肌がワントーン明るくなったように感じ、すごく効果を実感しています。」</p>
                    <p class="font-semibold">- 下谷 Gさん</p>
                </div>
            </div>
        </section>

        <section id="about" class="py-16 bg-white bg-opacity-80 rounded-lg shadow-md">
            <div class="max-w-3xl mx-auto text-center">
                <h2 class="text-3xl font-bold text-gray-800 mb-6">桜ビューティーについて</h2>
                <p class="text-gray-600 mb-4">桜ビューティーでは、日本のスキンケアとリラクゼーション技術の真髄をお届けします。熟練のセラピストが伝統的な手法を用いて、本物の癒しと若返りの体験をご提供いたします。</p>
                <p class="text-gray-600">当サロンで「おもてなし」の心をこめたサービスをお楽しみください。</p>
            </div>
        </section>



        <section id="agenda" class="py-16">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">年間予定</h2>
            <div class="max-w-3xl mx-auto bg-white p-8 rounded-lg shadow-md">
                <div class="mb-8">
                    <h3 class="text-xl font-semibold mb-4">春 (3月 - 5月)</h3>
                    <ul class="list-disc list-inside text-gray-600">
                        <li>桜の季節限定フェイシャルトリートメント</li>
                        <li>ゴールデンウィーク特別パッケージ</li>
                    </ul>
                </div>
                <div class="mb-8">
                    <h3 class="text-xl font-semibold mb-4">夏 (6月 - 8月)</h3>
                    <ul class="list-disc list-inside text-gray-600">
                        <li>夏の疲れ癒しマッサージキャンペーン</li>
                        <li>日焼けケア特別コース</li>
                    </ul>
                </div>
                <div class="mb-8">
                    <h3 class="text-xl font-semibold mb-4">秋 (9月 - 11月)</h3>
                    <ul class="list-disc list-inside text-gray-600">
                        <li>紅葉をイメージした香りのアロマトリートメント</li>
                        <li>乾燥対策スペシャルケア</li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-semibold mb-4">冬 (12月 - 2月)</h3>
                    <ul class="list-disc list-inside text-gray-600">
                        <li>年末年始リフレッシュコース</li>
                        <li>バレンタイン限定カップルプラン</li>
                    </ul>
                </div>
            </div>

                        <section id="contact" class="py-16">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">お問い合わせ</h2>
            <form class="max-w-lg mx-auto bg-white p-8 rounded-lg shadow-md">
                <div class="mb-4">
                    <label for="name" class="block text-gray-700 font-bold mb-2">お名前</label>
                    <input type="text" id="name" name="name" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-pink-600" required>
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-gray-700 font-bold mb-2">メールアドレス</label>
                    <input type="email" id="email" name="email" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-pink-600" required>
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-gray-700 font-bold mb-2">メッセージ</label>
                    <textarea id="message" name="message" rows="4" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-pink-600" required></textarea>
                </div>
                <button type="submit" class="w-full bg-pink-600 text-white px-4 py-2 rounded-md hover:bg-pink-700 transition duration-300">送信する</button>
            </form>
        </section>


        <section id="contacts" class="py-16 bg-white bg-opacity-80 rounded-lg shadow-md">

            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">連絡先・アクセス</h2>
            <div class="max-w-2xl mx-auto">
                <div class="mb-8">
                    <h3 class="text-xl font-semibold mb-4">住所</h3>
                    <p class="text-gray-600">〒100-0001 東京都千代田区千代田1-1-1 桜ビル3階</p>
                </div>
                <div class="mb-8">
                    <h3 class="text-xl font-semibold mb-4">電話番号</h3>
                    <p class="text-gray-600">03-1234-5678</p>
                </div>
                <div class="mb-8">
                    <h3 class="text-xl font-semibold mb-4">メールアドレス</h3>
                    <p class="text-gray-600">info@sakura-beauty.jp</p>
                </div>
                <div>
                    <h3 class="text-xl font-semibold mb-4">営業時間</h3>
                    <p class="text-gray-600">平日・土曜日: 10:00 - 20:00</p>
                    <p class="text-gray-600">日曜日・祝日: 10:00 - 18:00</p>
                </div>
            </div>
        </section>

<footer>
    <p>&copy; 2024 SakuraBeautyInc. All Rights Reserved.</p>
</footer>

            
            
</body> 
</html>

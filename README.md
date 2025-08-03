<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Shokoのハリウッド式ボイストレーニング</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Noto+Sans+JP:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* カスタムスタイル */
        body {
            font-family: 'Noto Sans JP', 'Inter', sans-serif;
            background-color: #F8F7F5; /* 落ち着いた背景色 */
            color: #333;
        }
        .hero-bg {
            /* 背景画像 */
            background-image: url('https://i.imgur.com/I1hsSKA.jpeg');
            background-size: cover;
            background-position: center; /* 中央に配置 */
        }
        .section-title {
            font-size: 1.8rem;
            font-weight: 700;
            text-align: center;
            margin-bottom: 2rem;
            color: #1E40AF; /* ダークブルー */
            border-bottom: 2px solid #2563EB; /* ブルー */
            padding-bottom: 0.5rem;
            display: inline-block;
        }
        .card {
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
            padding: 2rem;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
        }
        .icon-check {
            width: 1.5rem;
            height: 1.5rem;
            color: #2563EB; /* ブルー */
            margin-right: 0.75rem;
            flex-shrink: 0;
        }
        .cta-button {
            display: inline-block;
            padding: 1rem 2.5rem;
            background: linear-gradient(135deg, #2563EB, #1E40AF); /* ブルーのグラデーション */
            color: white;
            font-weight: 700;
            border-radius: 50px;
            text-align: center;
            text-decoration: none;
            transition: transform 0.3s, box-shadow 0.3s;
            box-shadow: 0 4px 15px rgba(37, 99, 235, 0.4);
        }
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(37, 99, 235, 0.5);
        }
    </style>
</head>
<body>

    <!-- ヘッダー -->
    <header class="bg-white/80 backdrop-blur-md sticky top-0 z-50 shadow-sm">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-xl font-bold text-gray-800">Shoko's Voice Training</h1>
            <a href="#apply" class="cta-button text-sm px-6 py-2">お申込み</a>
        </div>
    </header>

    <!-- ヒーローセクション -->
    <section class="hero-bg text-white relative">
        <div class="absolute inset-0 bg-black/40"></div>
        <div class="container mx-auto px-6 py-24 md:py-32 text-center relative z-10">
            <h2 class="text-3xl md:text-5xl font-bold leading-tight mb-4 shadow-text">Shokoのハリウッド式ボイストレーニング</h2>
            <p class="text-lg md:text-2xl mb-8 shadow-text">〜声に悩むあなたへ。理想の声に近づく50分〜</p>
            <p class="text-base md:text-xl bg-black/30 rounded-lg p-4 inline-block">“この声が出ない”から、“こんな声も出るんだ！”という感動を</p>
        </div>
    </section>

    <!-- メインコンテンツ -->
    <main class="container mx-auto px-6 py-16">

        <!-- どんなレッスン？ -->
        <section id="about" class="text-center mb-16">
            <h2 class="section-title">どんなレッスン？</h2>
            <div class="card max-w-3xl mx-auto text-left">
                <p class="mb-4 text-gray-700 leading-relaxed">
                    「お腹から声を出して！」「もっと頭に響かせて！」といった感覚頼りの指導ではありません。<br>
                    声帯・筋肉・骨格の構造や理論に基づく<strong>【ハリウッド式ボイストレーニング】</strong>で、あなたの声質（ボイスタイプ）に合った最適なトレーニングを提案します。
                </p>
                <div class="mt-6 p-4 bg-blue-50 rounded-lg border-l-4 border-blue-500">
                    <h3 class="font-bold text-blue-800 mb-2">こんな方にオススメ！</h3>
                    <ul class="space-y-2 text-gray-700">
                        <li class="flex items-center"><svg class="icon-check" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>発声に悩んでいる</li>
                        <li class="flex items-center"><svg class="icon-check" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>歌声や話し声を改善したい</li>
                        <li class="flex items-center"><svg class="icon-check" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>自分に合ったボイトレを探している</li>
                        <li class="flex items-center"><svg class="icon-check" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>自分の声にもっと自信を持ちたい</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- レッスン内容 -->
        <section id="lesson-content" class="text-center mb-16">
            <h2 class="section-title">レッスン内容 (50分)</h2>
            <div class="max-w-3xl mx-auto space-y-6">
                <div class="card text-left flex flex-col sm:flex-row items-start gap-6">
                    <div class="bg-blue-600 text-white rounded-full w-16 h-16 flex-shrink-0 flex items-center justify-center text-2xl font-bold">1</div>
                    <div>
                        <h3 class="font-bold text-xl mb-2 text-blue-800">なりたい声のヒアリング</h3>
                        <p class="text-gray-700">まずはあなたの「声に関するお悩み」「理想の声」や「歌いたい曲」などを丁寧にヒアリング。目標を共有し、レッスンのゴールを一緒に決めていきます。</p>
                    </div>
                </div>
                <div class="card text-left flex flex-col sm:flex-row items-start gap-6">
                    <div class="bg-blue-600 text-white rounded-full w-16 h-16 flex-shrink-0 flex items-center justify-center text-2xl font-bold">2</div>
                    <div>
                        <h3 class="font-bold text-xl mb-2 text-blue-800">ボイスタイプ診断</h3>
                        <p class="text-gray-700">あなたの現在の発声をチェックし、声のタイプを診断します。自分の声の癖や強み・弱みを客観的に知ることで、トレーニングの方向性が明確になります。</p>
                    </div>
                </div>
                <div class="card text-left flex flex-col sm:flex-row items-start gap-6">
                    <div class="bg-blue-600 text-white rounded-full w-16 h-16 flex-shrink-0 flex items-center justify-center text-2xl font-bold">3</div>
                    <div>
                        <h3 class="font-bold text-xl mb-2 text-blue-800">パーソナル発声エクササイズ</h3>
                        <p class="text-gray-700">診断結果に基づき、あなただけに合った発声エクササイズを行います。感覚的ではなく、身体の構造に基づいたアプローチで、発声を整えていきます。</p>
                    </div>
                </div>
                <div class="card text-left flex flex-col sm:flex-row items-start gap-6">
                    <div class="bg-blue-600 text-white rounded-full w-16 h-16 flex-shrink-0 flex items-center justify-center text-2xl font-bold">4</div>
                    <div>
                        <h3 class="font-bold text-xl mb-2 text-blue-800">実践・歌唱指導</h3>
                        <p class="text-gray-700">エクササイズで掴んだ感覚を、実際の歌に活かしていきます。表現したいニュアンスやテクニックを、あなたのペースに合わせて丁寧に指導します。</p>
                    </div>
                </div>
            </div>
            <p class="mt-8 text-gray-600">必要に応じて、発声や歌の土台となる姿勢・呼吸の見直しも行います。</p>
        </section>

        <!-- 形式・料金 -->
        <section id="details" class="mb-16">
            <div class="text-center mb-8">
                 <h2 class="section-title">レッスン詳細</h2>
            </div>
            <div class="max-w-4xl mx-auto grid md:grid-cols-2 gap-8">
                <div class="card">
                    <h3 class="font-bold text-xl mb-4 text-center text-blue-800">レッスン形式・場所</h3>
                    <ul class="space-y-3 text-gray-700">
                        <li class="flex"><strong class="w-24 flex-shrink-0">形式:</strong>マンツーマンレッスン</li>
                        <li class="flex"><strong class="w-24 flex-shrink-0">場所:</strong>対面 (藤沢/横浜) or オンライン (Zoom)</li>
                        <li class="flex"><strong class="w-24 flex-shrink-0">人数:</strong>1日最大3〜4名まで</li>
                    </ul>
                </div>
                <div class="card">
                    <h3 class="font-bold text-xl mb-4 text-center text-blue-800">スケジュール・料金</h3>
                    <ul class="space-y-3 text-gray-700">
                        <li class="flex"><strong class="w-24 flex-shrink-0">募集期間:</strong>〜8月20日まで (50名限定)</li>
                        <li class="flex"><strong class="w-24 flex-shrink-0">日時:</strong>希望者にご案内するカレンダーにて調整</li>
                        <li class="flex"><strong class="w-24 flex-shrink-0">料金:</strong>体験 <strong>5,500円</strong> <span class="text-sm line-through">(通常7,700円)</span></li>
                        <li class="flex"><strong class="w-24 flex-shrink-0">支払方法:</strong>銀行振込 (事前)</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- 講師プロフィール -->
        <section id="profile" class="text-center mb-16">
             <h2 class="section-title">講師プロフィール</h2>
             <div class="card max-w-3xl mx-auto flex flex-col md:flex-row items-center gap-8">
                <img src="https://i.imgur.com/hVmMt9Y.jpeg" alt="Shoko プロフィール写真" class="w-40 h-40 rounded-full object-cover shadow-lg flex-shrink-0" />
                <div class="text-left">
                    <h3 class="text-2xl font-bold text-blue-900">Shoko</h3>
                    <p class="text-blue-700 font-semibold mb-3">ボイストレーナー / シンガー</p>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        声を壊した経験をきっかけに発声を学び、音楽スクールでプロから一般、子どもから大人まで幅広く指導。2025年1月より「Voice Professionals」にて本格的に音声学・解剖学・ハリウッド式を学び、現在は上級コース「Boot Program」でさらなる技術を習得中。
                    </p>
                    <p class="text-sm text-gray-600"><strong>資格:</strong> Voice Professionals ボイストレーナー養成講座2期修了</p>
                    <p class="text-sm text-gray-600"><strong>得意分野:</strong> ボイスタイプ診断／発声改善／歌唱指導</p>
                </div>
             </div>
        </section>
        
        <!-- ご確認事項 -->
        <section id="notes" class="mb-16">
            <div class="text-center mb-8">
                <h2 class="section-title">お願い＆ご確認事項</h2>
            </div>
            <div class="max-w-3xl mx-auto space-y-4">
                <div class="card text-left">
                    <h4 class="font-bold text-lg mb-2">✅ レッスン録画のお願い</h4>
                    <p class="text-gray-600">品質向上・フィードバックのため、レッスンの様子を録画させていただきます。</p>
                </div>
                <div class="card text-left">
                    <h4 class="font-bold text-lg mb-2">✅ アンケートご協力</h4>
                    <p class="text-gray-600">より良いレッスンのため、簡単なアンケートにご協力ください。辛口コメントも歓迎です！</p>
                </div>
                <div class="card text-left">
                    <h4 class="font-bold text-lg mb-2">✅ オンライン参加時の注意点</h4>
                    <ul class="list-disc list-inside text-gray-600 space-y-1">
                        <li>安定したインターネット環境をご用意ください。</li>
                        <li>講師ピアノ音→あなたの声、の順番で行います（音のズレ防止のため）。</li>
                        <li>歌いたい楽曲の音源（YouTube等）をご自身でご用意ください。</li>
                        <li>Zoom設定の詳細は別途お送りします。</li>
                    </ul>
                </div>
                <div class="card text-left bg-red-50 border-l-4 border-red-400">
                    <h4 class="font-bold text-lg mb-2 text-red-800">⚠️ キャンセルポリシー</h4>
                    <p class="text-red-700">1週間前を過ぎたキャンセル・変更はスタジオ代の実費をご負担いただきます（オンラインレッスンの場合も講師はスタジオを予約しているため）。</p>
                </div>
            </div>
        </section>

        <!-- 申込み -->
        <section id="apply" class="text-center py-16 bg-gray-100 rounded-lg">
            <h2 class="section-title">お申込み・お問合せ</h2>
            <p class="max-w-2xl mx-auto text-gray-700 mb-8">
                自分の声を見つけて、理想の声に磨くボイトレを始めませんか？<br>
                定員に達し次第、受付終了となりますのでお早めに！
            </p>
            <div class="flex flex-col sm:flex-row justify-center items-center gap-4">
                <a href="https://www.instagram.com/shoko_voice_studio_tida/" target="_blank" rel="noopener noreferrer" class="cta-button w-full sm:w-auto">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 inline-block mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" /></svg>
                    Instagram DMでお問合せ
                </a>
                <a href="https://forms.gle/vWxmN9cNhXv4MrrR7" target="_blank" rel="noopener noreferrer" class="cta-button w-full sm:w-auto">
                    📝 フォームから申込む
                </a>
            </div>
            <p class="mt-4 text-sm text-gray-500">※先着順となります</p>
        </section>

    </main>

    <!-- フッター -->
    <footer class="bg-gray-800 text-white text-center py-6">
        <p>&copy; 2025 Shoko's Voice Training. All Rights Reserved.</p>
    </footer>

</body>
</html>

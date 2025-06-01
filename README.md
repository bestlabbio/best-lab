下記のコードでindex.html を生成してダウンロードしたい
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Best Lab | 膝関節バイオメカニクス・リハビリテーション科学</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;500;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Noto Sans JP', sans-serif;
      background-color: #f8f9fa;
    }
    .hero-image {
      background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://www.spu.ac.jp/Portals/0/images/about/campus/img_01-1.jpg');
      height: 400px;
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
      position: relative;
    }
    .hero-text {
      text-align: center;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: white;
    }
    .section-title {
      position: relative;
      padding-bottom: 15px;
      margin-bottom: 20px;
      border-bottom: 2px solid #1a56db;
    }
    .section-title::after {
      content: '';
      position: absolute;
      bottom: -2px;
      left: 0;
      height: 2px;
      width: 60px;
      background-color: #2563eb;
    }
    .research-card {
      transition: transform 0.3s ease-in-out;
    }
    .research-card:hover {
      transform: translateY(-5px);
    }
    .timeline {
      border-left: 2px solid #2563eb;
      position: relative;
      padding-left: 20px;
    }
    .timeline-item::before {
      content: '';
      position: absolute;
      left: -6px;
      height: 12px;
      width: 12px;
      border-radius: 50%;
      background-color: #2563eb;
      margin-top: 5px;
    }
  </style>
</head>
<body>
  <!-- ヘッダー -->
  <div class="hero-image">
    <div class="hero-text">
      <h1 class="text-4xl font-bold mb-2">小栢研究室</h1>
      <h2 class="text-2xl mb-4">膝関節バイオメカニクス・リハビリテーション科学</h2>
      <p class="text-xl">埼玉県立大学健康科学研究科</p>
    </div>
  </div>

  <!-- ナビゲーション -->
  <nav class="bg-white shadow-md">
    <div class="container mx-auto px-4">
      <div class="flex items-center justify-between py-4">
        <div class="text-xl font-semibold text-blue-800">小栢研究室</div>
        <div class="hidden md:flex">
          <a href="#about" class="px-3 py-2 mx-2 text-gray-700 hover:text-blue-600">研究室について</a>
          <a href="#members" class="px-3 py-2 mx-2 text-gray-700 hover:text-blue-600">メンバー</a>
          <a href="#research" class="px-3 py-2 mx-2 text-gray-700 hover:text-blue-600">研究内容</a>
          <a href="#publications" class="px-3 py-2 mx-2 text-gray-700 hover:text-blue-600">業績</a>
          <a href="#contact" class="px-3 py-2 mx-2 text-gray-700 hover:text-blue-600">連絡先</a>
        </div>
      </div>
    </div>
  </nav>

  <!-- メインコンテンツ -->
  <div class="container mx-auto px-4 py-8">
    
    <!-- 研究室について -->
    <section id="about" class="mb-16">
      <h2 class="section-title text-2xl font-bold text-blue-800">研究室について</h2>
      <div class="flex flex-wrap -mx-4">
        <div class="w-full md:w-2/3 px-4 mb-8">
          <p class="mb-4 text-lg">当研究室では、理学療法士の臨床的視点とバイオメカニクス・工学的手法を融合し、特に膝関節を中心とした運動器障害の予防・治療に関する研究を行っています。</p>
          <p class="mb-4">変形性膝関節症（膝OA）は高齢社会において重要な課題であり、我々は膝関節にかかるメカニカルストレスと疼痛メカニズムの解明を通じて、効果的な予防・治療法の開発を目指しています。</p>
          <p class="mb-4">モーションキャプチャ技術や有限要素法を駆使した動作解析により、杖歩行の効果検証や膝蓋下脂肪体の機能障害との関連性など、多角的な研究アプローチを展開しています。</p>
        </div>
        <div class="w-full md:w-1/3 px-4">
          <div class="border rounded-lg overflow-hidden shadow-lg">
            <img src="https://s-nagasaki.com/wp-content/uploads/2017/05/1cc83233b2daa2fbb6df0d83ee280ace.png" alt="膝関節の解剖学とバイオメカニクス" class="w-full h-auto">
            <div class="p-4 bg-white">
              <p class="text-sm text-gray-600">膝関節のバイオメカニクス解析は当研究室の主要テーマです</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    
    <!-- メンバー -->
    <section id="members" class="mb-16">
      <h2 class="section-title text-2xl font-bold text-blue-800">メンバー</h2>
      
      <!-- 教員 -->
      <div class="mb-8 bg-white shadow-md rounded-lg p-6">
        <div class="flex flex-wrap md:flex-nowrap">
          <div class="w-full md:w-1/4">
            <div class="bg-gray-100 rounded-lg p-4 text-center mb-4 md:mb-0">
              <i class="fas fa-user-tie text-5xl text-blue-800 mb-2"></i>
              <h3 class="font-bold text-lg">准教授</h3>
            </div>
          </div>
          <div class="w-full md:w-3/4 md:pl-6">
            <h3 class="text-xl font-bold mb-2">小栢 進也 <span class="text-sm font-normal">（博士・工学）</span></h3>
            <p class="mb-2"><span class="font-semibold">所属:</span> 埼玉県立大学 保健医療福祉学部 理学療法学科</p>
            <p class="mb-2"><span class="font-semibold">研究者番号:</span> 90611426</p>
            <p class="mb-4"><span class="font-semibold">専門分野:</span> リハビリテーション科学、バイオメカニクス、運動器障害</p>
            <p class="text-gray-700">変形性膝関節症患者の力学的ストレスと疼痛メカニズムの解明に取り組み、臨床的視点と工学的手法を融合した研究を推進しています。膝関節にかかるストレスを計算することで、関節症の進行を予防する治療法や装具の検討・開発を行っています。</p>
          </div>
        </div>
      </div>
      
      <!-- 博士研究員 -->
      <div class="mb-8 bg-white shadow-md rounded-lg p-6">
        <div class="flex flex-wrap md:flex-nowrap">
          <div class="w-full md:w-1/4">
            <div class="bg-gray-100 rounded-lg p-4 text-center mb-4 md:mb-0">
              <i class="fas fa-microscope text-5xl text-blue-600 mb-2"></i>
              <h3 class="font-bold text-lg">博士研究員</h3>
            </div>
          </div>
          <div class="w-full md:w-3/4 md:pl-6">
            <h3 class="text-xl font-bold mb-2">島村 雅彦 <span class="text-sm font-normal">（博士・工学）</span></h3>
            <p class="mb-4"><span class="font-semibold">研究テーマ:</span> バイオメカニクス解析、リハビリ工学</p>
            <p class="text-gray-700">日本学術振興会 科学研究費助成事業（若手研究）取得。膝関節の力学解析と関節症予防に関する研究を行っています。</p>
          </div>
        </div>
      </div>
      
      <!-- 博士後期課程 -->
      <div class="mb-8 bg-white shadow-md rounded-lg p-6">
        <div class="flex flex-wrap md:flex-nowrap">
          <div class="w-full md:w-1/4">
            <div class="bg-gray-100 rounded-lg p-4 text-center mb-4 md:mb-0">
              <i class="fas fa-user-graduate text-5xl text-blue-500 mb-2"></i>
              <h3 class="font-bold text-lg">博士後期課程</h3>
            </div>
          </div>
          <div class="w-full md:w-3/4 md:pl-6">
            <h3 class="text-xl font-bold mb-2">堀内 健太 <span class="text-sm font-normal">（理学療法士）</span></h3>
            <p class="mb-2"><span class="font-semibold">学年:</span> D1</p>
            <p class="mb-4"><span class="font-semibold">研究テーマ:</span> コンピュータシミュレーションとリハビリテーション</p>
            <p class="text-gray-700">理学療法士としての臨床経験を活かし、膝関節疾患に対する効果的なリハビリテーション手法の開発研究に従事しています。</p>
          </div>
        </div>
      </div>
      
      <!-- 学部生 -->
      <div class="bg-white shadow-md rounded-lg p-6">
        <div class="flex flex-wrap md:flex-nowrap">
          <div class="w-full md:w-1/4">
            <div class="bg-gray-100 rounded-lg p-4 text-center mb-4 md:mb-0">
              <i class="fas fa-users text-5xl text-blue-400 mb-2"></i>
              <h3 class="font-bold text-lg">学部生</h3>
            </div>
          </div>
          <div class="w-full md:w-3/4 md:pl-6">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div class="border-l-4 border-blue-400 pl-4">
                <h4 class="font-bold">4年生</h4>
                <p>4名</p>
              </div>
              <div class="border-l-4 border-blue-300 pl-4">
                <h4 class="font-bold">3年生</h4>
                <p>1名</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    
    <!-- 研究内容 -->
    <section id="research" class="mb-16">
      <h2 class="section-title text-2xl font-bold text-blue-800">研究内容</h2>
      
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
        <!-- 研究テーマ1 -->
        <div class="bg-white rounded-lg overflow-hidden shadow-md research-card">
          <div class="p-6">
            <div class="flex items-center mb-4">
              <div class="bg-blue-100 p-3 rounded-full mr-4">
                <i class="fas fa-bone text-blue-700 text-xl"></i>
              </div>
              <h3 class="text-lg font-semibold">膝関節の力学的ストレスと疼痛メカニズムの解明</h3>
            </div>
            <p class="text-gray-700">変形性膝関節症における膝関節にかかる力学的ストレスを定量化し、疼痛発生メカニズムを解明することで、効果的な予防・治療法の開発につなげます。最新の動作解析技術とシミュレーションを駆使した研究を実施しています。</p>
          </div>
          <div class="px-6 py-4 bg-gray-50">
            <span class="inline-block bg-blue-100 rounded-full px-3 py-1 text-sm font-semibold text-blue-700 mr-2 mb-2">#変形性膝関節症</span>
            <span class="inline-block bg-blue-100 rounded-full px-3 py-1 text-sm font-semibold text-blue-700 mr-2 mb-2">#疼痛メカニズム</span>
          </div>
        </div>
        
        <!-- 研究テーマ2 -->
        <div class="bg-white rounded-lg overflow-hidden shadow-md research-card">
          <div class="p-6">
            <div class="flex items-center mb-4">
              <div class="bg-blue-100 p-3 rounded-full mr-4">
                <i class="fas fa-walking text-blue-700 text-xl"></i>
              </div>
              <h3 class="text-lg font-semibold">杖歩行によるバイオメカニクス的効果の分析</h3>
            </div>
            <p class="text-gray-700">杖歩行が膝関節にかかる圧縮力や剪断力にどのような影響を与えるかを解析し、最適な杖歩行の方法を科学的に検証しています。有限要素法を用いたシミュレーションなど、先進的な手法を用いた研究を展開しています。</p>
          </div>
          <div class="px-6 py-4 bg-gray-50">
            <span class="inline-block bg-blue-100 rounded-full px-3 py-1 text-sm font-semibold text-blue-700 mr-2 mb-2">#杖歩行</span>
            <span class="inline-block bg-blue-100 rounded-full px-3 py-1 text-sm font-semibold text-blue-700 mr-2 mb-2">#関節圧縮力</span>
          </div>
        </div>
        
        <!-- 研究テーマ3 -->
        <div class="bg-white rounded-lg overflow-hidden shadow-md research-card">
          <div class="p-6">
            <div class="flex items-center mb-4">
              <div class="bg-blue-100 p-3 rounded-full mr-4">
                <i class="fas fa-heartbeat text-blue-700 text-xl"></i>
              </div>
              <h3 class="text-lg font-semibold">膝蓋下脂肪体の硬度と機能障害の関係</h3>
            </div>
            <p class="text-gray-700">膝蓋下脂肪体（ホフマン体）の硬度変化が膝関節機能にどのような影響を与えるかを解明し、新たな治療ターゲットとしての可能性を探っています。超音波エラストグラフィーなどの画像診断技術と臨床評価を組み合わせた研究を行っています。</p>
          </div>
          <div class="px-6 py-4 bg-gray-50">
            <span class="inline-block bg-blue-100 rounded-full px-3 py-1 text-sm font-semibold text-blue-700 mr-2 mb-2">#膝蓋下脂肪体</span>
            <span class="inline-block bg-blue-100 rounded-full px-3 py-1 text-sm font-semibold text-blue-700 mr-2 mb-2">#機能障害</span>
          </div>
        </div>
        
        <!-- 研究テーマ4 -->
        <div class="bg-white rounded-lg overflow-hidden shadow-md research-card">
          <div class="p-6">
            <div class="flex items-center mb-4">
              <div class="bg-blue-100 p-3 rounded-full mr-4">
                <i class="fas fa-laptop-code text-blue-700 text-xl"></i>
              </div>
              <h3 class="text-lg font-semibold">モーションキャプチャを用いた動作解析</h3>
            </div>
            <p class="text-gray-700">最新のモーションキャプチャ技術を用いて歩行や日常生活動作を詳細に分析し、運動器障害のメカニズム解明や効果的なリハビリテーション手法の開発に取り組んでいます。健常者と患者の動作比較から新たな知見を得る研究を推進しています。</p>
          </div>
          <div class="px-6 py-4 bg-gray-50">
            <span class="inline-block bg-blue-100 rounded-full px-3 py-1 text-sm font-semibold text-blue-700 mr-2 mb-2">#モーションキャプチャ</span>
            <span class="inline-block bg-blue-100 rounded-full px-3 py-1 text-sm font-semibold text-blue-700 mr-2 mb-2">#動作解析</span>
          </div>
        </div>
      </div>
      
      <div class="bg-white rounded-lg p-6 shadow-md">
        <h3 class="text-xl font-bold mb-4">研究設備</h3>
        <div class="flex flex-wrap items-center">
          <div class="w-full md:w-1/2 p-4">
            <div class="bg-gray-100 p-4 rounded-lg">
              <h4 class="font-bold mb-2">モーションキャプチャシステム</h4>
              <p class="text-gray-700 mb-2">三次元動作解析による歩行・運動パターンの詳細な計測が可能です。</p>
              <div class="mt-4">
                <img src="https://archivetips.com/public_img/prod/2014_08_gait-and-rehab-qtm-patient.jpg" alt="モーションキャプチャシステム" class="rounded-lg shadow-sm">
              </div>
            </div>
          </div>
          <div class="w-full md:w-1/2 p-4">
            <div class="bg-gray-100 p-4 rounded-lg">
              <h4 class="font-bold mb-2">バイオメカニクス解析ソフトウェア</h4>
              <p class="text-gray-700 mb-2">有限要素法による膝関節の力学的シミュレーションを実施しています。</p>
              <div class="mt-4">
                <img src="https://s3-ap-northeast-1.amazonaws.com/post-production/uploads/ckeditor/pictures/6367/content_1.jpg" alt="バイオメカニクス解析" class="rounded-lg shadow-sm">
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    
    <!-- 業績 -->
    <section id="publications" class="mb-16">
      <h2 class="section-title text-2xl font-bold text-blue-800">主な業績</h2>
      
      <div class="bg-white rounded-lg shadow-md p-6 mb-6">
        <h3 class="text-xl font-semibold mb-4">研究費獲得状況</h3>
        <ul class="timeline">
          <li class="timeline-item relative pl-4 pb-6">
            <p class="font-bold">関節剪断ストレスが変形性膝関節症の痛みを引き起こすメカニズムの解明</p>
            <p class="text-gray-600">研究代表者: 小栢 進也</p>
            <p class="text-gray-600">研究期間: 2022年度 - 2024年度</p>
            <p class="text-gray-600">研究種目: 基盤研究(C)</p>
          </li>
          <li class="timeline-item relative pl-4 pb-6">
            <p class="font-bold">変形性膝関節症患者の足部形態・機能と膝関節のメカニカルストレスの関係の解明</p>
            <p class="text-gray-600">研究代表者: 小栢 進也</p>
            <p class="text-gray-600">研究期間: 2019年度 - 2025年度</p>
            <p class="text-gray-600">研究種目: 若手研究</p>
          </li>
          <li class="timeline-item relative pl-4">
            <p class="font-bold">科学研究費助成事業 若手研究</p>
            <p class="text-gray-600">研究代表者: 島村 雅彦</p>
            <p class="text-gray-600">研究期間: 2023年4月 - 2026年3月</p>
          </li>
        </ul>
      </div>
      
      <div class="bg-white rounded-lg shadow-md p-6">
        <h3 class="text-xl font-semibold mb-4">論文・発表</h3>
        
        <div class="mb-6">
          <h4 class="font-bold text-blue-800 mb-2">論文</h4>
          <ul class="space-y-4 list-disc list-inside">
            <li>島村 雅彦, 中島 浩二, 鈴木 佳代子, 松野 隆史, 小栢 進也: 保健医療学雑誌 14(2) 93-100 2023年10月</li>
            <li>島村雅彦, 江澤良孝, 田村善昭, 高清水聖, 佐藤大亮: 日本包装学会誌 28(5) 2019年</li>
            <li>SHIMAMURA Masahiko, EZAWA Yoshitaka, TAMURA Yoshiaki, TAKASHIMIZU Satoru, SATOU Daisuke: Mechanical Engineering Journal 3(4) 16-00072 2016年</li>
          </ul>
        </div>
        
        <div class="mb-6">
          <h4 class="font-bold text-blue-800 mb-2">国際学会</h4>
          <ul class="space-y-4 list-disc list-inside">
            <li>Ogaya S, Shimamura M., Horiuchi K, Kido S.: 16th Asian congress of physical therapy 2023年11月</li>
          </ul>
        </div>
        
        <div class="mb-6">
          <h4 class="font-bold text-blue-800 mb-2">国内学会</h4>
          <ul class="space-y-4 list-disc list-inside">
            <li>旭竜馬, 島村雅彦, 小栢進也: 第32回埼玉県理学療法学会 2025年1月</li>
            <li>小栢 進也, 須崎 柊, 平 千夏, 高橋 和, 翠川 航介, 島村 雅彦: 日本運動器理学療法学会学術大会 2024年9月</li>
            <li>旭 竜馬, 小栢 進也, 島村 雅彦, 他: 日本骨粗鬆症学会 2024年9月</li>
            <li>島村 雅彦, 木戸 聡史, 堀内 健太, 須崎 柊, 小栢 進也: 臨床歩行分析研究会定例会 2024年3月</li>
            <li>堀内 健太, 王 森, 島村 雅彦, 小栢 進也: 関東甲信越ブロック理学療法士学会 2024年</li>
            <li>島村 雅彦, 中島 浩二, 鈴木 佳代子, 松野 隆史, 小栢 進也: JSEK2022 2023年3月</li>
          </ul>
        </div>
        
        <p class="mt-6 text-blue-700 font-semibold">詳しい業績は <a href="https://researchmap.jp/read0156816" target="_blank" class="underline">researchmap</a> をご覧ください。</p>
      </div>
    </section>
    
    <!-- 連絡先 -->
    <section id="contact" class="mb-16">
      <h2 class="section-title text-2xl font-bold text-blue-800">連絡先</h2>
      
      <div class="bg-white rounded-lg shadow-md p-6">
        <div class="flex flex-wrap -mx-4">
          <div class="w-full md:w-1/2 px-4 mb-6 md:mb-0">
            <h3 class="text-xl font-semibold mb-4">小栢研究室</h3>
            <div class="flex items-start mb-3">
              <i class="fas fa-map-marker-alt text-blue-700 mt-1 mr-3"></i>
              <div>
                <p>〒343-8540</p>
                <p>埼玉県越谷市三野宮820番地</p>
                <p>埼玉県立大学 健康科学研究科</p>
              </div>
            </div>
            <div class="flex items-start mb-3">
              <i class="fas fa-envelope text-blue-700 mt-1 mr-3"></i>
              <p>shinya-ogaya[at]spu.ac.jp <span class="text-sm text-gray-500">（[at]を@に置き換えてください）</span></p>
            </div>
            <div class="flex items-start">
              <i class="fas fa-globe text-blue-700 mt-1 mr-3"></i>
              <p><a href="https://researchmap.jp/read0156816" target="_blank" class="text-blue-700 underline">researchmap プロフィール</a></p>
            </div>
          </div>
          <div class="w-full md:w-1/2 px-4">
            <h3 class="text-xl font-semibold mb-4">アクセス</h3>
            <div class="bg-gray-100 p-4 rounded-lg mb-4">
              <p class="mb-2"><i class="fas fa-train mr-2 text-blue-700"></i> 東武スカイツリーライン「せんげん台駅」から徒歩約15分</p>
            </div>
            <div class="rounded-lg overflow-hidden">
              <img src="https://www.spu.ac.jp/Portals/0/images/about/campus/img_campus.png" alt="埼玉県立大学キャンパスマップ" class="w-full h-auto">
            </div>
          </div>
        </div>
      </div>
    </section>
    
    <!-- 研究室からのお知らせ -->
    <section class="mb-16">
      <h2 class="section-title text-2xl font-bold text-blue-800">研究室からのお知らせ</h2>
      
      <div class="bg-white rounded-lg shadow-md p-6">
        <div class="border-l-4 border-blue-500 pl-4 mb-6">
          <h3 class="text-xl font-semibold mb-2">研究室見学・学生募集について</h3>
          <p class="text-gray-700">当研究室では、運動器リハビリテーションやバイオメカニクスに興味のある学生を随時募集しています。見学希望の方は、メールでお問い合わせください。</p>
        </div>
        
        <div class="border-l-4 border-green-500 pl-4">
          <h3 class="text-xl font-semibold mb-2">共同研究について</h3>
          <p class="text-gray-700">医療機関や企業との共同研究も積極的に行っています。膝関節疾患の診断・治療に関する新たな知見や技術開発にご興味のある方は、お気軽にご連絡ください。</p>
        </div>
      </div>
    </section>
  </div>

  <!-- フッター -->
  <footer class="bg-gray-800 text-white py-8">
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap justify-between">
        <div class="w-full md:w-1/3 mb-6 md:mb-0">
          <h3 class="text-xl font-semibold mb-4">小栢研究室</h3>
          <p>膝関節バイオメカニクス・リハビリテーション科学</p>
          <p class="mt-2">埼玉県立大学 健康科学研究科</p>
        </div>
        <div class="w-full md:w-1/3 mb-6 md:mb-0">
          <h3 class="text-xl font-semibold mb-4">リンク</h3>
          <ul class="space-y-2">
            <li><a href="https://www.spu.ac.jp/" target="_blank" class="hover:text-blue-300">埼玉県立大学</a></li>
            <li><a href="https://www.spu.ac.jp/academics/gs/" target="_blank" class="hover:text-blue-300">埼玉県立大学大学院</a></li>
            <li><a href="https://researchmap.jp/read0156816" target="_blank" class="hover:text-blue-300">研究者データベース</a></li>
          </ul>
        </div>
        <div class="w-full md:w-1/3">
          <h3 class="text-xl font-semibold mb-4">関連学会</h3>
          <ul class="space-y-2">
            <li>日本理学療法学会</li>
            <li>日本バイオメカニクス学会</li>
            <li>臨床歩行分析研究会</li>
            <li>日本運動器理学療法学会</li>
          </ul>
        </div>
      </div>
      <div class="border-t border-gray-700 mt-8 pt-6 text-center">
        <p>&copy; 2025 小栢研究室 - 埼玉県立大学</p>
      </div>
    </div>
  </footer>
</body>
</html>

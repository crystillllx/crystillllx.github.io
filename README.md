# crystillllx.github.io
<html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>日本 - 樱花之国</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #ffb6c1, #ffffff);
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            padding-bottom: 30px;
        }
        
        header {
            text-align: center;
            padding: 40px 0;
            background: linear-gradient(135deg, #ff6b8b, #ff8e9e);
            color: white;
            margin-bottom: 40px;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .subtitle {
            font-size: 1.2rem;
            font-weight: 300;
		text-indent: 50px;
        }
        
        .hero-image {
            width: 100%;
            height: 500px;
            object-fit: cover;
            margin-bottom: 20px;
        }
        
        .tabs {
            display: flex;
            justify-content: center;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }
        
        .tab-btn {
            padding: 12px 25px;
            background: #f8f8f8;
            border: none;
            cursor: pointer;
            font-size: 1rem;
            font-weight: 600;
            color: #555;
            transition: all 0.3s ease;
            border-radius: 5px 5px 0 0;
            margin: 0 5px;
        }
        
        .tab-btn:hover {
            background: #ffccd5;
            color: #333;
        }
        
        .tab-btn.active {
            background: #ff6b8b;
            color: white;
        }
        
        .tab-content {
            display: none;
            padding: 0 30px;
            animation: fadeIn 0.5s ease;
        }
        
        .tab-content.active {
            display: block;
        }
        
        h2 {
            color: #ff6b8b;
            margin: 20px 0;
            font-size: 1.8rem;
            border-bottom: 2px solid #ffccd5;
            padding-bottom: 10px;
        }
        
        h3 {
            color: #d23669;
            margin: 15px 0;
            font-size: 1.4rem;
        }
        
        p {
            margin-bottom: 15px;
            text-align: justify;
        }
        
        .image-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .image-card {
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        
        .image-card:hover {
            transform: translateY(-5px);
        }
        
        .image-card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        
        .image-card p {
            padding: 10px;
            background: white;
            margin: 0;
            font-size: 0.9rem;
        }
        
        .timeline {
            position: relative;
            max-width: 800px;
            margin: 30px auto;
        }
        
        .timeline::after {
            content: '';
            position: absolute;
            width: 2px;
            background-color: #ff6b8b;
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -1px;
        }
        
        .timeline-item {
            padding: 10px 40px;
            position: relative;
            width: 50%;
            box-sizing: border-box;
        }
        
        .timeline-item::after {
            content: '';
            position: absolute;
            width: 20px;
            height: 20px;
            background-color: white;
            border: 4px solid #ff6b8b;
            border-radius: 50%;
            top: 15px;
            z-index: 1;
        }
        
        .left {
            left: 0;
        }
        
        .right {
            left: 50%;
        }
        
        .left::after {
            right: -10px;
        }
        
        .right::after {
            left: -10px;
        }
        
        .timeline-content {
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
        }
        
        .category {
            margin-bottom: 30px;
        }
        
        .food-item {
            display: flex;
            margin-bottom: 20px;
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
        }
        
        .food-img {
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
        
        .food-desc {
            padding: 15px;
            flex: 1;
        }
        
        .food-desc h4 {
            color: #d23669;
            margin-bottom: 10px;
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: #666;
            font-size: 0.9rem;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        @media (max-width: 768px) {
            .timeline::after {
                left: 31px;
            }
            
            .timeline-item {
                width: 100%;
                padding-left: 70px;
                padding-right: 25px;
            }
            
            .timeline-item::after {
                left: 21px;
            }
            
            .left::after, .right::after {
                left: 21px;
            }
            
            .right {
                left: 0;
            }
            
            .food-item {
                flex-direction: column;
            }
            
            .food-img {
                width: 100%;
                height: 200px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>日本</h1>
            <p class="subtitle">樱花之国 · 传统与现代的完美融合</p>
        </header>
        
        <img src="https://www.datocms-assets.com/101439/1700902043-icons-of-japan.jpg?auto=format&fit=crop&h=800&w=1200" alt="日本富士山" class="hero-image">
        
        <div class="tabs">
            <button class="tab-btn active" onclick="openTab(event, 'history')">历史</button>
            <button class="tab-btn" onclick="openTab(event, 'geography')">地理</button>
            <button class="tab-btn" onclick="openTab(event, 'culture')">文化</button>
            <button class="tab-btn" onclick="openTab(event, 'attractions')">景点</button>
            <button class="tab-btn" onclick="openTab(event, 'cuisine')">美食</button>
        </div>
        
        <!-- 历史标签内容 -->
        <div id="history" class="tab-content active">
            <h2>日本历史</h2>
            <p>日本拥有悠久而丰富的历史，从古代文明到现代经济强国，经历了多个重要时期。</p>
            
            <div class="timeline">
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>旧石器时代（公元前10万年-公园前18,000年左右）</h3>
                        <p>日本旧石器时代起源于日本列岛与大陆相连的时期，当时的人类为了追逐猎物来到日本列岛，并成为最早的住民。这一时期的日本人使用以石头打造而成的刀具和用动物的骨头或头角制成的骨角器，通过狩猎和采集来获取日常食物。人们过着狩猎和采集的生活，不长期定居一处，也没有农耕的迹象。</p>
                    </div>
                </div>

                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>绳文时代 (公元前16,000年-公元前300年)</h3>
                        <p>日本最早的文明时期，以绳文式陶器闻名。这个时候的人们制作绳文式陶器，大部分住在半地穴式房屋（竖穴式住居），形成了早期的定居社会。使用弓箭狩猎、贝冢渔捞、采集植物等为生，使用打制石器、磨制石器、骨角器等等。</p>
                    </div>
                </div>
                
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>弥生时代（公元前300年-公元250年）</h3>
                        <p>水稻种植从朝鲜半岛传到日本，因而产生了以种植水稻为主的农业文化，并开始使用铜器与铁器。这时的原始社会开始逐渐向阶级社会过渡。在当时频繁发生的贫穷部落与富裕部落之间的战争中，武力强大的部落征服弱小部落而形成许多个小国。之后，小国间也开始互相攻伐，从而引发日本国内的第一次大规模战争「倭国大乱」。「倭国大乱」以巫女卑弥呼被立为「倭国」之王而告终。于是，以卑弥呼所统领的「邪马台国」为中心的「邪马台国部落联盟」形成，「大和政权」由此诞生。</p>
                    </div>
                </div>

                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>古坟时代 (250年-592年)</h3>
                        <p>又称大和时代的古坟时代，因当时统治者大量营建具有独特“前方后圆”形状的大型古坟而得名。这一时期，日本出现了以畿内地区（今奈良县一带）为中心的全国性中央政权——大和政权。大和政权由当地强大的豪族联盟构成，逐步确立了对日本列岛的统治地位。
<br>随着与朝鲜半岛及中国大陆的交流日益频繁，日本从外部引入了先进的铁器技术、新的农业实践以及汉字书写系统，不仅获得了朝鲜半岛丰富的铁资源，也积极吸收了来自大陆的文化成果。大和政权在政治、文化和技术层面广泛采纳中国制度与文化，推动了日本社会的深刻变革。</br>
这一时期的文化发展为后来的律令国家体制奠定了重要基础，是日本国家形成过程中的关键阶段。</p>
                    </div>
                </div>
                
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>飞鸟时代 (592年-710年)</h3>
                        <p>在飞鸟时代，以圣德太子为核心的各方权力人物齐心协力，致力于建立一个以律令制为基础的国家体制。推古天皇、苏我马子与圣德太子共同推行一系列旨在增强国力的改革措施，确立了以天皇为中心的政治制度，并制定了《十七条宪法》，为国家治理奠定了基础。
<br>然而，随着权臣苏我虾夷及其子苏我入鹿权势日盛，并对天皇态度傲慢，朝廷内部的不满情绪日益高涨，皇族与贵族阶层对苏我氏的专横逐渐感到不安。在这种背景下，中臣镰足与中大兄皇子联手，结成反苏我势力，于645年发动「乙巳之变」，成功铲除了苏我氏家族的统治。</br>
政变胜利后，中臣镰足与中大兄皇子推动一系列深远的改革，确立了由天皇直接掌控全国土地、人民与赋税的制度。这场以「乙巳之变」为起点展开的政治变革，被称为「大化革新」。大化改新成为确立中央集权体制与律令制度国家的起点。
<br>此后，作为实施律令制政治的中心，朝廷迁都至仿照唐代长安城建造的平城京，日本历史由此进入奈良时代。</br></p>
                    </div>
                </div>

                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>奈良时代 (710年-794年)</h3>
                        <p>自奈良时代起，日本确立了以天皇为核心的中央集权政治体制。然而，成为国家权力中枢的朝廷内部权力斗争愈发激烈，导致社会局势日益动荡、不安。
<br>在这一不稳定的政治背景下，当时最具影响力的权门贵族——藤原氏，其势力迅速壮大。活跃于飞鸟时代的中臣镰足之子藤原不比等，将女儿嫁给文武天皇，与皇室缔结了亲缘关系。此后，文武天皇之子即位成为圣武天皇，藤原氏的朝廷地位由此更加稳固。</br>
与此同时，寺院势力也逐渐与贵族势力相抗衡。为摆脱大寺院在政治与宗教上的影响，桓武天皇决定将首都从奈良迁至平安京，从地理上拉开与寺院的距离，以巩固皇权。</p>
                    </div>
                </div>
                
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>平安时代 (794年－1185年)</h3>
                        <p>自飞鸟时代起，贵族阶层便一直处于日本政治的核心地位。进入平安时代后，这一地位更是达到了顶峰。尤其以藤原氏为代表的权门贵族，通过扶持自身子孙登上天皇宝座，牢牢掌控了朝政大权。为了削弱权势贵族和僧侣的力量，桓武天皇于784年决定从长冈迁都到山城国的平安京（今京都市），在那里筹建新都，命名为平安京，希望借此获得平安、吉利、安宁与和平。
<br>然而，随着掌权者对户籍与土地的管理日益松懈，朝廷逐渐失去了有效征税的能力，财政状况不断恶化。与此同时，地方豪族依靠垦殖土地积累了大量财富，并开始雇佣武士与佃农，以保卫自身的领地与财产，逐步形成了自有的私人武装力量。</br>
由于朝廷已无力承担地方治安维护的重任，只得将这一职责下放给地方豪族。这一举措进一步助长了豪族的势力，使他们在地方上的影响力日益膨胀。
<br>至平安时代末期，各地崛起的豪族因利益纷争而爆发激烈的相互征伐。朝廷无力调兵镇压，只能依赖强大的豪族力量来平息叛乱。平氏家族正是在镇压叛乱的过程中建立了赫赫战功，得以执掌朝政，成为权倾一时的贵族。</br>
然而，平氏的专横跋扈引发了皇室与另一大豪族——源氏的不满。二者结成同盟，最终将平氏覆灭。立下战功的源氏首领源赖朝被任命为征夷大将军，并在镰仓建立幕府。自此，日本历史正式迈入镰仓时代。</p>
                    </div>
                </div>

                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>镰仓时代（1185年－1333年）</h3>
                        <p>在镰仓时代之前，日本一直是一个由天皇为中心的「朝廷」体制所统治的国家。然而，自镰仓幕府建立以来，政治权力逐渐从朝廷转移至幕府，「幕府将军」成为国家实际上的最高统治者，朝廷的权威随之大幅削弱。
<br>为了夺回失去的政权，朝廷于1221年发动了「承久之乱」。然而，这场起义在短短一个月内便被幕府镇压，反而使镰仓幕府的统治更加稳固，进一步确立了其对全国的实际支配。</br>
然而，随着时间推移，幕府逐渐暴露出财政和权力运作上的困境。特别是在成功抵御蒙古（元朝）两度入侵之后，幕府由于财政拮据，无法以土地或金钱奖赏奋勇抗敌的武士，导致武士阶层对幕府积怨日深，原本赖以维系统治的封建关系开始动摇。
<br>在这种背景下，后醍醐天皇趁势而起，联合对幕府心存不满的武士与大臣，其中最具代表性者为足利尊氏。他们发动「元弘之乱」，共同推翻了镰仓幕府，宣告镰仓时代的结束。</br></p>
                    </div>
                </div>

                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>室町时代 (1336年－1573年)</h3>
                        <p>室町时代的前半期被称为「南北朝时期」，这是一个政局极度混乱的时代。不仅皇室分裂为南朝与北朝，长期对立，幕府内部也因权力纷争频繁发生内讧。
<br>在这种局势下，无论是幕府还是朝廷都逐渐失去了对地方的掌控能力。与此同时，地方上的权势人物、农民与武士势力迅速崛起，揭开了所谓「以下克上」时代的序幕。</br>
通过「以下克上」获得权力与领地的「守护大名」，各自拥兵自重，割据一方，为争夺更广阔的领土而展开连绵不断的战争。日本历史由此进入硝烟四起、战火纷飞的战国时代（后半期）。</p>
                    </div>
                </div>

                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>安土桃山时代 (1573年-1603年)</h3>
                        <p>在「以下克上」的时代风潮中，凭借武力获得权力与领地的「守护大名」中，织田信长迅速崛起，成为首位以统一天下为人生目标的大名。然而，就在其理想即将实现之际，却爆发了一场改变日本历史进程的重大事件——「本能寺之变」。织田信长最为信任的部下明智光秀，在京都的本能寺发动兵变，逼迫信长饮恨自尽。
<br>其后，丰臣秀吉迅速掌握实权，成为织田信长事实上的继承者，并最终完成了日本的初步统一，实现霸业。</br>
丰臣秀吉去世后，德川家康掌握了国家实权，并彻底消灭丰臣家族势力。1603年，天皇下旨封其为征夷大将军设立江户幕府，标志着安土桃山时代的终结，日本正式进入长达两百多年的江户时代。</p>
                    </div>
                </div>

                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>江户时代 (1603年-1868年)</h3>
                        <p>德川家康开创江户幕府后，颁布了一系列法令，以建立起严密的政治体制来巩固政权。江户幕府实施了如「参勤交代」和「武士诸法度」等政策，大幅削弱了大名的经济实力，并加强了对各大名的控制。同时，幕府还通过设立严格的阶层制度，将全体居民分为武士、农民、手工业者和商人四个等级，从而确保了社会的稳定与秩序。
<br>在政治统治的同时，江户幕府还通过儒教思想中的「朱子学」，将其作为官方的正统思想，用以教化民众，稳固其统治基础。</br>
随着这一封建集权体制的完成，江户幕府牢牢掌握了国家的绝对统治权，彻底结束了战国时代诸侯纷争的局面，为长达260余年的太平盛世奠定了坚实的基础。
<br>然而，为了阻止基督教的传入，江户幕府实行了限制海外贸易和禁止日本人出国的「锁国政策」。锁国政策延续了200余年，直到美国海军佩里将军率舰队以武力迫使日本开港，幕府不得不接受开港要求，宣告日本封闭的锁国时代结束。</br>
开国后，幕府未经朝廷的许可就宣布开国，导致国内的不满情绪加剧，并引发了「尊王攘夷」运动。这场运动呼吁恢复天皇的权力，推翻幕府政权。随着尊王攘夷运动的逐步升级，江户幕府最后一位将军德川庆喜意识到局势无法挽回，最终决定主动将政权奉还给天皇，史称「大政奉还」。
<br>尽管仍有一部分不愿屈服的幕府军进行顽抗，但最终都被新政府军平定。至此，江户时代宣告彻底结束。</br></p>
                    </div>
                </div>

                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>明治时代(1868年-1912年)</h3>
                        <p>从幕府手中夺回权力的朝廷建立明治政府，决心将落后于西方国家的日本发展成为一个强大的现代化国家。这个期间，皇室从京都迁到江户，改名东京，自此东京成为日本的首都。
<br>打开国门后，日本清楚地看到了自己与西方国家之间的距离。为了缩小差距，明治政府吸收西方制度，废除江户时代的各种制度。并以富国强兵为口号，为努力建设一个能与西方实力相当的国家，而在政治、经济、军事和文化教育等方面实施了一系列改革措施。从江户幕府末期至明治政府诞生之间所发生的一系列改革及政治运动被称为「明治维新」。</br>
与此同时，随着西洋文明在平民百姓中传播开来，人们的衣食住行等生活方式也发生了翻天覆地的变化。在此期间出现了砖瓦建筑增多，马车在被整齐排列的煤气灯照得一片通明的街道上行驶的城市景象。随着印刷技术的普及，各式各样的报纸也陆续刊行，福泽谕吉的《劝学篇》及明治时代的政治家中江兆民所解释的卢梭思想等新思潮得到广泛传播。</p>
                    </div>
                </div>

                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>大正时代 (1912年－1926年)</h3>
                        <p>迈入大正时代后，第一次世界大战爆发，日本根据英日同盟参战。在这场战争中，日本未直接遭受战火破坏，反而凭借出口贸易的剧增，迎来了前所未有的经济繁荣。然而，随着战争的结束，短暂的“大战景气”急剧反转，日本迅速陷入了战后萧条的危机，民众的生活变得异常艰难。
<br>另一方面，第一次世界大战期间，民主与自由主义思想在日本广泛传播，各种社会运动蓬勃兴起，推动着日本政治体制和社会结构的深刻变革。1925年，《普通选举法》的颁布，为国家政策的制定与实施必须获得公民同意的民主体制奠定了坚实的基础。</br></p>
                    </div>
                </div>

                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>昭和时代 (1926年-1989年)</h3>
                        <p>昭和初期，随着第一次世界大战带来的繁荣景气结束，日本迅速陷入战后经济萧条的困境。战后的不景气导致银行经营状况恶化，昭和金融危机随之爆发。加之关东大地震的重创和美国纽约华尔街股市崩盘引发的全球经济危机，经济形势持续恶化，日本社会深陷贫困。
<br>为应对经济危机的冲击，在军国主义的推动下，日本军方决定单方面在满洲发动战争，进而引发了中日战争，并使日本卷入了第二次世界大战。随着战争的进展，美国在广岛投下原子弹，标志着日本战败的最终结局。随之而来的是日本的投降，并于1945年接受《波茨坦宣言》，宣告战争结束。</br>
第二次世界大战结束后，战败的日本在盟军占领当局GHQ的管理下，实施了一系列重建政策，逐步创造起新的国家体系。在这一过程中，朝鲜战争（韩战）爆发，日本成为美军军需生产和维修的基地。美军大量向日本企业订购军需物资，带来了所谓的「特需景气」，这一阶段为日本经济注入了强劲动力。
<br>然而，随着韩战结束，特需景气也随之终结，日本再次陷入经济萧条。但不景气的局面很快激发了日本重工业的复苏，经济重新步入增长轨道，并进入了被称为「高度经济成长期」的时期。</br>
进入这一阶段后，日本逐渐崛起为世界经济大国，国民生活水平大幅提高。1985年9月22日，日本被迫签订了由世界五大经济强国（美国、日本、西德、英国和法国）在纽约广场饭店达成的「广场协议」，此后，日元急速升值，随之而来的是日本的超级繁荣期，亦即所谓的泡沫经济时代。</p>
                    </div>
                </div>
                
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>平成时代 (1989年－2019年)</h3>
                        <p>平成时代（1989年－2019年）的开始，标志着日本经济从一个以股票和房地产为中心、资产价格过度膨胀的繁荣时期转向了泡沫经济的崩溃。1980年代末，日本经济在全球化和金融化的背景下快速增长，尤其是在房地产和股市领域，资产价格膨胀如泡沫。然而，这种经济增长缺乏实体经济的坚实支撑，最终导致1991年泡沫的破裂，成为历史上著名的「泡沫经济」。
<br>随着泡沫经济的崩溃，日本的经济陷入长期低迷。股市暴跌、房地产价值缩水，造成了个人财富的急剧缩水和大规模的银行坏账。随之而来的是经济衰退，民众的平均年收入出现下降，社会广泛感受到经济困境带来的痛苦。然而，尽管经济不景气，平成时代却见证了年轻一代文化的蓬勃发展，尤其是音乐、时尚、动漫等领域的创新与繁荣，成为全球流行文化的重要组成部分。</br>
同一时期，科技的飞速进步也改变了日本人的日常生活。个人电脑、移动电话和互联网的普及，带来了前所未有的信息化社会变革。这些技术的快速发展不仅改变了人们的生活方式，也推动了社会结构和经济模式的变化。
<br>进入21世纪后，虽然经济持续低迷，但在经历了1997年亚洲金融危机、2008年全球金融危机以及2011年福岛核事故等重大挑战之后，日本的经济结构逐渐发生了转型。雷曼兄弟危机（2008年）导致了日经指数的暴跌，标志着日本经济的又一次重大转折。这一时期，日本社会的生活模式不再局限于「高度经济成长期」的传统模式，取而代之的是更加多元和灵活的生活方式与工作模式的兴起。</br></p>
                    </div>
                </div>
                
                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>令和时代(2019年-至今)</h3>
                        <p>2019年5月1日，日本正式步入“令和时代”，开启了一个生活方式进一步多样化和变革的新时代。然而，2020年，日本受到COVID-19疫情影响严重，导致日本政府数次援引新型冠状特措法发布紧急事态宣言（紧急状态）。随着疫情的持续蔓延，许多学校纷纷关闭校门，转而采用Zoom等在线平台进行授课；大量企业也开始推行远程办公；外出就餐与旅游活动受到严格限制，人们的日常生活因此受到了极大冲击。为了应对疫情的蔓延，社会各界在不同程度上调整了原有的生活方式与消费习惯。</p>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- 地理标签内容 -->
        <div id="geography" class="tab-content">
            <h2>日本地理</h2>
            
            <div class="category">
                <h3>地理位置</h3>
                <p>日本是位于东亚的岛屿国家，地处太平洋西北部，由北海道、本州、九州、四国四大岛以及6,800多个大小岛屿组成。东临太平洋，西以日本海、朝鲜海峡、东海与欧亚大陆的西伯利亚、朝鲜半岛、中国大陆邻接，南以菲律宾海与台湾、马里亚纳群岛邻接，北以宗谷海峡、鄂霍次克海与库页岛、千岛群岛邻接。</p>
            </div>
            
            <div class="category">
                <h3>国土面积与人口</h3>
                <p>日本国土总面积约为377,873平方公里，其中约75%为山地。2025年人口约1亿2355万2千人。人口密度为每平方公里338人，但分布极不均匀，大部分人口集中在沿海平原地区。</p>
            </div>
            
            <div class="category">
                <h3>自然环境</h3>
                <p>日本地形以山地为主，最高峰为富士山（海拔3,776米）。全国有约200座火山，其中约三分之一为活火山。由于日本地处太平洋地震带，因此，日本又是一个火山众多，地震多发的国家。森林覆盖率达67%，是世界上森林覆盖率最高的国家之一。</p>
                
                <div class="image-grid">
                    <div class="image-card">
                        <img src="https://static.gltjp.com/glt/data/article/21000/20522/20231116_142745_b1cac14b_w1920.webp" alt="富士山">
                        <p>富士山 - 日本最高峰</p>
                    </div>
                    <div class="image-card">
                        <img src="https://www.517japan.com/upload/img/20210302/23056f1e5b894e3481ad00a14018f7c0.jpg" alt="日本乡村">
                        <p>日本乡村风光</p>
                    </div>
                    <div class="image-card">
                        <img src="http://img.yun.cnhubei.com/a/10001/202001/1809f0e9850c7ef946b98ba584a84952.jpeg" alt="日本海岸线">
                        <p>日本海岸线</p>
                    </div>
                </div>
            </div>
            
            <div class="category">
                <h3>气候</h3>
                <p>日本气候多样，从北部的亚寒带气候到南部的亚热带气候。大部分地区属于温带季风气候，四季分明。夏季受东南季风影响高温多湿，冬季受西北季风影响寒冷干燥。6-7月为梅雨季节，8-10月常有台风侵袭。</p>
            </div>
            
            <div class="category">
                <h3>主要城市与首都</h3>
                <p>东京是日本首都及最大城市，人口约1,400万（都市圈超过3,700万）。其他主要城市包括横滨、大阪、名古屋、札幌、福冈等。东京是全球最重要的金融、商业和文化中心之一。</p>
                
                <div class="image-grid">
                    <div class="image-card">
                        <img src="https://static.gltjp.com/glt/data/article/21000/20183/20220816_214717_58d15bee_w1280.webp" alt="东京">
                        <p>东京 - 日本首都</p>
                    </div>
                    <div class="image-card">
                        <img src="https://dts0r5oeqkedm.cloudfront.net/2019/12/osakastreet3.jpg" alt="大阪">
                        <p>大阪 - 商业中心</p>
                    </div>
                    <div class="image-card">
                        <img src="https://static.gltjp.com/glt/data/article/21000/20205/20221009_190037_c8c26069_w1280.webp" alt="京都">
                        <p>京都 - 古都</p>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- 文化标签内容 -->
        <div id="culture" class="tab-content">
            <h2>日本文化</h2>
            <p>日本文化融合了传统与现代元素，既保留了古老的习俗和艺术形式，又积极吸收外来文化并加以创新。</p>
            
            <div class="category">
                <h3>传统艺术</h3>
                <p>日本拥有丰富的传统艺术形式，包括：</p>
                <ul>
                    <li><strong>茶道(Chado)</strong>：一种以茶会友的仪式性活动，强调"和敬清寂"的精神</li>
                    <li><strong>花道(Ikebana)</strong>：插花艺术，追求自然与人工的和谐统一</li>
                    <li><strong>书道（Shodo)</strong>：书法艺术，被视为心灵修养的方式</li>
                    <li><strong>能剧(Noh)</strong>：日本传统戏剧，使用面具和缓慢优雅的动作</li>
                    <li><strong>歌舞伎(Kabuki)</strong>：色彩鲜艳、风格夸张的传统戏剧形式</li>
                </ul>
                
                <div class="image-grid">
                    <div class="image-card">
                        <img src="https://cdn.esence.travel/1-261.png" alt="茶道">
                        <p>茶道仪式</p>
                    </div>
                    <div class="image-card">
                        <img src="https://static.gltjp.com/glt/data/article/21000/20707/20240522_180105_ce5d9cea_w1280.webp" alt="歌舞伎">
                        <p>歌舞伎表演</p>
                    </div>
                    <div class="image-card">
                        <img src="https://www.yac8.com/upFiles/infoImg/201708/2017081169626457.jpg" alt="书道">
                        <p>书道作品</p>
                    </div>
                </div>
            </div>
            
            <div class="category">
                <h3>节日与庆典</h3>
                <p>日本有许多传统节日和庆典活动：</p>
                <ul>
                    <li><strong>元旦</strong>：最重要的节日，人们会在神社进行初次参拜【初詣（hatsumode）】</li>
                    <li><strong>成人节</strong>（每年1月第2个星期一）：庆祝年满20岁的青年成为成年人</li>
                    <li><strong>樱花节(Sakura Matsuri)</strong>（每年3-4月）：赏樱花的季节，各地举行赏樱活动</li>
                    <li><strong>盂兰盆节(Obon)</strong>（每年8月中旬）：祭祖的节日，人们会返乡扫墓</li>
                    <li><strong>七五三(Shichi-go-san)</strong>（每年11月15日）：为3岁、5岁男孩和3岁、7岁女孩祈福的节日</li>
                </ul>
                
                <div class="image-grid">
                    <div class="image-card">
                        <img src="https://static.gltjp.com/glt/data/article/21000/20632/20240225_112143_7dba81fc_w1280.webp" alt="樱花节">
                        <p>樱花节赏樱</p>
                    </div>
                    <div class="image-card">
                        <img src="https://jct.tcymca.org.tw/Archive/_tw/upload/%E6%97%A5%E6%9C%AC%E5%BE%A1%E7%9B%86%E7%AF%80.jpg" alt="盂兰盆节">
                        <p>盂兰盆节舞蹈</p>
                    </div>
                    <div class="image-card">
                        <img src="https://5b0988e595225.cdn.sohucs.com/images/20191030/9560367304a94004a9e1f54b57904fb4.jpeg" alt="七五三">
                        <p>七五三节日</p>
                    </div>
                </div>
            </div>
            
            <div class="category">
                <h3>现代流行文化</h3>
                <p>日本现代流行文化在全球有广泛影响：</p>
                <ul>
                    <li><strong>动漫</strong>：日本动画产业世界闻名，如宫崎骏作品、《海贼王》等</li>
                    <li><strong>漫画</strong>：日本独特的连环画形式，题材广泛</li>
                    <li><strong>J-POP</strong>：日本流行音乐，拥有众多偶像团体</li>
                    <li><strong>电子游戏</strong>：任天堂、索尼等公司开发的游戏全球畅销</li>
                    <li><strong>时尚</strong>：原宿风、洛丽塔等独特时尚风格</li>
                </ul>
            </div>
        </div>
        
        <!-- 景点标签内容 -->
        <div id="attractions" class="tab-content">
            <h2>日本著名景点</h2>
            <p>日本拥有众多自然和人文景观，从古老的寺庙到现代的建筑奇迹，从宁静的庭园到繁华的都市，应有尽有。</p>
            
            <div class="category">
                <h3>历史遗迹</h3>
                <div class="image-grid">
                    <div class="image-card">
                        <img src="https://www.japan-travel.cn/images/spot/1128/20201026_fushimi_inari_taisha_shrine_01.jpg" alt="京都伏见稻荷大社">
                        <p>京都伏见稻荷大社 - 著名的千本鸟居</p>
                    </div>
                    <div class="image-card">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTEWa7US0GZsZFPZpkBkVowmNiX-kG4jYkwOA&s" alt="奈良东大寺">
                        <p>奈良东大寺 - 世界最大木造寺庙</p>
                    </div>
                    <div class="image-card">
                        <img src="https://static.gltjp.com/glt/data/article/21000/20400/20240204_172217_a64e7ad1_w1280.webp" alt="姬路城">
                        <p>姬路城 - 日本国宝级城堡</p>
                    </div>
                </div>
            </div>
            
            <div class="category">
                <h3>自然景观</h3>
                <div class="image-grid">
                    <div class="image-card">
                        <img src="https://static.gltjp.com/glt/data/article/21000/20522/20231116_142745_b1cac14b_w1920.webp" alt="富士山">
                        <p>富士山 - 日本象征</p>
                    </div>
                    <div class="image-card">
                        <img src="https://cdn.zekkei-japan.jp/images/spots/058f0309d12531c6296608dcb05afe94.jpg" alt="岚山竹林">
                        <p>京都岚山竹林</p>
                    </div>
                    <div class="image-card">
                        <img src="https://static.gltjp.com/glt/data/article/21000/20486/20231019_135309_f5a176c0_w1920.webp" alt="白川乡合掌村">
                        <p>白川乡合掌村 - 世界文化遗产</p>
                    </div>
                </div>
            </div>
            
            <div class="category">
                <h3>现代建筑</h3>
                <div class="image-grid">
                    <div class="image-card">
                        <img src="https://static.gltjp.com/glt/data/article/21000/20461/20231008_103635_0b1ebde9_w1280.webp" alt="东京晴空塔">
                        <p>东京晴空塔 - 世界上最高的电波塔</p>
                    </div>
                    <div class="image-card">
                        <img src="https://static.gltjp.com/glt/data/directory/12000/11149/20200915_034037_f2657b39_w1920.webp" alt="国立新美术馆">
                        <p>国立新美术馆</p>
                    </div>
                    <div class="image-card">
                        <img src="https://www.sakuratxg.com.tw/upload/Admin/images/%E6%9D%B1%E4%BA%AC%E8%81%96%E7%91%AA%E5%88%A9%E4%BA%9E%E4%B8%BB%E6%95%99%E5%BA%A7%E5%A0%82.jpg" alt="东京圣玛利亚主教座堂">
                        <p>东京圣玛利亚主教座堂</p>
                    </div>
                </div>
            </div>
            
            <div class="category">
                <h3>购物与娱乐</h3>
                <div class="image-grid">
                    <div class="image-card">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/5/5b/Ginza-WAKO_at_night.jpg" alt="银座">
                        <p>东京银座 - 高级购物区</p>
                    </div>
                    <div class="image-card">
                        <img src="https://static.gltjp.com/glt/data/article/21000/20306/20230428_135347_ef98cf89_w1280.webp" alt="秋叶原">
                        <p>秋叶原 - 电器与动漫圣地</p>
                    </div>
                    <div class="image-card">
                        <img src="https://static.gltjp.com/glt/data/article/21000/20444/20230926_163707_4cdb3895_w1280.webp" alt="道顿堀">
                        <p>大阪道顿堀 - 美食之城</p>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- 美食标签内容 -->
        <div id="cuisine" class="tab-content">
            <h2>日本美食</h2>
            <p>日本料理以精致多样、讲究季节性食材与摆盘艺术而著称，而日本的饮食文化——“和食” (Washoku)，于2013年被联合国教科文组织列为世界非物质文化遗产。</p>
            
            <div class="food-item">
                <img src="https://static.gltjp.com/glt/data/article/11000/10053/20240701_175234_afcabe5c_w1280.webp" alt="寿司" class="food-img">
                <div class="food-desc">
                    <h4>寿司</h4>
                    <p>日本最具代表性的美食之一，由醋饭与寿司料（新鲜海鲜、肉类、鸡蛋等各种食材）组合而成。主要种类包括握寿司、卷寿司、押寿司等。</p>
                </div>
            </div>
            
            <div class="food-item">
                <img src="https://static.gltjp.com/glt/data/article/21000/20290/20230407_104053_6903e13a_w1280.webp" alt="拉面" class="food-img">
                <div class="food-desc">
                    <h4>拉面</h4>
                    <p>发源于中国，后在日本衍生出无数新种类的面食，主要由面条、汤底和配料组成。各地有不同特色，如札幌味噌拉面、博多豚骨拉面、东京酱油拉面等。</p>
                </div>
            </div>
            
            <div class="food-item">
                <img src="https://static.gltjp.com/glt/data/article/12000/11030/20240729_091436_0561435e_w1280.webp" alt="天妇罗" class="food-img">
                <div class="food-desc">
                    <h4>天妇罗</h4>
                    <p>将海鲜或蔬菜裹上面衣（主要由小麦粉和鸡蛋调制而成）后高温油炸而成的料理，外酥里嫩。通常搭配特制的天妇罗酱汁和萝卜泥食用。</p>
                </div>
            </div>
            
            <div class="food-item">
                <img src="https://imgcp.aacdn.jp/img-a/1440/auto/global-aaj-front/article/2018/02/5a8f6e39c44ba_5a8f6b0c44f19_1300439408.jpg" alt="和牛" class="food-img">
                <div class="food-desc">
                    <h4>和牛</h4>
                    <p>日本特有的优质牛肉，以神户牛、松阪牛和近江牛最为著名。大理石花纹般的脂肪分布使其口感极为柔嫩多汁，赋予肉类丰富的风味和入口即化的质地。</p>
                </div>
            </div>
            
            <div class="food-item">
                <img src="https://rimage.savorjapan.com/svj/image/discover_oishii_japan/1049/article_329636_w640z.jpg" alt="怀石料理" class="food-img">
                <div class="food-desc">
                    <h4>怀石料理</h4>
                    <p>「怀石料理」是指在「茶会」中饮用浓茶（即浓郁稠密的抹茶）前享用的日本高级传统料理，起源于茶道。它注重食材的时令、原味，以及摆盘和用餐礼仪的精致，追求「一汁三菜」的搭配，强调季节感和艺术美感。</p>
                </div>
            </div>
            
            <div class="food-item">
                <img src="https://cdn.shopify.com/s/files/1/0512/5429/6766/files/image9_480x480.jpg?v=1689936875" alt="抹茶甜点" class="food-img">
                <div class="food-desc">
                    <h4>日式甜点</h4>
                    <p>日本传统甜点(和菓子)造型精美，常与茶道搭配。常见的有大福、羊羹、铜锣烧等。抹茶口味的甜点如抹茶冰淇淋、抹茶蛋糕也广受欢迎。</p>
                </div>
            </div>
        </div>
        
        <footer>
            <p>© 2025 日本介绍网页 | 资料仅供参考 </p>
        </footer>
    </div>
    
    <script>
        function openTab(evt, tabName) {
            // 隐藏所有标签内容
            var tabContents = document.getElementsByClassName("tab-content");
            for (var i = 0; i < tabContents.length; i++) {
                tabContents[i].classList.remove("active");
            }
            
            // 移除所有按钮的active类
            var tabButtons = document.getElementsByClassName("tab-btn");
            for (var i = 0; i < tabButtons.length; i++) {
                tabButtons[i].classList.remove("active");
            }
            
            // 显示当前标签内容并激活按钮
            document.getElementById(tabName).classList.add("active");
            evt.currentTarget.classList.add("active");
        }
    </script>
</body>
</html>

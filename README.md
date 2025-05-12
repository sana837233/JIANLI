<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Z世代探索者 | 个人简介</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#4F46E5',
                        secondary: '#EC4899',
                        accent: '#10B981',
                        dark: '#1F2937',
                        light: '#F9FAFB'
                    },
                    fontFamily: {
                        inter: ['Inter', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    
    <style type="text/tailwindcss">
        @layer utilities {
            .content-auto {
                content-visibility: auto;
            }
            .text-shadow {
                text-shadow: 0 2px 4px rgba(0,0,0,0.1);
            }
            .hover-scale {
                transition: transform 0.3s ease;
            }
            .hover-scale:hover {
                transform: scale(1.03);
            }
            .animate-float {
                animation: float 6s ease-in-out infinite;
            }
            @keyframes float {
                0% { transform: translateY(0px); }
                50% { transform: translateY(-10px); }
                100% { transform: translateY(0px); }
            }
            .gradient-bg {
                background: linear-gradient(135deg, #4F46E5 0%, #8B5CF6 100%);
            }
        }
    </style>
</head>
<body class="bg-gray-50 font-inter text-dark min-h-screen flex items-center justify-center p-4 md:p-8">
    <!-- 个人简介卡片 -->
    <div class="max-w-4xl w-full bg-white rounded-2xl shadow-xl overflow-hidden hover-scale">
        <!-- 头部背景 -->
        <div class="relative gradient-bg h-48 md:h-64">
            <div class="absolute inset-0 bg-gradient-to-b from-primary/80 to-primary/40"></div>
            <div class="absolute bottom-0 left-0 w-full h-16 bg-gradient-to-t from-white to-transparent"></div>
            
            <!-- 个人信息 -->
            <div class="absolute bottom-0 left-0 w-full px-6 pb-6 flex flex-col md:flex-row items-center md:items-end gap-4">
                <!-- 头像 -->
                <!-- <div class="relative z-10 animate-float">
                    <div class="w-32 h-32 md:w-40 md:h-40 rounded-full overflow-hidden border-4 border-white shadow-lg">
                        <img src="https://picsum.photos/seed/chiikawa/400/400" alt="个人头像" class="w-full h-full object-cover">
                    </div>
                    <div class="absolute -bottom-2 -right-2 bg-accent text-white text-xs font-bold px-3 py-1 rounded-full shadow-lg">
                        ESTJ
                    </div>
                </div> -->
                
                <!-- 名字和标签 -->
                <div class="flex-1 text-center md:text-left">
                    <h1 class="text-[clamp(1.8rem,5vw,2.5rem)] font-bold text-white text-shadow mb-1">Z世代探索者</h1>
                    <p class="text-[clamp(1rem,3vw,1.2rem)] text-white/90 font-medium mb-3">边缘科技爱好者 | 播客控 | 终身学习者</p>
                    
                    <!-- 社交媒体链接 -->
                    <div class="flex justify-center md:justify-start gap-3">
                        <a href="#" class="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center text-white hover:bg-white/30 transition-all">
                            <i class="fa-brands fa-twitter"></i>
                        </a>
                        <a href="#" class="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center text-white hover:bg-white/30 transition-all">
                            <i class="fa-brands fa-github"></i>
                        </a>
                        <a href="#" class="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center text-white hover:bg-white/30 transition-all">
                            <i class="fa-brands fa-linkedin"></i>
                        </a>
                        <a href="#" class="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center text-white hover:bg-white/30 transition-all">
                            <i class="fa-brands fa-instagram"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- 主要内容 -->
        <div class="px-6 py-8">
            <!-- 关于我 -->
            <div class="mb-8">
                <h2 class="text-2xl font-bold text-dark mb-4 flex items-center">
                    <i class="fa-solid fa-user-circle text-primary mr-2"></i> 关于我
                </h2>
                <p class="text-gray-700 leading-relaxed mb-4">
                    兴趣爱好极其广泛、不愿被世俗裹挟的Z世代er，边缘科技or科幻迷，啃过扎克伯格冗长的访谈，每天的爱好是薅chatgpt的新点子。
                </p>
                <p class="text-gray-700 leading-relaxed mb-4">
                    相信耳朵才是心灵的窗户，英语播客+各种pop乐稳定我每日好心情；买书如山倒的同时也在努力抽丝，没有灵感就会钻到前人的文字里畅游。
                </p>
                <p class="text-gray-700 leading-relaxed">
                    感兴趣的领域会主动跨越专业鸿沟，会主动积累+分门别类知识库，打破认知差连接世界；mbti里的estj，朋友和团队里的快乐小太阳，积极的心理暗示永葆稳定内核；最后，绝不践行"刻板"生活，闲暇时间也会遨游互联网，感受各种社会情绪的浇灌...
                </p>
            </div>
            
            <!-- 兴趣爱好 -->
            <div class="mb-8">
                <h2 class="text-2xl font-bold text-dark mb-4 flex items-center">
                    <i class="fa-solid fa-star text-secondary mr-2"></i> 兴趣爱好
                </h2>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-3">
                    <div class="bg-gray-50 p-4 rounded-xl shadow-sm hover:shadow-md transition-shadow">
                        <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center mb-3">
                            <i class="fa-solid fa-microchip text-primary"></i>
                        </div>
                        <h3 class="font-semibold text-gray-800">边缘科技</h3>
                    </div>
                    <div class="bg-gray-50 p-4 rounded-xl shadow-sm hover:shadow-md transition-shadow">
                        <div class="w-10 h-10 rounded-full bg-secondary/10 flex items-center justify-center mb-3">
                            <i class="fa-solid fa-podcast text-secondary"></i>
                        </div>
                        <h3 class="font-semibold text-gray-800">英语播客</h3>
                    </div>
                    <div class="bg-gray-50 p-4 rounded-xl shadow-sm hover:shadow-md transition-shadow">
                        <div class="w-10 h-10 rounded-full bg-accent/10 flex items-center justify-center mb-3">
                            <i class="fa-solid fa-book text-accent"></i>
                        </div>
                        <h3 class="font-semibold text-gray-800">阅读</h3>
                    </div>
                    <div class="bg-gray-50 p-4 rounded-xl shadow-sm hover:shadow-md transition-shadow">
                        <div class="w-10 h-10 rounded-full bg-blue-100 flex items-center justify-center mb-3">
                            <i class="fa-solid fa-music text-blue-500"></i>
                        </div>
                        <h3 class="font-semibold text-gray-800">Pop音乐</h3>
                    </div>
                </div>
            </div>
            
            <!-- 技能标签 -->
            <div>
                <h2 class="text-2xl font-bold text-dark mb-4 flex items-center">
                    <i class="fa-solid fa-code text-primary mr-2"></i> 知识领域
                </h2>
                <div class="flex flex-wrap gap-2">
                    <span class="px-4 py-2 bg-primary/10 text-primary rounded-full text-sm font-medium">人工智能</span>
                    <span class="px-4 py-2 bg-secondary/10 text-secondary rounded-full text-sm font-medium">Web开发</span>
                    <span class="px-4 py-2 bg-accent/10 text-accent rounded-full text-sm font-medium">数据科学</span>
                    <span class="px-4 py-2 bg-blue-100 text-blue-600 rounded-full text-sm font-medium">认知科学</span>
                    <span class="px-4 py-2 bg-purple-100 text-purple-600 rounded-full text-sm font-medium">心理学</span>
                    <span class="px-4 py-2 bg-amber-100 text-amber-600 rounded-full text-sm font-medium">用户体验</span>
                    <span class="px-4 py-2 bg-emerald-100 text-emerald-600 rounded-full text-sm font-medium">机器学习</span>
                    <span class="px-4 py-2 bg-red-100 text-red-600 rounded-full text-sm font-medium">科幻文学</span>
                </div>
            </div>
        </div>
        
        <!-- 页脚 -->
        <div class="bg-gray-50 px-6 py-4 border-t border-gray-100">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-500 text-sm">
                    <i class="fa-solid fa-quote-left text-primary/30 mr-1"></i>
                    打破认知差，连接新世界
                    <i class="fa-solid fa-quote-right text-primary/30 ml-1"></i>
                </p>
                <div class="mt-3 md:mt-0">
                    <button class="bg-primary hover:bg-primary/90 text-white px-6 py-2 rounded-full shadow transition-all flex items-center">
                        <i class="fa-solid fa-paper-plane mr-2"></i> 感谢你看到这
                    </button>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
    

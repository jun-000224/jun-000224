<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OOO의 포트폴리오</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" />
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;700;900&display=swap');
        body {
            font-family: 'Noto Sans KR', sans-serif;
        }
        .skill-badge {
            margin: 4px;
            height: 28px;
        }
        .project-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .project-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 10px 25px -5px rgba(0,0,0,0.1), 0 10px 10px -5px rgba(0,0,0,0.04);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <div class="container mx-auto max-w-4xl p-4 sm:p-8">

        <header class="text-center py-12">
            <h1 class="text-5xl font-black mb-2">👋 안녕하세요, OOO입니다</h1>
            <p class="text-lg text-gray-600">문제를 구조화하고 계획적으로 실행하며, 과정을 문서화하는 풀스택 개발자입니다.</p>
        </header>

        <section class="bg-white p-6 rounded-xl shadow-md mb-12">
            <div class="flex justify-center items-center flex-wrap">
                <img class="skill-badge" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
                <img class="skill-badge" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
                <img class="skill-badge" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
                <img class="skill-badge" src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java"/>
                <img class="skill-badge" src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle"/>
                <img class="skill-badge" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
                <img class="skill-badge" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
            </div>
        </section>

        <section class="mb-12">
            <h2 class="text-3xl font-bold mb-6">💡 About Me</h2>
            <div class="bg-white p-8 rounded-xl shadow-md space-y-4 text-lg">
                <p>🧑‍💻 **주도적인 문제 해결:** 주어진 과제를 꼼꼼함과 계획성을 바탕으로 주도적으로 수행하며, 막히는 부분은 반드시 해결하고 넘어가는 성향을 가졌습니다.</p>
                <p>🏛️ **탄탄한 기본기:** 데이터베이스와 백엔드 로직부터 시작하여 사용자 중심의 프론트엔드 UI/UX까지, 풀스택 개발의 전 과정을 이해하고 구현하는 것을 지향합니다.</p>
                <p>🔄 **유연한 개발 경험:** 경매/역경매와 같이 복잡한 비즈니스 로직을 설계하고, 외부 결제 API를 연동하여 안전한 거래 시스템을 구축한 경험이 있습니다.</p>
                <p>📚 **성장 지향:** SQLD 자격증을 준비하며 데이터 처리 역량을 강화하고 있으며, 새로운 기술을 배우고 적용하는 데에 적극적입니다.</p>
            </div>
        </section>

        <section>
            <h2 class="text-3xl font-bold mb-6">🚀 Projects</h2>
            
            <div class="project-card bg-white rounded-xl shadow-md overflow-hidden flex flex-col md:flex-row">
                <div class="md:w-1/3">
                    <img src="./images/cross-auction-project.png" alt="Cross Auction 프로젝트" class="object-cover h-full w-full">
                </div>
                <div class="md:w-2/3 p-6 flex flex-col">
                    <h3 class="text-2xl font-bold">Cross Auction (개인 프로젝트)</h3>
                    <p class="text-sm text-gray-500 mb-4">2025.09.12 ~ 2025.09.19</p>
                    <p class="text-gray-700 mb-4 flex-grow">
                        일반 경매와 가격 하락형 역경매 시스템을 결합한 포인트 기반 중고 거래 플랫폼입니다. Vue.js를 이용한 동적인 프론트엔드와 Node.js 기반의 안정적인 백엔드 API를 구축하고, Oracle DB와 연동하여 전체 서비스를 구현했습니다.
                    </p>
                    <div class="mb-4">
                        <h4 class="font-bold text-md mb-2">✍️ 주요 역할 및 기여</h4>
                        <ul class="list-disc list-inside text-gray-600 text-sm space-y-1">
                            <li>일반 경매 및 가격 하락형 역경매 비즈니스 로직 설계 및 구현</li>
                            <li>포인트 기반의 안전 거래를 위한 에스크로 시스템 구축</li>
                            <li>PortOne(카카오페이) API를 연동한 포인트 충전 기능 구현</li>
                            <li>관리자 페이지에서 사용자 제재 및 신고 관리 기능 개발</li>
                            <li>Oracle DB 테이블 설계 및 데이터 관리</li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="font-bold text-md mb-2">🛠️ 사용 기술</h4>
                        <div class="flex flex-wrap">
                             <span class="bg-indigo-100 text-indigo-800 text-sm font-semibold mr-2 mb-2 px-2.5 py-0.5 rounded">Vue.js</span>
                             <span class="bg-sky-100 text-sky-800 text-sm font-semibold mr-2 mb-2 px-2.5 py-0.5 rounded">Node.js</span>
                             <span class="bg-red-100 text-red-800 text-sm font-semibold mr-2 mb-2 px-2.5 py-0.5 rounded">Oracle</span>
                             <span class="bg-yellow-100 text-yellow-800 text-sm font-semibold mr-2 mb-2 px-2.5 py-0.5 rounded">PortOne</span>
                             <span class="bg-gray-100 text-gray-800 text-sm font-semibold mr-2 mb-2 px-2.5 py-0.5 rounded">Git</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</body>
</html>

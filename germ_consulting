<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>김윤균의 자기소개서 프리미엄 퍼스널 컨설팅</title>
    <style>
        /* Noto Sans KR 폰트 가져오기 (웹폰트) */
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700&display=swap');

        body {
            font-family: 'Noto Sans KR', 'Malgun Gothic', sans-serif;
            margin: 0;
            padding: 30px 20px;
            background-color: #f8f9fa; 
            color: #343a40; 
            display: flex;
            flex-direction: column; 
            align-items: center;
            min-height: calc(100vh - 60px);
            box-sizing: border-box;
            line-height: 1.75; 
        }

        .container {
            background-color: #ffffff; 
            padding: 35px 45px; 
            border-radius: 8px; 
            box-shadow: 0 6px 18px rgba(0, 0, 0, 0.07); 
            width: 100%;
            max-width: 800px; /* 탭 인터페이스를 고려하여 너비 약간 증가 */
            text-align: left;
        }

        h1 { /* 사이트 전체 제목 */
            font-size: 2.1em; 
            font-weight: 700;
            color: #1a3a5a; 
            text-align: center;
            margin-top: 0; 
            margin-bottom: 30px;
            padding-bottom: 15px;
            border-bottom: 1px solid #dee2e6; 
        }

        /* --- Tab Interface Styles --- */
        .tab-buttons-container {
            display: flex;
            border-bottom: 2px solid #34568B; /* 탭 하단에 강조선 */
            margin-bottom: 25px;
        }

        .tab-button {
            flex-grow: 1; /* 버튼들이 공간을 균등하게 차지하도록 */
            padding: 12px 15px;
            cursor: pointer;
            border: 1px solid transparent; /* 기본 테두리 없음 */
            border-bottom: none; /* 하단 테두리는 컨테이너가 담당 */
            background-color: #f1f3f5; /* 비활성 탭 배경색 */
            color: #495057; /* 비활성 탭 텍스트색 */
            font-size: 1.05em; /* 탭 버튼 폰트 크기 */
            font-weight: 500;
            text-align: center;
            transition: background-color 0.3s ease, color 0.3s ease;
            border-radius: 6px 6px 0 0; /* 상단 모서리 둥글게 */
            margin-right: 5px; /* 탭 간 간격 */
        }
        .tab-button:last-child {
            margin-right: 0;
        }

        .tab-button:hover {
            background-color: #e9ecef;
        }

        .tab-button.active {
            background-color: #ffffff; /* 활성 탭 배경색 (컨테이너와 동일) */
            color: #34568B; /* 활성 탭 텍스트 색 (강조) */
            border-top: 1px solid #ced4da;
            border-left: 1px solid #ced4da;
            border-right: 1px solid #ced4da;
            position: relative;
            bottom: -2px; /* 탭 하단 강조선과 겹치도록 */
            border-bottom: 2px solid #ffffff; /* 활성 탭 하단은 배경색으로 덮어 연결된 느낌 */
            font-weight: 700;
        }

        .tab-content {
            display: none; /* 기본적으로 모든 탭 내용 숨김 */
            padding: 20px 10px; /* 탭 내용 패딩 */
            animation: fadeIn 0.5s; /* 부드러운 나타남 효과 */
        }

        .tab-content.active {
            display: block; /* 활성 탭 내용만 보여줌 */
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        /* 내용 안의 제목 및 문단 스타일 (탭 콘텐츠 내부용) */
        .tab-content h3 { 
            font-size: 1.5em; 
            font-weight: 700; 
            color: #34568B; 
            margin-top: 10px; 
            margin-bottom: 20px;
            padding-bottom: 8px;
            border-bottom: 1px solid #e0e0e0; 
        }
        
        .tab-content .promo-article > h3:first-of-type { /* 아티클의 메인 제목 */
            font-size: 1.6em; 
            text-align:center;
            border-bottom-style: dashed;
        }

        /* 철학 섹션의 소제목들 */
        .philosophy-section h4 {
            font-size: 1.25em; 
            font-weight: 500;
            color: #2c3e50; 
            margin-top: 25px;
            margin-bottom: 15px;
        }
        
        .promo-article .sub-headline { 
            font-size: 1.15em;
            font-weight: 400;
            color: #495057;
            text-align: center;
            margin-top: -5px; 
            margin-bottom: 25px;
            line-height: 1.6;
        }
        
        .promo-article h4 { /* 아티클 내 항목 제목 */
             font-size: 1.3em; 
             font-weight: 500; 
             color: #34568B; 
             padding-bottom: 5px;
             margin-top: 30px;
             border-bottom: 1px dotted #adb5bd;
        }

        .tab-content p {
            font-size: 1em; 
            color: #343a40;
            padding: 0;
            margin-bottom: 1.4em; 
            line-height: 1.8; 
        }

        .tab-content strong { 
            font-weight: 700;
            color: #005A9C; 
        }
        
        .promo-article .conclusion {
            margin-top: 35px;
            padding: 20px 25px;
            background-color: #f1f3f5;
            border-radius: 6px; 
        }

        .promo-article .conclusion p {
            margin-bottom: 0.8em;
            font-size: 1.05em; 
        }
        
        .contact-section p {
            margin-bottom: 12px;
        }

        .contact-section a {
            color: #005A9C; 
            text-decoration: none;
            font-weight: 500;
        }

        .contact-section a:hover,
        .contact-section a:focus {
            text-decoration: underline;
            color: #003d6b;
        }

    </style>
</head>
<body>
    <div class="container">
        <h1>김윤균의 자기소개서 프리미엄 퍼스널 컨설팅</h1>

        <div class="tab-interface">
            <div class="tab-buttons-container">
                <button type="button" class="tab-button active" data-tab="#philosophyTab">김윤균의 컨설팅 철학</button> <button type="button" class="tab-button" data-tab="#articleTab">서비스 제공 세부 내용</button> <button type="button" class="tab-button" data-tab="#contactTab">연락 및 문의</button>
            </div>

            <div class="tab-content-panels">
                <div id="philosophyTab" class="tab-content active">
                    <div class="philosophy-section">
                        <p>자, 아직도 취업 컨설팅 업체에서 나눠주는 '자소서 만능 템플릿' 붙들고 씨름하고 계십니까? 친구 따라 이른바 '합격 공식'이라는 거 베껴 쓰고 있나요? 아니면 해피캠퍼스나 이런저런 취업 카페에서 '합격 자소서'랍시고 돌아다니는 남의 글들 교묘하게 짜깁기해서 '나만의 것'이라고 착각하고 있습니까? 그렇게 해서 수백, 수천 명의 복제품 중 하나가 될 바에야 차라리 안 내는 게 낫습니다. 인사 담당자가 바보인 줄 아십니까? 그런 어설픈 '붕어빵 자소서', 광속으로 걸러냅니다.</p>
                        <p><strong>김윤균의 첨삭 철학은 그런 '양산형 스펙' 만들기와는 차원이 다릅니다. 우리의 핵심은 단 두 가지, 바로 '초정밀 개인 맞춤 전략'과 '독하다 싶을 정도의 집요한 꼼꼼함'입니다.</strong></p>
                        
                        <h4>당신은 '데이터 샘플'이 아닙니다 – 100% 당신만을 위한 퍼스널 전략을 설계합니다.</h4>
                        <p>우리는 천편일률적인 조언이나 누구나 할 수 있는 '일반론' 따위는 거들떠보지도 않습니다. 당신의 아주 사소한 경험, 남들이 보기엔 별것 아닌 것 같은 특징 속에서 당신만의 '결정적 한 방'을 찾아냅니다. 당신의 모든 것을 현미경으로 들여다보듯 분석하여, 오직 당신만이 가진 고유한 강점과 스토리를 발굴하고, 이를 지원하는 기업과 직무에 칼같이 맞춰 '승리하는 전략'을 일대일로, 바닥부터 설계합니다. A에게 통했던 방법이 당신에게도 통할 거라는 안일함, 김윤균에게는 사치일 뿐입니다.</p>
                        
                        <h4>'대충', '적당히'는 없습니다 – 마침표 하나, 단어 하나까지 완벽을 추구합니다.</h4>
                        <p>자소서의 성패는 때로 아주 작은 디테일에서 갈립니다. 우리는 '이 정도면 되겠지'라는 자기만족이나 타협을 용납하지 않습니다. 당신의 자소서에 담긴 모든 문장, 모든 단어, 심지어 보이지 않는 논리의 흐름과 문맥의 적절성까지, 그야말로 '징하다' 싶을 정도로 수십, 수백 번을 검토하고 다듬습니다. 기업 문화와의 적합성, 당신의 진정성이 행간에 제대로 녹아 있는지, 다른 첨삭 서비스에서는 절대 신경 쓰지 못할 영역까지 집요하게 파고듭니다. 그들이 놓치는 1mm의 차이, 우리는 그것을 찾아내 합격과 불합격의 경계를 뒤집습니다.</p>
                    </div>
                </div>

                <div id="articleTab" class="tab-content">
                    <article class="promo-article">
                        <h3>당신의 자소서, 언제까지 ‘감성 소설’에 머무를 것인가?</h3> <p class="sub-headline">김윤균의 프리미엄 퍼스널 컨설팅, '합격하는 전략'으로 서류 통과의 공식을 새로 쓰다.</p>

                        <p>수많은 자기소개서가 오늘도 불합격 통보를 받습니다. 안타깝지만, 대부분의 지원자는 무엇이 문제인지조차 제대로 파악하지 못한 채, A업체, B업체 같은 곳을 전전하며 밑 빠진 독에 물 붓듯 시간과 비용을 낭비하고 있습니다. 그저 그런 ‘문장 다듬기’와 ‘미사여구 추가’만으로는 절대 합격의 문턱을 넘을 수 없습니다.</p>
                        <p>이제, ‘김윤균의 자기소개서 프리미엄 퍼스널 컨설팅’가 왜 단순한 첨삭을 넘어선 ‘합격 전략 컨설팅’인지, 그 압도적인 차이를 명확히 보여드리겠습니다.</p>

                        <h4>1. '문장 교정'을 넘어선 '합격 논리'의 재구축</h4>
                        <p>대부분의 자소서 첨삭 서비스는 당신의 경험을 그럴싸한 단어로 포장하거나, 감성적인 문구로 현혹하는 데 그칩니다. 하지만 인사 담당자는 문학 평론가가 아닙니다. 그들은 당신의 ‘글솜씨’가 아니라, 당신이 제시하는 ‘논리적 근거’와 ‘데이터’를 통해 직무 적합성을 판단합니다.</p>
                        <p><strong>김윤균의 접근법은 근본부터 다릅니다.</strong> 우리는 당신의 경험을 단순 나열하는 ‘자소설’이 아닌, 채용 담당자를 설득하는 ‘전략 보고서’로 재탄생시킵니다. 모든 경험을 철저히 분석하여 객관적인 성과와 데이터를 추출하고, 이를 바탕으로 ‘왜 당신이어야 하는가’에 대한 강력하고 논리적인 주장을 구축합니다. 당신의 이야기가 단순한 ‘경험담’이 아닌, ‘합격을 부르는 증거’가 되도록 만듭니다.</p>

                        <h4>2. '듣기 좋은 조언'이 아닌 '성장을 이끄는 정밀 진단'</h4>
                        <p>마음 상할까 두려워 핵심을 비껴가는 피드백, "이 정도면 괜찮아요" 식의 무책임한 위로는 당신의 발전에 하등 도움이 되지 않습니다. 그런 서비스는 당신의 불안감을 잠시 해소할 수는 있겠지만, 합격이라는 실질적인 결과는 가져다주지 못합니다.</p>
                        <p><strong>김윤균의 첨삭은 ‘팩트 폭격’이라 불릴 만큼 정직하고 날카롭습니다.</strong> 우리는 당신의 자소서에 담긴 모든 논리적 허점, 근거 없는 주장, 직무 이해도 부족 등을 가차 없이 지적합니다. 왜냐고요? 고통스럽더라도 진짜 문제를 직시해야만 근본적인 개선과 실질적인 성장이 가능하기 때문입니다. 우리는 듣기 좋은 위로 대신, 당신의 합격 가능성을 현실적으로 끌어올리는 ‘정밀 진단’과 ‘명쾌한 해법’을 제시합니다.</p>

                        <h4>3. '나만의 이야기'를 '기업이 원하는 인재상'으로 정교하게 매칭</h4>
                        <p>자신이 하고 싶은 말만 늘어놓는 자소서는 일기장에 불과합니다. 합격하는 자소서는 지원하는 기업과 직무가 무엇을 원하는지 정확히 파악하고, 자신의 강점과 경험을 그에 맞춰 전략적으로 제시해야 합니다. 단순히 ‘잘 쓴 글’을 만드는 것을 넘어선 통찰이 필요합니다.</p>
                        <p><strong>김윤균은 당신의 모든 경험과 역량을 ‘채용자의 관점’에서 재해석하고,</strong> 지원 기업의 인재상 및 직무 핵심 역량과 완벽하게 ‘매칭’시킵니다. 이는 단순한 글쓰기 지도가 아닙니다. 당신이라는 ‘인재’를 해당 기업에 가장 매력적으로 어필할 수 있도록 최적화하는 ‘퍼스널 브랜딩 전략’이자, ‘합격 지향적 컨설팅’입니다.</p>

                        <h4>4. '표면적 수정'이 아닌 '경쟁력을 극대화하는 근본적 혁신'</h4>
                        <p>문장 몇 개 고치고, 표현을 다듬는 ‘땜질식 처방’으로는 결코 경쟁자들을 앞설 수 없습니다. 자소서의 진정한 문제는 글솜씨가 아니라, 그 안에 담긴 생각의 깊이와 논리의 구조이기 때문입니다.</p>
                        <p><strong>김윤균의 서비스는 ‘완전 재건축’을 지향합니다.</strong> 당신의 경험, 생각, 가치관을 심층적으로 분석하여, ‘합격’이라는 목표에 가장 부합하는 방식으로 당신의 커리어 스토리 전체를 새롭게 디자인합니다. 이 과정에서 당신은 스스로도 인지하지 못했던 잠재력과 논리를 발견하며, 취업 경쟁력 자체를 근본부터 혁신하게 될 것입니다.</p>

                        <div class="conclusion">
                            <p>이제 선택은 당신의 몫입니다.</p>
                            <p>계속해서 의미 없는 ‘자소설’에 당신의 소중한 시간과 노력을 허비하시겠습니까? 아니면 ‘김윤균의 자기소개서 프리미엄 퍼스널 컨설팅’을 통해 당신의 진짜 가치를 증명하고, 꿈에 그리던 기업의 합격 통지서를 쟁취하시겠습니까?</p>
                            <p><strong>더 이상 망설이지 마십시오. 압도적인 결과로 당신의 선택이 옳았음을 증명해 보이겠습니다.</strong></p>
                        </div>
                    </article>
                </div>

                <div id="contactTab" class="tab-content">
                    <div class="contact-section">
                        <h3>연락 및 문의</h3> 
                        <p>서비스 관련 문의는 아래 이메일 또는 카카오톡 상담방을 통해 연락주시면 신속하게 답변드리겠습니다.</p>
                        <p><strong>이메일:</strong> your_email@example.com (실제 이메일 주소로 변경하세요)</p>
                        <p><strong>카카오톡 상담방:</strong> <a href="https://open.kakao.com/o/smXa78wh" target="_blank" rel="noopener noreferrer">김윤균의 첨삭 상담방</a></p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        const tabButtons = document.querySelectorAll('.tab-button');
        const tabContents = document.querySelectorAll('.tab-content');

        // 기본적으로 첫 번째 탭을 활성화 상태로 만듭니다.
        if (tabButtons.length > 0) {
            tabButtons[0].classList.add('active');
            document.querySelector(tabButtons[0].getAttribute('data-tab')).classList.add('active');
        }

        tabButtons.forEach(button => {
            button.addEventListener('click', () => {
                const targetTabId = button.getAttribute('data-tab');

                tabButtons.forEach(btn => btn.classList.remove('active'));
                tabContents.forEach(content => content.classList.remove('active'));

                button.classList.add('active');
                document.querySelector(targetTabId).classList.add('active');
            });
        });
    </script>

</body>
</html>

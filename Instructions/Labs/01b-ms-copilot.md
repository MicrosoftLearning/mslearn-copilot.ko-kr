---
lab:
  title: Microsoft Edge의 Copilot 살펴보기
---
# Microsoft Edge의 Microsoft Copilot 살펴보기

Microsoft Copilot의 흥미로운 세계에 오신 것을 환영합니다!

이 연습에서는 Copilot의 힘을 활용하여 회사 청소 기업을 시작하기 위한 새로운 비즈니스 아이디어를 살펴봅니다.

어디서나 사무실 공간에 혁명을 일으킬 최고 수준의 청소 서비스를 시작하려는 상황이라고 상상해 보십시오. Microsoft Copilot을 통해 시장 추세를 연구하고 견고한 비즈니스 플랜을 개발할 수 있습니다. 그것이 전부가 아닙니다. 또한 흥미로운 문서, 눈길을 끄는 프레젠테이션, 설득력 있는 이메일을 만들어 아이디어를 얻고 투자자를 유치할 수 있습니다.

이 매력적인 대화형 랩을 통해 탐색해 나가며 창의력과 비즈니스 통찰력을 발휘할 준비를 할 수 있습니다. 이 연습이 끝나면 기업가적 성공의 길을 열어줄 포괄적인 자료 세트를 갖추게 됩니다. 회사 청소 기업을 현실로 만들어 보겠습니다!

이 연습을 완료하는 데 약 **40**분 정도 소요됩니다.

> **참고**: 이 연습에서는 컴퓨터에서 [Microsoft Edge](https://www.microsoft.com/edge/download)에 로그인하는 데 사용되는 [개인 Microsoft 계정](https://signup.live.com)(예: outlook.com 계정)이 있다고 가정합니다. 회사 계정과 개인 계정이 모두 있는 경우 Microsoft Edge의 왼쪽 위에 있는 계정 설정에서 *개인* 계정을 선택해야 합니다.

## Copilot을 사용하여 문서 탐색 및 아이디어 조사

생성형 AI 탐색을 시작하려면 Edge에서 Microsoft Copilot을 사용하여 기존 문서를 검사하고 여기에서 몇 가지 인사이트를 추출해 보겠습니다.

1. Microsoft Edge에서 `https://onedrive.live.com`의 [OneDrive](https://onedrive.live.com)로 이동하여 개인 Microsoft 계정을 사용하여 로그인합니다. 표시된 환영 메시지나 제안을 닫습니다.
1. 다른 브라우저 탭에서 `https://github.com/MicrosoftLearning/mslearn-copilot/raw/main/Allfiles/Business%20Idea.docx`의 [Business Idea.docx](https://github.com/MicrosoftLearning/mslearn-copilot/raw/main/Allfiles/Business%20Idea.docx) 문서를 엽니다. 그런 다음 Edge에서 문서가 열리면 **복사본 편집** 옵션을 선택하여 문서를 OneDrive에 복사합니다. 그러면 문서가 Microsoft Word 온라인에서 자동으로 열립니다.

    > **팁**: 복사본 편집 옵션이 표시되지 않으면 해당 파일을 로컬 컴퓨터에 다운로드합니다. 그런 다음 OneDrive에서 **+ 새로 추가** 단추를 사용하여 로컬 컴퓨터의 **Business Idea.docx** 파일을 OneDrive에 업로드합니다.

1. 뉴욕시의 청소 비즈니스에 대한 몇 가지 고급 아이디어를 설명하는 **Business Idea** 문서의 텍스트를 확인합니다.
1. 다음과 같이 Edge 도구 모음의 **Copilot** 아이콘을 사용하여 Copilot 창을 엽니다.

    ![Microsoft Edge의 Copilot 창 스크린샷.](./Media/edge-copilot.png)

1. Copilot 창 하단에 있는 채팅 상자에 다음 프롬프트를 입력합니다.

    ```prompt
    Summarize this document into 5 key points, and suggest next steps.
    ```

    메시지가 표시되면 Copilot이 페이지에 액세스하도록 허용할지 확인합니다.

1. Copilot의 응답이 문서의 주요 사항을 요약하고 다음과 같이 수행할 몇 가지 후속 작업을 제안하고 있는지 검토합니다.

    ![응답이 포함된 Copilot 창의 스크린샷.](./Media/copilot-response.png)

    > **참고**: 구체적인 응답은 다를 수 있습니다.

    Copilot으로 몇 가지 유용한 지침을 얻게 되었길 바랍니다. 추가 질문이 있는 경우, 더 구체적인 정보를 요청할 수 있습니다.

1. 다음 프롬프트를 입력합니다.

    ```prompt
    How do I go about setting up a business in New York?
    ```

1. 응답에 뉴욕에서 비즈니스를 시작하는 데 도움이 되는 조언과 리소스 링크가 포함되어 있는지 검토합니다.

    > **중요**: AI가 생성한 응답은 웹에 공개된 정보를 기반으로 합니다. 사업체를 설립하는 데 필요한 단계를 이해하는 데 도움이 될 수 있지만 100% 정확하다고 보장할 수 없으며 전문적인 조언의 필요성을 바꿀 수는 없습니다!

## Copilot을 사용하여 사업 계획용 콘텐츠 만들기

이제 몇 가지 초기 조사를 완료했으므로 Copilot을 통해 청소 회사를 위한 사업 계획을 작성해 보겠습니다.

1. Microsoft Edge에 **Business Idea.docx** 문서가 열려 있는 상태에서 Copilot 창에 다음 프롬프트를 입력합니다.

    ```prompt
    Suggest a name for my cleaning business.
    ```

1. 제안 사항을 검토하고 청소 회사의 이름을 선택해 줘(그렇지 않으면 원하는 회사 이름을 찾으라는 제안 메시지를 계속 표시해 줘). 회사 이름을 선택한 경우, Copilot에게 이름을 알려 줍니다.예: `Let's go with the first one.` 입력.
1. 기본 브라우저 페이지에서 **Business Idea** 문서가 계속 열려 있는지 확인하고 다음 프롬프트를 입력합니다.

    ```prompt
    Based on the contents of this document, create a business plan for my cleaning business.
    ```

1. 응답을 검토합니다. 그런 다음 Microsoft Word 창의 **파일** 메뉴에서 새 빈 문서를 만듭니다. **Designer** 창이 열리면 창을 닫고 새 문서의 이름을 *문서*에서 `Business Plan`로 변경합니다.
1. Copilot 창에서 생성된 비즈니스 플랜을 복사하여 비즈니스 플랜 문서에 붙여넣습니다.

    ![Copilot이 생성한 사업 계획이 포함된 Word 문서의 스크린샷.](./Media/generated-content.png)

1. Copilot 창에서 다음 프롬프트를 입력합니다.

    ```prompt
    Create a corporate logo for the cleaning company. The logo should be round and include an iconic New York landmark.
    ```

1. Copilot이 생성한 이미지를 검토합니다.

1. 만족스러운 로고가 나올 때까지 더 많은 프롬프트를 사용하여 디자인(예: `Make it green and blue`)을 반복합니다.

    > **팁**: Coplot에서 텍스트가 포함된 이미지를 생성하면 일부 맞춤법 오류가 발생할 수 있습니다. 결과에 만족할 때까지 다른 프롬프트를 시도합니다.

1. 생성된 로고를 마우스 오른쪽 단추로 클릭하여 클립보드에 복사합니다. 그리고 다음과 같이 사업 계획 문서 상단에 붙여넣습니다.

    ![Copilot에서 생성된 이미지가 포함된 Word 문서의 스크린샷.](./Media/generated-image.png)

1. Microsoft Word 브라우저 탭을 닫고 OneDrive로 돌아갑니다.

## Copilot를 사용하여 재무 계획 생성 및 시각화

Copilot의 도움으로 청소 사업 아이디어에 대한 사업 계획 초안을 작성했습니다. 이제 Copilot를 사용하여 비즈니스 플랜을 더욱 구체화하는 데 도움이 되는 몇 가지 계산을 수행해 보겠습니다.

1. OneDrive에서 **(+)** 단추를 사용하여 새 **Excel 통합 문서**를 추가합니다. 그런 다음 통합 문서의 이름을 `Financial Projections`로 변경합니다.
1. Copilot 창에서 다음 프롬프트를 입력합니다.

    ```prompt
    Create a table of projected profits for the next 5 years, starting with this year. The profit this year should be $10,000 and it should increase by 12% each year.
    ```

1. 응답이 향후 5년 동안 예상되는 수익 테이블을 포함하는지 검토합니다.
1. 테이블을 클립보드에 복사합니다(테이블만 선택하도록 주의). 그런 다음 Excel 통합 문서에서 셀 A1을 선택하고 **홈** 탭의 **클립보드** 메뉴에 있는 **선택하여 붙여넣기**에서 **값만**을 선택하여 테이블의 값을 다음과 같이 스프레드시트에 붙여넣습니다.

    ![Copilot에서 생성된 데이터가 있는 Excel 통합 문서의 스크린샷.](./Media/generated-financials.png)

1. Copilot 창에서 다음 프롬프트를 입력합니다.

    ```prompt
    What's a good way to visualize these projections in a chart?
    ```

1. 응답이 예측 데이터를 시각화하는 몇 가지 방법을 권장하고 있는지 검토합니다. 그리고 다음 프롬프트를 입력합니다.

    ```prompt
    How do I create a line chart in Excel?
    ```

1. Copilot이 제공한 지침에 따라 꺾은선형 차트를 만듭니다.

    > **팁**: Excel에서 선택한 기본 데이터 축을 조정해야 할 수 있습니다. 스프레드시트에서 차트를 선택하고 **차트** 탭에서 **데이터 선택**을 선택합니다. 그런 다음 **Chart** 창의 **데이터** 탭에서 **Year** 필드가 가로 레이블이고 **Projected Profit** 필드만 꺾은선형 값으로 사용되도록 설정을 수정합니다.

    ![꺾은선형 차트가 있는 Excel 통합 문서의 스크린샷.](./Media/line-chart.png)

1. **차트** 탭을 닫아 스프레드시트의 차트를 확인합니다.

1. Microsoft Excel 브라우저 탭을 닫고 OneDrive로 돌아갑니다.

## Copilot을 사용하여 프레젠테이션용 콘텐츠 만들기

Copilot을 사용하여 청소 비즈니스를 위한 비즈니스 플랜을 세우고 몇 가지 재무 계획을 생성했습니다. 이제 투자자가 사업을 시작하기 위한 자금을 빌려줄 수 있도록 설득하려면 효과적인 프레젠테이션이 필요합니다.

1. OneDrive에 새 **PowerPoint 프리젠테이션**을 추가합니다. **디자이너** 창이 자동으로 열리면 닫습니다. 그런 다음 프레젠테이션의 이름을 *프레젠테이션*에서 `Business Presentation`로 변경합니다.

1. 프레젠테이션 제목 슬라이드의 제목에 청소 회사 이름을 입력하고 자막에 `Investor Opportunity`를 입력합니다.
1. **두 개의 콘텐츠** 슬라이드 레이아웃(제목과 콘텐츠에 대한 두 개의 자리 표시자 포함)을 사용하여 새 슬라이드를 추가합니다.
1. 슬라이드 제목을 `Benefits of Hiring a Commercial Cleaner`로 변경합니다.
1. Copilot 창에서 다음 프롬프트를 입력합니다.

    ```prompt
    Write a summary of the benefits of using a corporate cleaning company for your business. The summary should consist of five short bullet points.
    ```

1. Copilot의 응답을 클립보드에 복사하고 왼쪽 콘텐츠 자리 표시자에 붙여넣습니다. 그런 다음, 만족할 때까지 자리 표시자의 텍스트를 편집하고 서식을 다시 지정합니다.
1. Copilot 창에서 다음 프롬프트를 입력합니다.

    ```prompt
    Create a photorealistic image of a clean office.
    ```

1. Copilot에서 원하는 이미지를 생성하면 이를 클립보드에 복사하고 슬라이드 오른쪽에 있는 콘텐츠 자리 표시자에 붙여넣습니다.

    **디자이너** 창이 자동으로 열리면 원하는 슬라이드 디자인을 선택합니다. 그런 다음 **디자이너** 창을 닫습니다.

1. 다음과 유사한 슬라이드가 나올 때까지 필요하다고 생각되는 추가 서식 변경을 적용합니다.

    ![Copilot에서 생성된 콘텐츠가 포함된 PowerPoint 프레젠테이션의 스크린샷.](./Media/powerpoint-slide.png)

1. 새 브라우저 탭을 열고 이 탭을 사용하여 [mopping.png](https://github.com/MicrosoftLearning/mslearn-copilot/raw/main/Allfiles/mopping.png) 이미지를 `https://github.com/MicrosoftLearning/mslearn-copilot/raw/main/Allfiles/mopping.png`에서 로컬 컴퓨터로 다운로드하여 폴더에 저장합니다.
1. PowerPoint 프레젠테이션이 포함된 브라우저 탭으로 돌아가 Copilot 창에서 채팅 상자 옆의 **+** 단추를 사용하여 **mopping.png** 이미지를 Copilot에 업로드하고 `What does this image show?` 프롬프트를 추가합니다.
1. 응답이 다음과 유사한지 검토합니다.

    ![이미지에 대한 Copilot 설명을 보여주는 스크린샷.](./Media/copilot-image-analysis.png)

1. 다음 프롬프트를 사용하여 후속 작업을 수행하고 응답을 검토합니다.

    ```prompt
    Would this image be helpful to promote a commercial cleaning business?
    ```

    Copilot은 이미지를 분석하고 동료의 의견을 묻는 것과 같은 방식으로 특정 비즈니스 시나리오에 대한 유용성을 평가했습니다.

1. PowerPoint에서 이전과 동일한 **두 개의 콘텐츠** 레이아웃으로 새 슬라이드를 추가합니다. 그런 다음 콘텐츠 자리 표시자 중 하나에서 **mopping.png** 이미지를 업로드하여 슬라이드에 추가합니다.

1. Copilot 창에서 다음 프롬프트를 입력합니다.

    ```prompt
    Write a short paragraph to accompany this image, emphasizing the professionalism of the cleaning staff we employ.
    ```

1. 결과 텍스트를 검토한 다음 슬라이드의 빈 콘텐츠 자리 표시자에 복사하여 필요에 따라 편집하고 서식을 지정합니다.
1. Copilot 창에서 다음 프롬프트를 입력합니다.

    ```prompt
    Suggest a good title for a slide that contains the image and text.
    ```

1. 슬라이드에 제안된 제목을 사용한 다음 PowerPoint의 디자이너를 사용하여 슬라이드의 서식을 지정합니다. 다음과 유사한 슬라이드가 표시됩니다.

    ![Copilot의 제안을 사용하여 만든 슬라이드의 스크린샷.](./Media/powerpoint-new-slide.png)

1. PowerPoint 탭을 닫고 OneDrive로 돌아갑니다.

## Copilot을 사용하여 자금 조달 회의 주선

비즈니스를 시작하는 데 도움이 되는 몇 가지 참고 자료를 만들었습니다. 이제 스타트업 자금을 제공하려는 투자자에게 연락할 시간입니다.

1. OneDrive 제목 표시줄 왼쪽 세로면에 있는 **앱 시작 관리자**(&#8759;)를 사용하여 **Outlook**을 엽니다.
1. **일정** 페이지로 전환하고 보기를 **작업 주**로 변경합니다. 일정에 예약된 이벤트가 아직 없는 경우 Copilot이 작업할 정보를 확보하도록 몇 가지 내용을 추가할 수 있습니다.
1. Copilot 창에서 다음 프롬프트를 입력합니다.

    ```prompt
    What events do I have scheduled in this calendar?
    ```
    
    Copilot은 웹 페이지에서 일정을 읽고 일정에서 이벤트를 식별할 수 있어야 합니다.

    ![이벤트를 식별하는 Copilot이 있는 Outlook 일정의 스크린샷.](./Media/calendar-events.png)

1. 이 프롬프트를 사용하여 비즈니스에 대한 자금 조달을 요청할 은행 관리자와의 회의에 참여할 수 있을지 확인합니다.

    ```prompt
    What's my availability for a meeting this week?
    ```

    Copilot은 Outlook 웹 페이지의 일정 정보를 기반으로 가용성에 대한 요약을 제공합니다.

    > **참고**: Microsoft Copilot는 브라우저에서 열려 있는 일정 페이지를 읽을 수 있지만(현재 세션 중에 세부 정보를 "기억"할 수 있음) 일정 데이터에 직접 액세스할 수는 없습니다. 기업 환경에서 조직은 Outlook의 일정 및 이메일뿐만 아니라 Microsoft Teams와 같은 다른 엔터프라이즈 앱의 정보에 액세스할 수 *있는* Microsoft 365 Copilot을 사용할 수 있습니다.

1. **메일** 페이지로 전환하고 새 이메일을 만듭니다. **받는 사람** 상자에 자신의 이메일 주소를 입력하고 **제목**을 `Business funding meeting request`로 설정합니다.
1. Copilot 창에서 다음 프롬프트를 입력합니다.

    ```prompt
    Write an email to a bank manager requesting a meeting to discuss funding for a commercial cleaning business. The email should be concise and the tone should be professional.
    ```
    
1. 생성된 콘텐츠를 사용하여 여기에 표시된 대로 이메일을 완료합니다.

    ![Copilot에서 생성된 이메일 메시지의 스크린샷.](./Media/generated-email.png)

    원하는 경우 이메일을 자신에게 보내도 됩니다.

## 과제

이제 Copilot을 사용하여 아이디어를 조사하고 콘텐츠를 생성하는 방법을 살펴보았습니다. 더 자세히 살펴보겠습니다. 새 Copilot 세션을 시작하려면 채팅 상자 옆의 **+** 메뉴에서 **새 채팅 시작**을 선택합니다. 그런 다음, 이 연습에서 배운 내용에 따라 Copilot을 사용하여 조직에서 생성형 AI를 채택하도록 제안할 회의를 계획해 봅니다. 다음은 이러한 공간을 만들기 위한 몇 가지 아이디어입니다.

- 생성형 AI 및 Microsoft Copilot이 비즈니스에 제공하는 이점을 조사하여 생산성에 있어서의 이점, 비용 절감, 이미 AI를 성공적으로 채택한 조직의 사례에 대한 정보를 찾습니다.
- 모임 전에 사전 참조 자료로 돌릴 수 있는 토론 문서를 만듭니다.
- 피치의 핵심 요소를 강조하는 데이터 및 시각화를 포함하여 사례를 발표하는 데 사용할 수 있는 프레젠테이션을 만듭니다.
- 동료에게 모임에 대해 알리고 모임에 대한 컨텍스트를 제공하기 위한 이메일을 작성합니다.

원하는 만큼 창의력을 발휘하여, Copilot이 정보 검색, 텍스트 생성 및 구체화, 이미지 만들기, 질문 답변을 통해 어떻게 도움을 줄 수 있는지 알아봅니다.

## 결론

이 연습에서는 Microsoft Edge의 Copilot을 사용하여 정보를 찾고 콘텐츠를 생성했습니다. Copilot에서 생성형 AI를 사용하는 것이 생산성과 창의성에 어떻게 도움이 될 수 있는지 확인했기를 바랍니다.

이 연습에 사용된 무료 서비스는 의심의 여지 없이 매우 강력하지만, Microsoft Copilot이 Windows 및 Microsoft Office 생산성 애플리케이션에 통합되어 일반적인 작업에 대해 고도로 상황에 맞는 도움말을 제공하는 [Microsoft 365 Copilot](https://www.microsoft.com/microsoft-365/enterprise/copilot-for-microsoft-365)과 같은 서비스를 사용하면 더 많은 목표를 달성할 수 있습니다. Microsoft 365를 사용하면 생성형 AI의 강력한 기능을 비즈니스 데이터 및 프로세스에 적용하는 동시에 기존 IT 인프라에 통합하여 관리 가능하고 안전한 솔루션을 보장할 수 있습니다.
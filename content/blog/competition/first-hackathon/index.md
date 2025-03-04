---
title: '첫 해커톤 회고록'
date: 2022-9-3 16:21:13
category: 'Competition'
draft: false
tags: ['해커톤', 'NextJS', '서버리스']
---

![](https://velog.velcdn.com/images/woog2roid/post/74852e87-9910-4306-aebc-23150b394168/image.png)

# 지원 동기

> _군대에서 첫 해커톤에 참여하게 되었다._

친했던 후배나 동기들이 개발 경험을 쌓아 여러 해커톤에 참여하는 모습을 보면서 참 멋있다고 생각했었는데, 나도 드디어 해커톤에 참가하게 되었다.

무려 휴가를 잘라 나가면서까지 해커톤의 모든 행사에 참여하였는데, 혼자서만 하는 프로젝트를 벗어나 다른 사람들과 소통하며 프로젝트를 한다는 점도, 이 분야의 새로운 사람들을 알아간다는 점도 기대가 되었다.

# 팀 리더 신청

> _첫 해커톤에서 팀 리더를 맡게 되었다. 내가 생각해도 좀 화끈한 결정인데, 그래도 나름의 합리적인 이유를 통해 팀 리더를 지원했다._

내가 생각했던 해커톤을 팀 리더로 참가해야 하는 이유로는, 팀 리더와 같은 자리에서 내 역량을 최대로 발휘할 수 있음을 경험적으로 알고 있었으며, 성향 상 자연히 팀 리더와 같은 역할을 맡곤 해서 팀 리더 자리가 부담스럽기 보단 더 익숙하고 편했다.

사실 처음엔 첫 해커톤이기도 하고 스스로에게 확신이 안 들어서 고민했는데, 막상 하게되면 잘 할 수 있을거라는 은근한 자신감과 스스로가 준비가 안되어있다고 걱정이 되면 걱정이 안 될 만큼 준비하자고 다짐하며 팀 리더를 신청하였다.

# 팀 빌딩

팀 리더들은 2분 동안의 자유 피칭을 하고, 팀원분들이 마음에 드는 팀 리더에게 연락해서 팀빌딩이 이뤄지는 형식이었다. 발표순서가 맨 처음이라서 상당히 떨면서 발표했던 기억이 있다.

![](https://velog.velcdn.com/images/woog2roid/post/fb312b17-50a4-41ec-8d20-2ab595fefc3e/image.png)
"서비스의 힘을 믿는 개발자"로 스스로를 소개하고 실제 주변 사람들과 이용했던 서비스들을 소개하였으며, 바라는 팀의 모습으로는 2박3일 간의 조금은 힘들 수도 있는 여정을 즐겁게 이겨낼 팀을 말했다.

결과는 상당히 많은 개발자분들이 지원해주셨고, 기획자와 디자이너분은 생각만큼은, 아니 거의 오지 않으셨다. 기획(1), 디자인(1), 개발(3)로 이상적인 팀 구성을 원하였는데 계획과는 조금 달랐다.

기획자와 디자이너 분들이 보기에는 내 피칭이 맘에 들지 않은걸까? 개발자 출신 팀 리더로써, 기획자와 디자이너 분들에 대한 이해도가 상대적으로 적었던 점이 결과로 드러난 것 같아 너무 아쉬웠다.

그래도 팀빌딩은 기획(1)+개발(4)로 마무리가 되었다. 거기에 기획자 분이 개발자 출신이라서 5개발자 팀이라고 팀명도 Devel5per로 지었다.

# 해커톤 본 행사 전까지

본 행사 까지는 1주일의 시간이 남았는데, 그 기간동안 개발자분들 간의 스택을 조율하고, 해당 스택으로 TodoList를 만들어 실습해보는 것이 목표였다.

백엔드 개발자들끼리의 논의 결과, supabase를 이용하여서 개발의 속도를 올리는 것이 해커톤에서 적합한 방법이고, 백엔드가 복잡해지게 되면 NestJS + TypeORM를 이용하기로 하였다. 또한 프론트엔드 스택으로는 NextJS(React) + Recoil + Emotion이 채택되었다.

사실 백엔드 개발자 두 명이 웹 풀스택 개발이 가능한 인원이라 가능했던 전략이 아닐까 싶다. 추가로 심사위원분들께서도 이 팀은 개발이 많이 되었다고 놀라셨는데, supabase의 영향과 개발자가 4명이라는 것도 한 몫 한듯 하다.

![](https://velog.velcdn.com/images/woog2roid/post/d9a6ca4e-3961-4e0b-94d6-da2d393c9134/image.png)

결국 나를 포함해서 모든 개발 팀원분들이 해당 스택으로 TodoApp을 만들어보는 것으로 해커톤 본 행사 전까지의 준비를 마쳤다. 사실 해커톤에서는 평소 익숙한 스택을 사용하는 것이 최선이라고 생각했는데, 팀원분들이 새로운 스택에 열의를 보이기도 했고, 개발시에도 더 빠른 속도를 낼 수 있다 생각이 들어서 팀 자체적으로 이런 작업을 진행했었다.

첫 해커톤에서 팀 리더를 맡는다는 것이 그래도 큰 도전이었던 지라, 최대한 준비를 많이하려고 노력했다. 프론트엔드 분들이 스택에 익숙해지도록 TodoApp을 제작하는 것을 도왔고, 미리 supabase도 사용해보았다. 그 외에도 미리 프로젝트의 폴더 구조 등을 정하는 등 실제 해커톤 행사장에서 생길 불필요한 시간소요를 줄이려고 노력했다. 이런 것들을 최대한 도와주는 것이 팀 리더로써 해커톤 본행사 전까지 할 수 있는 일이라는 생각이 들어서 더 열심히 한 것도 있었다.

# 대망의 해커톤 본 행사

## 1일차

### 아이디어 회의

> _"함께하는 사회를 위한 서비스"가 주제로 나왔다._

주제를 듣자마자 여러가지 아이디어들이 쏟아졌다. 하지만 떠오르는 아이디어들마다 구체화할수록 현존하는 서비스들과 차별점을 만들지 못하거나 해커톤에서 만들기 어려운 규모의 기획안이 나와서 절망하고 있던 와중에, 팀원들이 평소에 만들고 싶던 서비스를 그냥 말해보기로 하였다.

팀원분들 중 한 분이 평소에 환경 관련한 서비스를 만들고 싶어했다는 얘기를 듣고 주제와도 맞는 듯 하여 환경 관련한 서비스 쪽으로 논의가 진행되었다.

환경 운동에 "게이미피케이션"을 적용하여서 흥미요소를 돋구고, 인스타 스토리 기능을 통해서 멀리 퍼 나를 수 있도록 하는 서비스로 기획을 잡아갔다. 게이미피케이션 시스템에 흥미를 가진 유저들이 모이면 추후 환경 커뮤니티로써의 확장성도 생각해 볼 수 있어서, 꽤 괜찮은 기획이라고 보여졌다.

## 2일차

### 멘토링

2일차의 오전에는 해커톤의 후원기업에서 멘토 분들이 오셔서 서비스에 대한 멘토링을 하는 시간이 있었다. 우리팀에는 "VisualCamp의 석윤찬 대표님"과 "아루의 이명진 대표님"이 멘토로 와주셨다. 이 시간에 우리 서비스의 기획을 구체화하고 마무리할 수 있었다.

또한 대표님들 당 50분 정도의 시간 동안 멘토링이 진행되면서 우리 서비스에 대한 멘토링 뿐 아니라 진로 고민 혹은 대표님들의 경험을 들을 수 있어서 더 좋았다. 사실 스타트업의 대표님들과 이렇게 대화를 나눌 수 있는 기회가 언제 또 있을까? 참 좋은 기회였던 것 같다.

### 아이디어 구체화

> _"환경 운동을 하나의 사회의 트렌드로 만들자는 모토를 가진 서비스"로 정해졌다._

투두메이트의 사례를 어느정도 참고하여, 인스타그램 스토리 기능을 이용해서 입소문을 타며, 환경 운동에 관심이 없는 사람들조차도 조금씩 환경 운동에 관심을 갖게 할 수 있도록 하였다.

즉, 환경 운동을 좋아하는 사람들만의 어떤 커뮤니티가 아니라 SNS 입소문과 게이미피케이션을 접목해서, 평범한 사람들도 환경 운동에 관심을 갖게하고, 이를 하나의 문화로 만들자는 원대한 목표를 가진 서비스로 구체화가 되었다.

시민의식 수준이 높아짐에 따라 환경 운동에 대한 거부감이 없어진 것과 일명 "인스타 감성"에 맞게끔 특이하면서도 밝은 주제인 것이 SNS 마케팅을 주장할 근거가 되었다.

### 무한 개발

![](https://velog.velcdn.com/images/woog2roid/post/6e263cb2-5426-44cd-a92e-dc9cc1836f86/image.png)

> _무려 390대의 커밋을 찍으며 무한 개발에 들어갔다._

api폴더에 supabase관련 코드들을 넣어서 프론트엔드 개발자분들은 최대한 supabase 코드를 만지지 않고 호출해서 쓰는 식으로 하였고, 추후에는 백엔드 개발자들도 프론트엔드 개발에 들어가며 최대한 구현에 힘을 쏟았다.

## 3일차

### 발표

> _시간이 없어서 걱정했는데, 기대이상으로 발표를 잘 마칠 수 있었다._

![](https://velog.velcdn.com/images/woog2roid/post/93ef6ba4-a4e0-47eb-9f38-8a8a5e2772ce/image.jpeg)

사실 3일차 새벽부터 발표준비를 시작해서, 호텔 체크아웃까지 하다보니 시간이 여유있는 상황은 아니었다. 거기에 주요 기획 포인트들의 제안을 했다보니, 심사위원 분들이 보실 서비스 소개글 작성도 맡다보니 시간이 더 모자랐다.

태블릿을 들고 발표를 하다가 관중들과의 소통이 안되는 느낌이라 내려놓고, 중간부터 라이브로 발표를 했다. 대본 없이 발표를 하는 것에 어느정도 자신도 있었지만, 서비스 기획과정에서 내 제안들이 채택이 많이 되어서 말이 딱히 막히지 않기도 하였다.

팀원들이 발표가 정말 좋았다고 해주셔서 기분이 좋았었다. 후에 네트워킹 행사에서도 발표 잘 봤다는 말을 들을 때 마다 정말 기분이 좋았다.

### 시상식

![](https://velog.velcdn.com/images/woog2roid/post/5fdf938f-ca54-4818-982b-3f26e00d228a/image.JPG)
정말 상상하지도 못했는데, 5등상을 받았다.

![](https://velog.velcdn.com/images/woog2roid/post/b8a52475-472a-40a0-b8cd-3dfc1758c07f/image.JPG)
398commits로 잔디상도 받았다.

# 네트워킹

> _타 직군이 보는 이번 해커톤을 느껴보고, 개발자들끼리의 고민도 나누고, 마지막으로는 좋은 사람들을 만날 수 있어서 행복했다._

네트워킹 시간에는 다른 팀의 기획자와 디자이너 분들과의 소통을 해보았다. 타 직군 입장에서의 이번 해커톤은 어땠는지 너무 궁금했었다. 기획자나 디자이너가 보는 개발자의 느낌, 다른 팀은 어떤 식으로 타임라인이 흘러갔는지 등을 물어보며 타 직군에 대한 이해도도 높이고 싶었다.

또 같은 개발자 분들과의 소통도 재미있었다. 현업을 경험해보신 분도 있었고 이제 막 개발을 시작해보시는 분도 있었는데, 개발자로서의 고민을 털어놓을 수도 있었고 다른 이의 고민을 듣고 같이 생각해보기도 했다.

그리고 뒷풀이 행사에서는 정말 좋은 사람들을 만날 수 있었다. 그들과 깊은 얘기를 하며 친해질 수 있었다는 것에 감사하고, 이런 자리를 만들어준 운영진들한테도 정말 고마웠다.

# 글을 마치며

> _이번 해커톤은 나에게 정말 큰 의미를 안겨주었다._

우선, 나의 역량을 객관적으로 판단할 수 있는 계기가 되었다. 개발적인 능력 뿐 아니라, 팀 리더로서의 자질과 타 직군에 대한 이해 등 여러 가지를 객관적으로 돌아보는 계기가 되었고, 이는 내가 앞으로의 로드맵을 그리는데 큰 도움이 될 것 같다.

또한, 좋은 사람들을 많이 만날 수 있었다. 팀원분들도 정말 좋았고 네트워킹에서도 정말 좋으신 분들을 많이 만날 수 있었다. 특히 네트워킹에서 열정이 넘치는 분들을 보며 나도 동기부여를 엄청 받았는데, 이것이 또 서로에게 미치는 선한 영향력이 아닐까 생각해봤다.

또한, 협업경험을 처음 가져봤는데 군 전역 후 앞으로 있을 프로젝트에서 크게 도움이 될 것 같고, 웹 개발을 시작하고 바로 군 입대를 해서 정말 어떤 프로젝트에 최대한으로 몰입 해본 경험도 처음인데 값 비싼 경험을 한 것 같다. 첫 해커톤이어서 그런지 이번 해커톤은 글로 표현할 수 없을 만큼이나 큰 의미를 가진 해커톤이었던 것 같다.

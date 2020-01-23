FLASK TUTORIAL
=================

> 플라스크 프레임워크 튜토리얼입니다.
> [공식문서](https://flask.palletsprojects.com/en/1.1.x/tutorial/)


Contents
---------

1. [Project Layout](./docs/ch01.md)
2. Application Setup
3. Define and Access the Database
4. Blueprints and Views
5. Templates
6. Static Files
7. Blog Blueprint
8. Make Project Installable
9. Test Coverage
10. Deploy to Production
11. Keep Deploying
12. [Appendix 1 - Installation](./docs/ch12.md)
13. Appendix 2 - Quickstart


이 튜토리얼은 "Flaskr"이라고 불리는 기본적인 블로그 애플리케이션을 만드는 것입니다. (이 애플리케이션의) 사용자들은 등록하고, 로그인할 수 있고, 포스트를 작성할 수 있으며 작성된 포스트를 수정 및 삭제를 할 수 있습니다. 당신은, 다른 컴퓨터에 애플리케이션을 패키징하고 설치할 수 있을것입니다.

이 튜토리얼은 독자가 이미 파이썬을 어느 정도 능숙하게 사용할 수 있는 개발자라고 가정합니다. 파이썬에 능숙하지 않다면, [파이썬 튜토리얼 공식문서](https://docs.python.org/3/tutorial/)를 통해 파이썬을 먼저 배우는 것을 추천드립니다.

이 문서는 "Flask Framework"를 배우는데 "좋은 시작점"으로 설계되었기 때문에, "Flask"의 모든 기능을 커버하지는 않습니다. Flask가 수행 할 수있는 작업에 대한 개요는 [Quickstart](./docs/ch13.md)을 확인한 다음 문서를 통해 자세히 알아보십시오. 이 튜토리얼은 오로지, 파이썬과 플라스크에 의해 제공된 것을 어떻게 사용하는지에 대해서만 알려드립니다. 참고적으로 다른 프로젝트에서 필요할 수 있는 다양한 라이브러리들의 경우 [Extensions](https://flask.palletsprojects.com/en/1.1.x/extensions/#extensions)를 참고하세요.

"Flask"는 유연합니다. 이것은 특정 프로젝트 혹은 코드 레이아웃을 사용할 것을 요구하지 않습니다. 그러나 처음 시작할때는, 좀 더 구조화된 접근법이 더 유용할 수 있습니다. 즉, 이 튜토리얼에서는 약간의 boilerplate가 필요하지만, 새로운 개발자가 겪는 많은 일반적인 함정을 피하고 확장하기 쉬운 프로젝트 구조를 이용하여 진행합니다. 당신이 조금 더 "Flask"에 대해 익숙해졌을 때, 이 구조에서 벗어나 "Flask의 유연성"의 이점을 완전히 사용할 수 있을겁니다.

[Project Layout](./docs/ch01.md)에서 계속됩니다.
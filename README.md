# hoony0203.github.io

2020.09.28-10.01 인프런 강의 수강 
                    
                    (비전공자를 위한 개발자 취업 개론 http://asq.kr/2pxQn78w40whD)

2020.10.01       깃헙 jekyll 블로그 최초 제작 시도 + 시행착오 
                    
                    # ruby 설치, github desktop 설치, visual studio code 설치)
                    
                    # 1. _config.yml과 index.html만 복사하여 remote_theme 사용하는 방식 http://asq.kr/3ltKEG8JznrM - 실패
                      
                      2. github desktop으로 repo를 하드디스크에 연동 
                         테마 다운로드하여 연동된 폴더에 복사하여 붙여넣기 한 후 업로드 - 실패
                      
                      3. visual studio code로 git clone한 후 업로드하는 방식 https://murra.tistory.com/m/160 - 실패
                    
                    # localhost:4000상에서 실행시에는 작동하나 repository 업로드시 404 오류
                    
                    # clean blog 테마 등 적용 시도 했으나 실패. 
                                      
                    # 원인 분석       : 깃헙 페이지에서 지원하지 않는 테마 
                                       + Branch를 Main으로 설정하지 않아서 깃헙 페이지 활성화되지 않고 404 오류 발생
                    
                    # 배운 것         : 깃헙 페이지 비활성화시 세팅에서 블로그 이름 Rename 필요
                                       Branch는 반드시 Main으로 해야 깃헙 페이지 활성화됨.
                                       테마 적용 후에는 bundle install 명령어가 필요함. 
                                       커밋 후에 push해야 하드디스크상에서 깃헙으로 업로드됨
                                       pull은 깃헙 기준으로 하드디스크의 clone을 동기화함.
                    
                    # 더 알아봐야할 것과 궁금한 것 : gem의 설치 방식 및 bundel install시에 일어나는 프로세스
                                                 포스트 작성 방식
                    
2020.10.02       깃헙 페이지 활성화 후 minimal-mistakes 테마 적용 (참조 : https://opentutorials.org/course/3084/18891)
                    
                    # 1. _config.yml상의 사용자 정보 기록 
                      2. assets 폴더 생성 및 사진 등록 
                    
                    # 미구현 :  disuqus로 댓글 등록 '시도' (포스트가 보이지 않아 등록 여부 확인 불가)
                               파비콘 등록 방법 확인 
                               포스트 
                               좌측 메뉴 혹은 상단 메뉴
                               포트폴리오 

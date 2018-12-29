# 『이펙티브 자바 3판』(원서: Effective Java 3rd Edition)

<img src="https://github.com/WegraLee/effective-java-3e-source-code/blob/master/EJ3.jpg" width="640">

이 저장소는 『이펙티브 자바 3판』([인사이트](http://blog.insightbook.co.kr/), 2018)의 지원 사이트입니다.
한국어판의 [정오표는 여기](https://docs.google.com/document/d/1PB9DpFff24MtguO3DYKpW-n6xtSC7NbY5A5_Tm55qMs)에서 확인하실 수 있습니다.

---

## 새소식
:white_check_mark: **2018.11.12** - 출판사에서 이벤트를 진행하네요. [이펙티브 자바 '이판삼판' 이벤트](http://www.insightbook.co.kr/13113). 11월 21일까지입니다. ;)

:white_check_mark: **2018.11.05** - [정오표](https://docs.google.com/document/d/1PB9DpFff24MtguO3DYKpW-n6xtSC7NbY5A5_Tm55qMs)를 추가했습니다.

:white_check_mark: **2018.10.28** - 한국어판 출간에 맞춰 본 저장소의 예제 코드 한글화를 모두 끝마쳤습니다.

:white_check_mark: **2018.10.19** - 한국어판이 11월 1일에 드디어 출간됩니다. 원서보다 출간이 상당히 늦어진 점 죄송합니다. 그에 대한 보상이라긴 뭣하지만, 70여 개의 [원서 오류](https://docs.google.com/document/d/1mAeEgQu4H4ADxa03k7YaVDjIP5vJBvjVIjg3DIvoc8E/edit)를 바로잡을 수 있었고 최근 릴리스된 자바 11까지의 변경도 반영했습니다. 저자가 소스코드를 2018년 8월에서야 공개해서 제가 직접 준비하던 것은 버렸는데, 다행히 저자가 공개한 코드가 훨씬 깔끔하네요. ^^

**룰루랄라~ 책 사러 가기~** [예스24](http://www.yes24.com/24/Goods/65551284) | [교보문고](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788966262281&orderClick=LAH&Kc=) | [알라딘](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=171196410) | [인터파크](http://book.interpark.com/product/BookDisplay.do?_method=detail&sc.shopNo=0000400000&sc.prdNo=294626264&sc.saNo=003002001&bid1=search&bid2=product&bid3=title&bid4=001)

:white_check_mark: **2018.07.18** - [저자 직강 동영상](https://www.infoq.com/presentations/effective-java-third-edition?useSponsorshipSuggestions=true&utm_source=presentations_about_java&utm_medium=link&utm_campaign=java)이 공개됐습니다. 스트림과 람다에 집중하여 3판의 특징을 이야기하네요. 어느 분 말씀에 따르면 발표를 귀엽고 신나게 하신다고... ;)

## 『이펙티브 자바 3판』의 주요 특징

* 자바 7, 8, 9 신기능 반영
  * 함수형 인터페이스, 람다식, 메서드 참조, 스트림
  * 인터페이스의 디폴트 메서드와 정적 메서드
  * 제네릭 타입에서의 다이아몬드 연산자를 포함한 타입 추론
  * @SafeVarargs 애너테이션
  * try-with-resources 문
  * Optional〈T〉 인터페이스, java.time, 컬렉션의 편의 팩터리 메서드 등의 새로운 라이브러리 기능
* 2판까지는 제공하지 않던 [예제 소스코드](https://github.com/WegraLee/effective-java-3e-source-code/tree/master/src/effectivejava) 제공

## 한국어판에 가미된 특징

* 자바 10과 11에서의 변경 사항 반영(본문 내용과 관련된 사항에 한함!)
* [번역 용어 해설](https://docs.google.com/document/d/1Nw-_FJKre9x7Uy6DZ0NuAFyYUCjBPCpINxqrP0JFuXk/edit) 제공
* API 문서화 설명(아이템 56)에 영어용과 국문용 모두 수록
* 본문부터 색인까지, 읽기 쉽도록 원서보다 신경 쓴 편집

## 추천사
>"고급 자바 개발자로 거듭나고 싶은 분들이라면 꼭 보길 바라며, 대세가 되고 있는 함수형 프로그래밍을 자주 사용하는 실무 개발자에게도 적극 추천합니다."
**_나상혁**, LG전자 선임연구원, LG전자 SW Colleage JAVA 사내 강사

>"이 책이 유명한 만큼 번역에 대한 부담도 컸을 텐데 책임감을 가지고 정성을 기울여 작업했다는 게 느껴집니다. 조슈아 블로크의 여전한 통찰력에 이복연 님의 친절한 번역이 더해졌습니다."
**_정상혁**, 네이버 재직, [『네이버를 만든 기술, 읽으면서 배운다: 자바편』](http://www.yes24.com/24/Goods/16813496) 공저자

>"자바 8이 나오자 자바 개발자들이 하나 같이 『이펙티브 자바 3판』이 언제 나오는지 궁금해했습니다. 대폭 개선되었던 자바 6 때 『이펙티브 자바 2판』이 나왔던 것처럼 3판이 나올 때가 되었기 때문입니다. 『이펙티브 자바』 없는 자바 개발은 상상할 수 없으니까요."
**_박성철**, 우아한형제들 재직

>"『이펙티브 자바』는 자바 언어의 초창기부터 대가의 목소리를 들을 수 있었던 훌륭한 책입니다. 3판에서는 자바 9의 '플랫폼 모듈화'를 다룬 내용을 포함하여 더욱 새로워졌네요. 깊이 있게 자바를 공부하고 싶은 개발자와 학생에게 추천합니다."
**_유동환**, [『RxJava 프로그래밍』](http://www.yes24.com/24/goods/45506284) 공저자, [『Java 9 모듈 프로그래밍』](http://www.yes24.com/24/Goods/60232732) 역자

## 기타 유용한 정보

* 이 번역서와 직접적인 관련은 없습니다만, 네이버 랩스의 백기선 님이 이 책의 원서를 기반으로 [동영상 강의](https://www.youtube.com/watch?v=X7RXP6EI-5E&list=PLfI752FpVCS8e5ACdi5dpwLdlVkn0QgJJ)를 시리즈로 진행 중입니다. 책만 읽기 따분한 분, 혹은 활자가 아닌 생생한 강의를 듣고 싶은 분께 강추합니다!
* 국내 자바 개발자들과 소통하며 도움을 얻고자 하시는 분은 [Javawocky](https://www.facebook.com/groups/javawocky/)를 찾아주세요. 이 책의 번역 용어를 정하는 데도 많이 도와주셨습니다.
* 진지하게 책 저술 혹은 번역에 관심 있으신 분은 [책쓰는 프로그래머 협회](https://www.facebook.com/groups/techbookwriting/)에 들러봐주세요. (제가 쓴 [번역 가이드](https://www.slideshare.net/wegra/ss-52826286)와 [집필 가이드](https://github.com/hanbitmedia/Writing-IT-Books)도 한번 살펴보세요~ ^^)

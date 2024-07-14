#스프링부트3 시작하기

- 스프링은 엔터프라이즈 애플리케이션을 쉽게 개발할 수 있도록 도와주는 프레임워크이다.
- IoC는 제어의 역전, DI는 의존성 주입을 뜻한다.
- 스프링 부트는 스프링을 더 빠르고 쉽게 사용하기 위한 도구로서 스타터와 자동 구성을 제공한다.
- 애너테이션은 자바 소스 코드에 추가하는 표식이다. 보통 @ 기호를 앞에 붙여서 사용하며, JDK1.5 버전부터 사용할 수 있습니다. 애너테이션은 다양한 목적으로 사용하지만, 메타데이터(데이터에 대한 설명을 담고 있는 데이터)의 비중이 가장 크다.
- @SpringBootApplication은 스프링 부트 관련된 설정을 하는 @SpringBootConfiguration, 사용자가 등록한 빈을 읽고 등록하는 @ComponentScan, 자동설정으로 등록되는 빈을 읽고 등록하는 @EnableAutoConfiguration으로 이루어져있다.
- @Component 애너테이션이 있는 클래스는 빈으로 등록되며, @Controller, @RestController, @Configuration, @Repository, @Service 모두 @Conponent 애너테이션을 가지고 있습니다. 때에 따라 알맞은 애너테이션을 선택해야 합니다.

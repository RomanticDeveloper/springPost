# springPost


> 프로젝트명 : 스프링 기초 연습  Post (FastCampus)
> 시작일자 : 2021.11.27
> 작성자 : Ro.D



1. JSON 데이터 형태
1) 
String : value
number : value
boolean : value 
object : value {}
array : []
2) Snake Case : "phone_number" : "value"
3) Camel Case : "phoneNumber" : "value"
4) ex) 
{
	"phone_number" : "010-8888-8888",
    "age" : 19,
    "isAgree" : false,
    "account" : {
    "email" : "asdf@gmail.com",
    "password" : "1234",
    }
}
2. 통신데이터 간의 case 프로토콜이 다른 경우
1) @JsonProperty Dto 상 변수 선언시 어노테이션을 사용하여 리퀘스트의 키값과 맵핑시켜줌!
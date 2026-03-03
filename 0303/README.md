

## 과제 제출 코드 

📌 요구사항

- 불변 변수 studentName에 본인의 이름을 넣으세요.
- 가변 변수 score에 100을 넣고, 다음 줄에서 95로 변경하세요.
- 문자열 템플릿으로 출력: "[이름]님의 점수는 [점수]점입니다."
- studentName이 null이 될 수 있다고 가정하고 길이를 안전하게 출력하세요.

```
fun main() {
    val studentName: String? = "정원희"
    var score: Int = 100
    score = 95
    println("${studentName}님의 점수는 ${score}점입니다.")  // println("$studentName 님의 점수는 $score 점입니다")
    println("이름 길이: ${studentName?.length ?:0}")
}
```

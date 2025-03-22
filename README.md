Parser 개발
각 문자 변환 메서드를 매칭 하는 알고리즘 구현 
```kotlin
fun main() {
    print("문자열 입력: ") // 입력받고
    val input = readLine() ?: "" // readline
    
    val asciiCodes = input.map { it.code }  // 문자 → 아스키코드 변환 과정 
   
    println("아스키 코드: $asciiCodes")
}

```

```kotlin
fun main() {
    val charA: Char = 'A'
    val asciiValue: Int = charA.code

    println("Character: $charA")
    println("ASCII Value: $asciiValue")
}
```
![image](https://github.com/user-attachments/assets/ce9910e7-1358-4f43-a2f4-8ceb53c9b2de)

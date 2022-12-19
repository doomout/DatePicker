# DatePicker 
날짜와 시간을 선택할 수 있게 해주는 객체  

스위프트 문법   
1. 배열 : 하나의 변수 이름으로 여러 개의 데이터를 저장할 수 있는 공간을 의미한다.    
예) var name: [String] = ["이름", "나이", "주소", "취미"]  
    var score: [Int] = [100, 90, 80, 70, 50]  

2.빈 배열을 선언하고 값을 추가하는 방법  
예) var name = [String]()  
    var score = [Int]()  
    
    name.append("슈퍼맨")  
    name.append("배트맨")  
    
    score.append(100)  
    score.append(50)  
    
3. for 문 : 특정 코드를 특정한 조건을 만족하는 만큼 반복하는 기능  
예) for 변수 in Range {  
      반복할 코드  
    }  
      
    //변수 i를 0~9까지 반복하면서 print(i)를 출력한다.  
    for i in 0...9 {     
      print(i)  
    }   
    
    //i를 0부터 10보다 작을 동안까지 반복하며 print(i)를 출력한다.  
    for i in 0..<10 {  
      pirnt(i)  
    }  

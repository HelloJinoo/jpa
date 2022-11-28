# ✏️ 설계 내용 / 이유
 - 독립적인 회원, 메뉴, 주문/결제 시스템 
 - MSA아키텍처 구성 
   1. Spring Cloud Gateway (Routing 및 Filter)
   2. Spring Cloud Eureka (Discovery 및 Registry)
   3. Member, Menu, Order Service (요청 처리) 
   4. H2 Database (Local 개발 및 테스트용)
   
 - 이유 :
   1. 대용량 트래픽 분산 처리  
   2. 독립적으로 배포 가능  
   3. 트래픽이 많은 서비스의 추가적인 확장 용이
 
# 📌 핵심 문제 해결 전략, 분석 내용

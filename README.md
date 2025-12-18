# Parking-Guard
세그먼테이션 기반 객체 탐지를 활용한 불법 주·정차 민원 자동화 시스템 입니다.
---

기존 불법 주·정차 민원은 사람이 직접 확인하고 판단해야 하는 구조라 시간도 오래 걸리고, 처리 부담도 크다는 점에서 출발했습니다.  
이 프로젝트에서는
> “AI가 1차로 판단해주면 어떨까?”  

라는 질문에 답해보는 것을 목표로 했습니다.

---

객체 탐지 모델을 선정할 때 크게 3가지로 분류하여 비교 실험했습니다.

<table>
  <tr>
    <td align="center">
      <img width="291" height="284"
           src="https://github.com/user-attachments/assets/57daabdb-5787-4298-be11-b835e3121689" />
      <br/>
      <b>YOLO-SEG</b>
    </td>
    <td align="center">
      <img width="291" height="284"
           src="https://github.com/user-attachments/assets/6d48fa79-c95d-4012-9962-7c5be391492b" />
      <br/>
      <b>YOLACT</b>
    </td>
    <td align="center">
      <img width="291" height="284"
           src="https://github.com/user-attachments/assets/7cfad2ae-5b81-424a-97ef-31a993094a5a" />
      <br/>
      <b>Mask R-CNN</b>
    </td>
  </tr>
</table>

최종적으로 **YOLOv11x-seg** 모델로 선정했습니다.

---
# 애플리케이션 실행 화면
<img width="410" height="471"
     src="https://github.com/user-attachments/assets/ea894205-8c64-4d76-9262-8b4eb39a588f" />




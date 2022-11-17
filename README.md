# Korean_pronunciation_analysis
#### 외국인의 한국어 발음 오류 패턴 비교 분석입니다.
#### 외국인 학습자들의 한국어 발화 데이터셋을 이용하여 권역별(국가별) 발음 오류 패턴을 비교 분석하는 task 입니다.
#### Chinese, English, Spanish 의 L1 외국인들의 한국어 발음 오류 패턴을 분석하였습니다.

### * 한국어 음소셋
<img width="715" alt="제목 없음" src="https://user-images.githubusercontent.com/59900689/202398402-1fe81a92-678e-448b-9ab7-d06c6b4c0a98.png">
![image](https://user-images.githubusercontent.com/59900689/202398523-3d5be012-dd62-4d59-8303-450fb0a64988.png)

### * txt 파일로 제공된 데이터
![image](https://user-images.githubusercontent.com/59900689/202400329-14a76622-74ba-4ad1-97fe-e430da7dc2eb.png)

# 데이터 정제
파일 이름으로부터 성별, 연령, 국적, 발화 난이도, 단락/문장/단어 를 추출하여 데이터프레임으로 변경
![image](https://user-images.githubusercontent.com/59900689/202400837-c4b4b4bf-32e3-4d1f-8bf7-f2a6bbc26b49.png)

## 데이터 발화 샘플인 ref, 정답 음소 ans, 음소인식기를 돌린 결과 음소 rec 에 대한 분석으로 CSID 추출 
- correct, substitution, insertion, deletion
![image](https://user-images.githubusercontent.com/59900689/202401185-3cb2648d-25cd-494e-beb5-47170efcfd87.png)
![image](https://user-images.githubusercontent.com/59900689/202401224-ef0a2976-ae47-491a-a7d2-cd62aec27394.png)
![image](https://user-images.githubusercontent.com/59900689/202401270-3cd5694a-a281-41bf-86bf-b4d3575caf4d.png)

# 데이터 시각화 - PowerBI 이용


https://user-images.githubusercontent.com/59900689/202401504-e6ba1cba-8d1a-43da-b628-59f7da9737de.mp4


## Chinese


https://user-images.githubusercontent.com/59900689/202401537-a21396a4-be3a-47e3-93dd-9cf07097c973.mp4


## Spanish


https://user-images.githubusercontent.com/59900689/202401556-09cf4cae-d814-4b7b-85d6-454301125276.mp4


## English


https://user-images.githubusercontent.com/59900689/202401583-00736087-3b9c-4b33-a184-f453695b63fe.mp4


# 발음 오류 패턴 분석
- 모국어 영향에 따른 음소 단위의 치환, 삭제, 삽입 오류 패턴 분석
![image](https://user-images.githubusercontent.com/59900689/202401684-913efd6e-1268-4bfb-ada7-bcd0a2e0a78d.png)

## 1) English : deletion of N
![image](https://user-images.githubusercontent.com/59900689/202402035-ebe560b5-6207-4f51-bb77-9be153c8df96.png)
  
  ![image](https://user-images.githubusercontent.com/59900689/202402448-32325195-784f-4510-b3a0-2c0544f08c8a.png)


## 2) English : substitution of GG to G
 ![image](https://user-images.githubusercontent.com/59900689/202402610-7aacf73e-e02c-45f2-b4aa-2e954f203d33.png)
  
## 3) Spanish : insertion of M
  ![image](https://user-images.githubusercontent.com/59900689/202402674-c4e078fe-2d76-4557-a299-01a946fcb7dc.png)


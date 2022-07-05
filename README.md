# RealCheck shopping

- **목차**

## **프로젝트 소개**

### 개요

- 회사 RealCheck 라는 비트코인을 안전하게 보관할 수 있는 카드를 판매하는 쇼핑몰을 제작했습니다.

### 담당

- 디자인
- 화면구현(Front-End)

### 사용 기술

- Javascript
- HTML
- CSS
- jQuery

### 사용 툴

- Visual Studio

---

# 0. Navigation

### **Navigation - 전체화면**

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled.png)

### **Navigation - 세부설명**

![Group 179.png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Group_179.png)

- 1번 버튼 을 클릭시 **메인페이지**로 이동합니다
- 2번 버튼 을 클릭시 **상품구매** 페이지로 이동합니다.
- 3번 버튼 을 클릭시 **상품주문내역** 페이지로 이동합니다.
- 4번 버튼 을 클릭시 **상품 설명서** 페이지로 이동합니다.

---

# 1. 메인 페이지

## 1) 메인페이지 1번 Section

### **메인 페이지 1번 Section -전체화면**

![image 130.png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/image_130.png)

### **메인 페이지 1번 Section - 세부설명**

![Group 178.png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Group_178.png)

- 1번 모양의 버튼을 클릭시 안의 내용 이 변경돼서 출력 됩니다.

---

## 2) 메인페이지 2번 Section

### **메인 페이지 2번 Section -전체화면**

![image 131.png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/image_131.png)

### **메인 페이지 2번 Section - 세부설명**

- 카드의 전체적인 모양과 장점 소개페이지입니다.

---

## 3) 메인페이지 3번 Section

### **메인 페이지 3번 Section -전체화면**

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled%201.png)

### **메인 페이지 3번 Section - 세부설명**

![Group 180.png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Group_180.png)

- 판매하고있는 상품을 보여주는 섹션입니다.
- 1번 DIV 클릭시 해당 상품의 구매페이지로 이동합니다.

---

## 4) 메인페이지 4번 Section

### **메인 페이지 4번 Section -전체화면**

![image 133.png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/image_133.png)

### **메인 페이지 4번 Section - 세부설명**

![Group 181.png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Group_181.png)

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled%202.png)

- 고객센터 페이지입니다.
- 1번 클릭시 발송되었다는 alert 창이 나타납니다.

---

# 2. 상품 상품 선택 페이지

### 상품 상품 선택 페이지 **-전체화면**

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled%203.png)

### 상품 상품 선택 페이지 **- 세부설명**

![Group 182 (1).png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Group_182_(1).png)

- 수량이 다른카드를 먼저 3번으로 선택합니다.
- 코인을 담은카드를 수량을 1번 input 칸으로 지정합니다.
- 수량을 지정한후 2번 버튼을 클릭시 card_count 으로 제출하면 DB장바구니 테이블에 데이터가 입력됩니다.

---

# 3. 장바구니

## 1) **장바구니 -전체화면**

### 장바구니 데이터가 있을시

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled%204.png)

### 장바구니 데이터가 없을시

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled%205.png)

## 2) **장바구니- 세부설명**

### 장바구니 데이터가 있을시

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled%206.png)

- 상품의 데이터는 DB에서 JSON형식으로 받아옵니다.
- 1번 버튼클릭시 상품이 전체 선택이 됩니다.
- 2번 버튼 클릭시 해당 데이터는 삭제됩니다.
- 3번 버튼 클릭시 체크박스를 선택한 상품이 구매하기 페이지로 넘어갑니다.

### 장바구니 데이터가 없을시

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled%207.png)

- 1번버튼 클릭시 상품 구매하기 페이지로 이동합니다.

---

# 4. 결제페이지

### 결제페이지**-전체화면**

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled%208.png)

### 결제페이지 **- 세부설명**

![Group 184.png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Group_184.png)

- 1번 radio 버튼을 클릭시 결제정보의 대한 input 값들이 나타납니다.
- 2번 버튼을 클릭시  input 값안에 있는 정보들이 결제완료 페이지로 이동합니다.

---

# 5. 결제완료

### 결제완료 **-전체화면**

![image 153.png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/image_153.png)

### 결제완료 **- 상세설명**

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled%209.png)

- 1번 버튼 클릭시 상품이용 방법 페이지로 이동합니다
- 2번 버튼 클릭시 메인 화면으로 이동합니다.
- 3번 버튼 클릭시 주문 내역 확인하기로 이동합니다.

---

# 6. 주문조회

### 주문조회 **- 전체화면**

![image 154.png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/image_154.png)

### 주문조회 **- 상세설명**

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled%2010.png)

- 1번 input 칸에 주문 번호를 입력합니다.
- 2번 버튼으로 1번에 입력한 주문 번호를 조회합니다.
- 3번 버튼을 클릭하면 메인으로 돌아갑니다.

### 주문 번호 조회 했을 시 화

![image 155.png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/image_155.png)

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled%2011.png)

> ㆍ배송확인 버튼 클릭시 배달중인 택배사 배송조회 페이지로 이동합니다.
> 

---

# 7. 상품설명서

### 결제페이지**-전체화면**

![image 161.png](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/image_161.png)

### 결제페이지 **- 상세설명**

![Untitled](RealCheck%20shopping%20746c4e5b50004c4e8e8064d4522d8cbd/Untitled%2012.png)

- 1번 nav 클릭시 해당 페이지로 이동합니다.

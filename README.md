๐ ๊ทธ๋ฆฐ๋ํ๊ต(Green university)
====================

* ๊ทธ๋ฆฐ๋ํ๊ต ์ฑ์  ๊ด๋ฆฌ ํ์ด์ง ๊ตฌํ

๐ธ ์๊ฐ
------------

* ํ๋ก์ ํธ๋ช : ๊ทธ๋ฆฐ๋ํ๊ต(Green university)
* ์ํ ๊ธฐ๊ฐ  : 2022.06.10 ~ 2022.06.24
* ๊ธฐ๋ฅ ๊ตฌํ  : ํ์๊ฐ์, ๋ก๊ทธ์ธ, ์์ด๋/๋น๋ฐ๋ฒํธ ์ฐพ๊ธฐ, ํ์์ ๋ณด ์์ , ์ฑ์  ์กฐํ, ์์๋ชฉ๋ก ์กฐํ
* ์ค์ ๊ธฐ๋ฅ
  * [JAVA]Mybatis-mvcํจํด์ ์ด์ฉ
  * GUI ํ๋ก๊ทธ๋๋ฐ - AWT ์ปดํฌ๋ํธ, Swing์ปดํฌ๋ํธ ์ฌ์ฉ
  * ํ์๊ฐ์์ ๋๋ค์ผ๋ก ์ ์ ๋ถ์ฌ
  ```
  public void setKorGrade(String korGrade) {
		int random = (int)(Math.random()*100)+1;
		if("".equals(korGrade))
			this.korGrade = Integer.toString(random);
		else
			this.korGrade = korGrade;
	}
  ```
  * CommonPopup.java ํ์ผ์ ๋ณ๋๋ก ๊ด๋ฆฌํ์ฌ Popup ์ฐฝ์ ํธ๋ฆฌํ๊ฒ ์ฌ์ฉํ๋๋ก ๊ตฌํ
 
   ```
    public CommonPopup(int num) {

      message = null;
      int messageIcon = ERROR_MESSAGE;

      switch (num) {
      case 1:
        message = "๋น๊ฐ์ ์๋ ฅํ  ์ ์์ต๋๋ค.";
        break;

            case 11:
        message = "๋น๋ฐ๋ฒํธ๊ฐ ์ผ์นํ์ง ์๊ฑฐ๋ ํด๋น ์์ด๋๊ฐ ์กด์ฌํ์ง ์์ต๋๋ค.";
        break;
          }
     }
     ```
  
   ``` 
    btn_login.addActionListener(new ActionListener() {
			@Override
			public void actionPerformed(ActionEvent e) {
				
				String sid = id.getText();
				String spw = new String(pw.getPassword());
				if(sid.equals("") || spw.equals(""))
				{
					new CommonPopup(1);		// "๋น๊ฐ์ ์๋ ฅํ  ์ ์์ต๋๋ค."
				}
				else
				{
					boolean loginTF = loginCheck();
					if(loginTF)
					{
						dispose();
						new MemberInfoWindow(id.getText());
					}
					else
					{
						new CommonPopup(11);	// "๋น๋ฐ๋ฒํธ๊ฐ ์ผ์นํ์ง ์๊ฑฐ๋ ํด๋น ์์ด๋๊ฐ ์กด์ฌํ์ง ์์ต๋๋ค."
					}
				}
			}
		});
  ```
๐ธ ๊ฐ๋ฐ ๊ณผ์ 
------------
* ํฐ์คํ ๋ฆฌ์ ์ ๋ฆฌ-์ฒซ ์์ URL: <https://developer-jeri.tistory.com/18> 

๐ธ๊ตฌํ ์ด๋ฏธ์ง
------------
* ๋ก๊ทธ์ธ

![image](https://user-images.githubusercontent.com/102607435/223306626-52d1f4a0-eb0e-4b95-b7ae-768db8fac490.png)

* ํ์๊ฐ์

<img src="https://user-images.githubusercontent.com/102607435/223306770-23aa592a-b59b-4f15-972a-dfbd97afd05d.png" width="405" height="320">

![image](https://user-images.githubusercontent.com/102607435/223307897-e687cdbc-6eff-414a-9522-50f29e98775e.png)

![image](https://user-images.githubusercontent.com/102607435/223307975-c5eb09c5-3dfa-4562-be73-dceadcb7e6c0.png)

![image](https://user-images.githubusercontent.com/102607435/223308039-e33f7d5d-4a1f-4430-9a3c-be20d4c6e75a.png)

* 

![image](https://user-images.githubusercontent.com/102607435/223307194-f0368b55-6a42-466b-ab37-c66583e58bb5.png)

* ํ์์ ๋ณด 

![image](https://user-images.githubusercontent.com/102607435/223307307-c47b1188-1b03-48ea-8085-341b8f3bf93f.png)

* ์ฑ์ ๊ด๋ฆฌ

![image](https://user-images.githubusercontent.com/102607435/223307371-9db28d9b-0f08-42b2-9368-8f1abc815885.png)




 
 
